# Product Company Website
## AIM:
To develop a static company website to display the sale of products.

## Design Steps:

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

### Step 7:
Publish the website in the given URL.

## Code:
```html
home.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:rgb(226, 214, 43);
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    img{
        height: 150px;
        width: 150px;
        align-items:center;
    }
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>VINTAGE</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <marquee><b>FEEL GOOD WHAT YOU SEEK </b></marquee>
                    <p style="color:BLACK; font-family:'ariel'; font-size:30px;"> THIS IS OFFICIAL VINTAGE MOBILE STORE</p>
                    </div>
                    <br>
                <center>
                    <img src="/static/images/ben1.png">
                    <img src="/static/images/ben2.jpg">
                    <img src="/static/images/ben3.png">
                    <img src="/static/images/ben4.jpg">
                    <img src="/static/images/ben5.png">
                    <img src="/static/images/ben6.png">
                    <img src="/static/images/ben7.png">
                </center>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by UDAYAKUMAR</footer></div>
            </div>
        </div>
    </body>
</html>
```
```html
products.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Products
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 1700px;
            width: 85%;
            border: 12px solid red;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
            color:blueviolet;
            font-family:'Lucida Sans';
            font-size: 30px;
            text-align:center;
        
        }
        .content{
            border:3px solid red;
            background-color: white;
            width:98%;
            height:1300px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ph1{
            background-image: url(/static/images/item1.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:250px;
            width:30%;
            position:relative;
            left: 50px;
        }
        .l1{
            color:black;
            position:relative;
            right:380px;
            
            
        }
        .ph2{
            background-image: url(/static/images/item2.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:250px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l2{
            color:black;
            position:relative;
            right:380px;
        }
        .ph3{
            background-image: url(/static/images/item3.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:250px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l3{
            color: black;
            position:relative;
            right:380px;
        }
        .ph4{
            background-image: url(/static/images/item4.jpeg);
            background-position-x: center;
            border:1px solid black;
            height:250px;
            width:30%;
            position:relative;
            left: 700px;
            bottom:930px;
            background-size: 310px;
            background-repeat: no-repeat;
            
            
        }
        .l4{
            color: black;
            position:relative;
            left:270px;
            bottom: 930px;
        }
    
        .ph5{
            background-image: url(/static/images/item5.jpeg);
            background-position-x: center;
            border:1px solid black;
            height:300px;
            width:30%;
            position:relative;
            left: 700px;
            bottom:930px;
            background-size: 280px;
            background-repeat: no-repeat;
            
            
        }
        .l5{
            color: rgb(18, 19, 19);
            position:relative;
            left:270px;
            bottom: 930px;
        }   
        .bot{
            text-align:center;
            font-size:larger;
            color:magenta;

        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>PRODUCTS</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>These are the products that are available now</p>
                    </div>
                    <div class="ph1"></div>
                    <div class="l1"><p align="center"><b>1980's Model Vintage version <br> Price: 6999.00</b><br><br><br><br></p></div>
                    <div class="ph2"></div>
                    <div class="l2"><p align="center"><b>Black Berry<br> Price: 9999.00</b><br><br><br><br></p></div>
                    <div class="ph3"></div>
                    <div class="l3"><p align="center"><b>Landline Model<br> Price: 1999.00</b><br<br><br><br></p></div>
                    <div class="ph4"></div>
                    <div class="l4"><p align="center"><b>Wooden Booth Modl<br> Price: 6999.00</b><br><br><br><br></p></div>
                    <div class="ph5"></div>
                    <div class="l5"><p align="center"><b>Classic Model<br> Price: 3999.00</b><br><br><br><br></p></div>
                </div>
                <div class="bot"><p>To Order Online: Call 90 80 70 2009</p></div>

                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by UDAYAKUMAR</footer></div>
            </div>
        </div>
    </body>
</html>
```
```html
people.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 2600px;
            width: 80%;
            border: 12px solid rgb(0, 102, 255);
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:yellow;
        }
        .text{
        color:blueviolet;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:2px solid rgb(241, 247, 255);
            background-color:black;
            width:98%;
            height:2300px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ceoph{
            background-image: url(/static/images/P1.jpg);
            background-size: 300px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid gold;
            height:300px;
            width:20%;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color:white;
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url(/static/images/P6.jpg);
            background-size: 300px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid yellow;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;            
        }
        .man1{
            color: white;
            position:relative;
            text-align:center;
            
        }
        .amph1{
            background-image: url(/static/images/P4.jpg);
            background-size: 300px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid yellow;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color: rgb(243, 237, 237);
            position:relative;
            text-align:center;
        }

        .amph2{
            background-image: url(/static/images/P2.jpg);
            background-size: 300px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid yellow;
            height:300px;
            width:20%;
            position:relative;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am2{
            color: white;
            position:relative;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: rgb(46, 70, 173); text-decoration: none;"><b>HOME</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: rgb(2, 0, 139); text-decoration: none;"><b>PRODUCTS</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:rgb(0, 2, 139); text-decoration: none;"><b>PEOPLE</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:rgb(2, 0, 139); text-decoration: none;"><b>CONTACT US</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>PEOPLE</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>Board Members</p>
                    <h4><u>CHAIRMAN</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2>Mr. Udaya</h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>HEAD EXECUTIVES</u></b></p><br>
                    </div>
                    <div class="manph1"></div>
                    <div class="man1"><p align="center"><b><h2>Mr. Elvin</h2></b></p></div>
                    <div class="manph2"></div>
                    <br>
                    <div class="text"><p><b><u>MANAGERS</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="center"><b><h2>Mr. Tarun</h2></b></p></div>
                    <div class="amph2"></div>
                    <div class="am2"><p align="center"><b><h2>Mr. Nani</h2></b></p></div>
                    <div class="amph3"></div>
                    <div class="am3"><p align="center"><b><h2>Ashwin</h2></b></p></div><br>
                    <div class="text">Thank you so much for your kind support!<br>Keep buying our products..!!</div>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by Udayakumar</footer></div>
            </div>
        </div>
    </body>
</html>
```
```html
contact.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:rgb(0, 201, 90);
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: darkred; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: darkred; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:darkred; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:darkred; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>CONTACT US</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>HERE ARE THE DETAILS ABOUT US!
                    <h5>D0 CONTACT US FOR ANY QUIRES OR ANY NEED!!</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                        N0.102 Kabilar Nagar,TamilNadu.India.
                    </p>
                    <ul>
                        <li><b>Landline:</b> 12345678</li>
                        <li><b>Mobile</b>: 9783095770</li>
                        <li><b>Facebook</b>: vintage.store_ </li>
                        <li><b>Email Id:</b>vstore@vintage.com</li>
                    </ul>
                    <div style="text-align: center;color:violet;font-size:20px;"><b>24/7 Services Available!</b></div>

                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by UDAYAKUMAR</footer></div>
            </div>
        </div>
    </body>
</html>
```
```html
styles.css

 .home{
            height: 700px;
            width: 85%;
            border: 12px solid red;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .content{
            border:1px solid whitesmoke;
            background-color: white;
            width:95%;
            height:1190px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .header{
            height: 128px;
            width:100%;
            background-size: cover;
        }
        .logo{
            height:18%;
            width: 10%;
            position:absolute;
            background-size:cover;
        }
        .prod{
            height:auto;
            width:auto;
            position:relative;
            bottom:10px;
            left:550px;
            border:4px solid transparent;
            text-align:center;
            display: inline;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .prod:hover{
            background-color:red;
        }
        .people{
            height:auto;
            width:auto;
            position:relative;
            bottom:10px;
            left:700px;
            border:4px solid transparent;
            text-align:center;
            display: inline;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .people:hover{
            background-color:red;
        }
        .contact{
            height:20px;
            width:10%;
            position:relative;
            bottom:45px;
            left:1000px;
            border:4px solid transparent;
            text-align:center;
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .contact:hover{
            background-color:rgb(51, 255, 0);
        }
                
        .h{
            height:20px;
            width:10%;
            position:relative;
            top:30px;
            left:200px;
            border:4px solid transparent;
            text-align:center;
            
            padding:15px;
            font-family:'Gill Sans MT';
            font-size: large;  
        }
        .h:hover{
            background-color:red;
            overflow:hidden;
        }
        .footer{
            border: 15px solid red;
            width:98%;
            height:10px;
            position:relative;
            bottom: 1px;
            background-color:red;
            text-align:center;

        }
        .title{
            border:2px solid pink;
            background-color:white;
            padding:1px;
            width:99.7%;
            height: 70px;
            text-align:center;
            font-family:'Impact';
            margin-left:auto;
            margin-right: auto;
            
        }
        .content{
            border:1px solid red;
            background-color: white;
            width:98%;
            height:400px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;

        }
```
## Output:
![image](https://user-images.githubusercontent.com/118708024/215314669-b44cb4c9-e066-4d37-85eb-43ed66eb7d2c.png)
![image](https://user-images.githubusercontent.com/118708024/215314689-ad39207b-d93f-4f70-95d8-f539297b88f5.png)
![image](https://user-images.githubusercontent.com/118708024/215314721-b35b074a-92d8-4e41-8a6e-b86f992fd7a2.png)
![image](https://user-images.githubusercontent.com/118708024/215314750-c4cc3ef6-2524-4f7b-9e49-eb9b28066220.png)

## HTML Validator
![image](https://user-images.githubusercontent.com/118708024/215314782-0f3ae86b-9b86-48f5-acf9-8e4971d9f377.png)
## Result:
The program for designing company website for sale of products using HTML and CSS is completed successfully.
