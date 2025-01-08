# pacific-
* { box-sizing: border-box; }
 body { 
background-color: #90C7E3;
color: #666666;
font-family: Verdana, Arial, sans-serif;
margin: 0;
}
#wrapper { 
background-color: #FFFFFF;
}
header { 
background-color: #002171;
color: #FFFFFF;
font-family: Georgia, serif;
padding: 1em;
}
header a { text-decoration: none; }
header a:link       { color: #FFFFFF; }
header a:visited { color: #FFFFFF; }
header a:hover     { color: #90C7E3; }
h1 {  
font-size: 1.5em;
text-align: center;
}
h2 { color: #1976D2;
font-family: Georgia, serif; 
}
h3 { font-family: Georgia, serif; }
nav { background-color: #FFF;
font-size: 1.2em;
text-align: center;
}
nav a { text-decoration: none; }
nav a:link       { color: #5C7FA3; }
nav a:visited { color: #344873; }
nav a:hover     { color: #A52A2A; }
nav ul { 
display: flex;
flex-direction: column;
list-style-type: none; 
margin: 0;
padding: 0; 
}
nav li { 
border-bottom: 1px solid #344873;
padding: .5em 1em;
width: 100%; 
}
main { display: block; 
padding: 0 1em;
}
dt { color: #002171;
font-weight: bold;
}
.resort { color: #1976D2;
font-size: 1.2em;
}
#homehero { height: 300px;
background-image: url(coast.jpg);
background-repeat: no-repeat;
background-size: 200% 100%; 
 }
#yurthero { height: 300px;
background-image: url(yurt.jpg);
background-repeat: no-repeat;
background-size: 200% 100%; 
 }
#trailhero { height: 300px;
background-image: url(trail.jpg);
background-repeat: no-repeat;
background-size: 200% 100%; 
}
#reshero { height: 300px;
background-image: url(ocean.jpg);
background-repeat: no-repeat;
background-size: 200% 100%; }
#mobile  { display: inline; }	
#desktop { display: none; }
section {  
padding-left: .5em;
padding-right: .5em;
}			
footer { background-color: #FFF;
font-size: .70em;
font-style: italic;
padding: 1em;
text-align: center;
}
table { margin: auto;
width: 90%;
border: 1px solid #3399CC; 
border-collapse: collapse; 
}
td, th { padding: 5px;
border: 1px solid #3399CC;
}
td { text-align: center; }
.text { text-align: left; }
tr:nth-of-type(even) { background-color: #F5FAFC; }
form { 
display: flex;
flex-direction: column;
padding-left: 1em;
width: 80%; }
input, textarea { margin-bottom: .5em; }
@media (min-width: 600px) { 
		h1 { font-size: 2em;
            	letter-spacing: .25em;		}
		nav ul { flex-flow: row nowrap; 
		       justify-content: space-around;
			   padding-right: 2em; }
		nav li { border-bottom: none;
		      width: 12em; }
		section { padding-left: 2em;
		        padding-right: 2em; }
		#flow { display: flex; 
		        flex-direction: row; }
		#mobile { display: none; }
		#desktop { display: inline; }
		#homehero, #yurthero, #trailhero, #reshero { background-size: 100% 100%; }
		form { width: 60%;
		      display: grid;
			  grid-gap: 1em; gap: 1em;
			  grid-template-columns: 10em 1fr; }
		input[type="submit"] { grid-column: 2 / 3; width: 9em; }
}
@media (min-width: 1024px) { 
		body { background-image: linear-gradient(to bottom, #FFFFFF 20%, #90C7E3 60%, #FFFFFF 100%);
		  }
		nav ul { padding-left: 10%;
		       padding-right: 10%; }
		#wrapper { margin: auto;
		          width: 80%; }	
}				  
