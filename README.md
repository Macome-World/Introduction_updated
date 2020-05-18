
* 
{
  box-sizing: border-box;
}

/* Style the header */
header 
{
  background-color: #666;
  padding: 5px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Container for flexboxes */
section 
{
  display: -webkit-flex;
  display: flex;
}

/* Style the navigation menu */
nav 
{
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul 
{
  list-style-type: none;
  padding: 0;
}

/* Style the content */
article 
{
  -webkit-flex: 3;
  -ms-flex: 3;
  flex: 3;
  background-color: #f1f1f1;
  padding: 10px;
}

/* Style the footer */
footer 
{
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the menu and the content (inside the section) sit on top of each other instead of next to each other */
@media (max-width: 600px) 
{
  section 
  {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
}

body
{
    background-color: whitesmoke;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

h1
{
  color: rgb(255, 255, 255); 
}

button
{
    background-color: white;
}

a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
  text-shadow: rgb(209, 15, 57);
}

a:visited 
{
  color: blue;
  background-color: transparent;
  text-decoration: none;
}

a:hover 
{
  color: red;
  background-color: transparent;
  text-decoration: underline;
}

a:active 
{
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
a:link, a:visited 
{
  background-color: lightblue;
  color: black;
  padding: 10px 20px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  border: 1px solid blue;
}

a:hover, a:active 
{
  background-color: white;
}

table, th, td 
{
  border: 1px solid blue;
  text-align: center;
  border-collapse: unset;
  border-spacing: 3px;
  padding: 5px;
  font-size: 15px;
}

.T05
{
  background-color: lightgreen;
  padding: 15px;
}

.T06
{
  background-color: lightgreen;
  padding: 15px;
}

table
{
  width: 50%;
  
}

caption
{
  text-align: left;
}

th
{
  background-color: black;
  color: white;
  
}

tr#T01
{
  background-color:lightblue;
  color: black;
  
}

tr#T02
{
  background-color: rgb(240, 230, 230);
  color: rgb(11, 13, 14);  
}

tr#T03
{
  background-color: lightblue;
  color: black  
}

tr#T04
{
  background-color: rgb(240, 230, 230);
  color: rgb(11, 13, 14);  
}

div#Academic
{
  background-color: lightcyan;
  border: 1px solid blue;
  padding: 5px;
  
}

