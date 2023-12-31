# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
home.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:plum;
            color:purple;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:45%;
        }
        a{
            color:purple;
            text-decoration: none;
        }
        a:hover{
            color:yellow;
            cursor:pointer;
 }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
      
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: plum;
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:plum;
        
        }
        .heading1{
            color:purple;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:plum;
            text-align: justify;
            font-size: 30px;
            margin-left: 30px;
        }
        .edge{
            padding-left: 900px;
        }
        .box{
            text-align: center;
        }
 p{
            color:purple;
            text-align: center;
        }
    
        .bottomdiv{
 background-color:plum;
            color:purple;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 210px;

        }
        table{
            margin-left: 40px;
        }
    </style>
</head>
<body background="coverpage.jpeg">
    <div class="header">
        <nav id="nav">
            <h1>
              METASOFT SOLUTIONS 
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="services.html" target="_blank">Services  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
 	"Welcome to Metasoft company,where innovation meets excellence!"

<br>
 	Join us on this exhilarating tech ride!					<b></i></pre></div>
        <div class="edge">
            <div class="box">
            <h1 class="heading1">LOGIN HERE</h1>
            <br>
            <br>
            <form>
                <table cellpadding="15px" cellspacing="15px">
                    <tr>
                        <td>
                           <p> Username:</p>
                        </td>
                        <td>
                            <input type="email" name="name" placeholder="Enter a Email">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <p> Password:</p>
                        </td>
                        <td>
                            <input type="password" name="pwd" placeholder="Enter a Password">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" value="LOGIN" style="background-color: purple; color:white;">
                        </td>
                    </tr>
                </table>
                
            </form>
            </div>
        </div>
    <div class="bottomdiv">
        <p>Designed and Developed by Hari Priya (23013964)</p>
    </div>
</body>
<html>

service.html

 
 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Products</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:purple;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:60%
        }
        li{
            color:purple;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
 input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:purple;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:white;
            cursor:pointer;
        }
        a{
            color:purple;
            text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:plum;
        }
      p{
            color:purple;
            text-align: center;
        }
   b{
            width: 300px;
            height: 200px;
        }
    h1{
            color:purple;
            text-align: center;
        }
        .bottomdiv{
 background-color:plum;
            color:purple;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 375px;

        }
    </style>
</head>
<body background="coverpage.jpeg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">METASOFT SOLUTIONS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="services.html" target="_blank">Services  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">SERVICES</h1>
        <br>
        <br>
        <br>
        <br><br><br><br>
        <div class="product">
           

               <img src="ai.jpeg">
               

               <img src="aws.jpeg">

               <img src="crm.jpeg">

               <img src="ui.jpeg">

               <img src="tech.jpeg">

               

            </div>
        </div>
    </div>
    <div class="bottomdiv">
        <b>Designed and Developed by Hari Priya (23013964)</b>
    </div>
</body>
</html>

pereson.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Employees</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:purple;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:purple;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:purple;
text-decoration: none;
        }
        a:hover{
            color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 50px;
            padding-bottom: 10px;
            text-align: center;
            color:plum;
        }
        .bottomdiv{
            background-color:plum;
            color:purple;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 315px;

        }
        img{
            border-radius: 50%;
            width: 190px;
            display: inline;
            padding:3px;
            
        }
        .person{
            margin:100px;
            text-align: center;
        }
        b,p{
            color:lightpink;
            text-align: center;
        }
        c{
            color:purple;
            text-align: center;
        }
</style>
</head>
<body background="coverpage.jpeg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">METASOFT SOLUTIONS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="services.html" target="_blank">Services  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">EMPLOYEES</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="mypic.jpeg" class="MyPic">
                </td>
               
                <td>
                   <img src="henry.jpeg" class="Henry Cavill">
                </td>
                <td>
                    <img src="emma.jpeg" class="Emma watson">
                </td>
                <td>
                    <img src="chris.jpeg" class="Chris Hemsworth">
                </td>
		<td>
		    <img src="reyhan.jpeg" class="Reyhan">
		<td>
			<img src="hath.jpeg" class="Annie Hathway">
		<td/>
            </tr>
            <tr>
                <td>
                    <b>Atchaya</b>
                    <p>CEO,chair person</p>
                </td>
                
               
                <td>
                    <b>Henry Cavill</b>
                    <p>CEO,Founder</p>
                </td>
                <td>
                    <b>Emma watson</b>
                    <p>CEO,Co-Founder</p>
                </td>
                <td>
                    <b>Chris Hemsworth</b>
                    <p>The Director</p>
                </td>
		<td>
	  	    <b>Reyhan</b>
		    <p>Asst.Director</p>
         	</td>
              <td>
		<b>Annie Hathaway</b>
		<p>Secretary</p>
	</td>
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
<c>Designed and Developed by Hari Priya (23013964)</c>
    </div>
</body>
</html>

contactus.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact us</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:plum;
            color:purple;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:black;
  }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:black;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:plum;
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
color:white;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:lightpink;
        }
        .table1{
            color:white;
            font-size: large;
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color: lightpink;
        }
        .table2{
            color:purple;
            font-size: large;
            background-color:plum;
            border-radius: 5px;
            border-style:dotted;
            border-color: plum;

        }
        .queries{
            margin-left:600px;
        }
        .bottomdiv{
            background-color:plum;
            color:purple;
            text-align: center;
            position:relative;
display:block;
            margin-top: 138px;

        }
    </style>
</head>
<body background="coverpage.jpeg">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">METASOFT SOLUTIONS</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="services.html" target="_blank">Services  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contactus">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    <td>
                        Rigno Garderns,257A/102,5th-Floor,R.K Road, Sholinganallur,Chennai-600119. 
</td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        near padiflyover, next to sidco bus stop.
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        info@metasoftsolutions.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        9786278993
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h3 class="heading3">QUERIES</h3>
            <br>
            <br>
            <br><br><br>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
			 NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: white; color: purple;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p><b>Designed and Developed by Hari Priya (23013964)</b></p>
        </div>
    </div>
</body>
</html>
```
## OUTPUT:
![Screenshot from 2023-12-31 20-39-16](https://github.com/HARIPRIYASIVAKUMAR/productcompanywebsite/assets/147477684/df2f39a1-5de0-4a64-9372-c5f9ed1eb01a)
![Screenshot from 2023-12-31 20-39-30](https://github.com/HARIPRIYASIVAKUMAR/productcompanywebsite/assets/147477684/37ccc69a-23ee-4ee7-96c9-3b83e0f1ade9)
![Screenshot from 2023-12-31 20-39-38](https://github.com/HARIPRIYASIVAKUMAR/productcompanywebsite/assets/147477684/610f29ed-8e7f-437a-be80-aaf931c4dcbb)
![Screenshot from 2023-12-31 20-39-58](https://github.com/HARIPRIYASIVAKUMAR/productcompanywebsite/assets/147477684/d6b3fe4e-1aca-4866-9816-c21a783c6d5d)



## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
