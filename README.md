# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

### Step 7:
Publish the website in the given URL.

## PROGRAM:

## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XI TECH</title>
    <style>
        *{
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }
        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color:wheat;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;

        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        }

        .cname{
            padding-top: 20px;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color:cadetblue;
            height: 500px;        
            overflow: hidden;
            line-height: 30px;
        }

        h1,h2{
            text-align: center;
        }

        .image1 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
        }

        .image3 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 600px;
        }

        .image2  img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 1170px;
        }

        footer{
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <div class="logo">
            <a><img src="xitech.jpg" alt="logo" border="2"></a>
        </div>
        <a class ="cname"><h1>XI TECH</h1></a>
        <div class="header-right">
            <a class="active" href="index.html">Home</a>
            <a href="product.html">Product</a>
            <a href="people.html">People</a>
            <a href="contact.html">Contact</a>
          </div>
    </header>

    <section id="content">
        <h1>WELCOME GUYS</h1>
        <h2>" Code is like a humor. When u have to explain it,its bad "</h2>
        <div class="image1">
            <img src="index1.jpg" alt="image1">
        </div>
        <div class="image2">
            <img src="index2.jpg" alt="image2">
        </div>
        <div class="image3">
            <img src="index3.jpg" alt="image3">
        </div>
    </section>

    <footer>
        <p>&copy; 2023 O<sup>+</sup> Solutions. All rights reserved.</p>
    </footer>
</body>
</html>
```

## product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XI TECH</title>
    <style>
        *{
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color:wheat;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        }

        .cname{
            padding-top: 20px;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: cadetblue;
            height: 1500px;        
            overflow: hidden;
            line-height: 30px;
        }
        
        .prod1 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 280px;
        }

        .prod2 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 1170px;
        }

        .prod3 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 280px;
            left: 600px;
        }

        .prod4 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 740px;
        }

        .prod5 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 740px;
            left: 650px;
        }

        .prod6 img{
            padding: 50px;
            height: 300px;
            width: 500px;
            position:absolute;
            top: 740px;
            left: 1100px;
        }

        .prod7 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 1140px;
        }

        .prod8 img{
            padding: 50px;
            height: 300px;
            width: 400px;
            position:absolute;
            top: 1140px;
            left: 1170px;
        }

        .prod9 img{
            padding: 50px;
            height: 300px;
            width: 300px;
            position:absolute;
            top: 1140px;
            left: 650px;
        }

        .quote{
            text-align: center;
            font-size: 20px;
            color: khaki  ;
        }

        footer{
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="xitech.jpg" alt="logo" border="2"></a>
        <a class ="cname"><h1>XI TECH</h1></a>
        <div class="header-right">
            <a href="index.html">Home</a>
            <a class="active" href="product.html">Product</a>
            <a href="people.html">People</a>
            <a href="contact.html">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="quote">
            <h3>"Software is a gas; it expands to fill its container." - Nathan Myhrvold</h3>
        </div>
        <div class="prod1">
            <img src="norton.png" alt="prod3">
        </div>
        <div class="prod2">
            <img src="canva.png" alt="prod2">
        </div>
        <div class="prod3">
            <img src="opera.png" alt="prod1">
        </div>
        <div class="prod4">
            <img src="wix.png" alt="prod4">
        </div>
        <div class="prod5">
            <img src="word.png" alt="prod5">
        </div>
        <div class="prod6">
            <img src="vscode.jpg" alt="prod6">
        </div>
        <div class="prod7">
            <img src="adobe.jpg" alt="prod7">
        </div>
        <div class="prod8">
            <img src="sql.jpg" alt="prod8">
        </div>
        <div class="prod9">
            <img src="music.jpg" alt="prod9">
        </div>
    </section>

    <footer>
        <p>&copy; 2023 O<sup>+</sup> Solutions. All rights reserved.</p>
    </footer>
</body>
</html>
```

### people.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XI TECH</title>
    <style>
        *{
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: wheat;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        }

        .cname{
            padding-top: 20px;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: cadetblue;
            overflow: hidden;
            line-height:normal;
        }
        .person {
            text-align: center;
        }

        p{
            font-size: 20px;
        }
        .person img {
            display:grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            margin: 0 auto;
            height: 340px;
            padding-top: 40px;
        }

        .person p.name {
            font-weight: bold;
            margin-top: 10px;
            color:black;
        }

        .person p.desig {
            font-weight: bold;
            margin-top: 10px;
            color:crimson;
        }

        .title{
            text-align: center;
            font-size: 30px;
            color:maroon  ;
        }
        
        footer{
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="xitech.jpg" alt="logo" border="2"></a>
        <a class ="cname"><h1>XI TECH</h1></a>
        <div class="header-right">
            <a href="index.html">Home</a>
            <a href="product.html">Product</a>
            <a class="active" href="people.html">People</a>
            <a href="contact.html">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="title">
            <h3>OUR REPRESENTATIVES</h3>
        </div>
        <div class="image">
            <div class="person">
                <img src="arish.jfif" alt="Arish">
                <p class="name">ARISH P</p>
                <p class="desig">MANAGING DIRECTOR</p>
            </div>
            <div class="person">
                <img src="john.jfif" alt="John">
                <p class="name">JOHN K</p>
                <p class="desig">CEO</p>
            </div>
            <div class="person">
                <img src="kiran.jpg" alt="Kiran">
                <p class="name">KIRAN M</p>
                <p class="desig">GENERAL MANAGER</p>
            </div>
            <div class="person">
                <img src="maya.jfif" alt="Maya">
                <p class="name">MAYA K</p>
                <p class="desig">MARKETING HEAD</p>
            </div>
            <div class="person">
                <img src="sanjay.png" alt="Sanjay">
                <p class="name">SANJAY S</p>
                <p class="desig">HR MANAGER</p>
            </div>
            <div class="person">
                <img src="zara.jpg" alt="Zara">
                <p class="name">ZARA J</p>
                <p class="desig">REGIONAL MANAGER</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 O<sup>+</sup> Solutions. All rights reserved.</p>
    </footer>
</body>
</html>
```

## contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XI TECH</title>
    <style>
        *{
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: wheat;
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: dodgerblue;
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        }

        .cname{
            padding-top: 20px;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: cadetblue;
            overflow: hidden;
            line-height:normal;
        }
        
        .contact-container {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 50px;
        }

        .contact-image {
            flex: 1;
            text-align: center;
        }

        .contact-image img {
            max-width: 100%;
            height: auto;
        }

        .contact-details {
            flex: 1;
            padding: 50px;
            font-size: 25px;
        }

        .title{
            text-align: center;
            font-size: 30px;
            color:maroon;
        }

        footer{
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="xitech.jpg" alt="logo" border="2"></a>
        <a class ="cname"><h1>XI TECH</h1></a>
        <div class="header-right">
            <a href="index.html">Home</a>
            <a href="product.html">Product</a>
            <a href="people.html">People</a>
            <a class="active" href="contact.html">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="title">
            <h3>CONTACT US</h3>
        </div>
        <div class="contact-container">
            <div class="contact-image">
                <img src="company.jpg">
            </div>
            <div class="contact-details">
                <p><strong>Email:</strong> xitech123@gmail.com</p>
                <p><strong>Phone:</strong> +144 2564 2587</p>
                <p><strong>Address:</strong> 1/88, Tech Street, Ambattur I.E, Chennai</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 O<sup>+</sup> Solutions. All rights reserved.</p>
        </footer>
</body>
</html>
```

## OUTPUT:
![image-5](https://github.com/Kishoreyyy/softweb/assets/119157062/204a85c4-1bd0-4d3b-af5f-8543650c91f2)
![image-6](https://github.com/Kishoreyyy/softweb/assets/119157062/d30560f8-6bb5-4e86-ade1-758c941e733e)
![image-8](https://github.com/Kishoreyyy/softweb/assets/119157062/5683afff-6a7c-4c67-a038-f851bda68759)
![image-9](https://github.com/Kishoreyyy/softweb/assets/119157062/5e4f67c4-be3f-4f67-bec7-2ffadda548af)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
