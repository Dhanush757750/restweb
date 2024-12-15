# Ex.07 Restaurant Website
## Date:15-12-2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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
```
Home.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><b>Welcome to DHANUSH MEES</b></title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('resturant.png');
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: rgba(148, 145, 143, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #2a9d8f;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: rgb(34, 16, 16);
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #0caded;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(223, 21, 21, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 200px;
            height: auto;
            border-radius: 13px;
        }
    </style>
</head>
<body>


    <!-- Header Section -->
    <div class="banner">
        <h1><b>Welcome to DHANUSH MEES</b></h1>
        <p>Experience the taste of excellence!</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="Home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Main Content Section -->
    <div class="welcome-section">
        <h2>ABOUT DHANUSH MESS </h2>
        <p>At DHANUSH MESS, Everything that we bring you is pure,</p>
        <P>delicious and authentic.</P>
        <P> At  DHANUSH MESS, we prepare only using the finest ingredients, following time-tested methods.</P>
        <P> Experience a perfect blend of timeless tradition and innovation in every bite.</p>
   

    <!-- Food Images Section -->
    <div class="food-images">
        <img src="D1.png" alt="Delicious Food 1">
        <img src="D2.png" alt="Delicious Food 2">
    </div>
    <br>
    <br>
    <br>
    <br>
    <br>

    <!-- Footer Section -->
    <footer>
        <p><b>&copy; DESIGNED BY: DHANUSH C(24009885)</b></p>
    </footer>
</body>
</html>

Menu.html
<!DOCTYPE html>
<html>
<head>
    <html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><b>Welcome to DHANUSH MEES</b></title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('resturant.png');
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: rgba(148, 145, 143, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #2a9d8f;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: rgb(34, 16, 16);
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #0caded;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(223, 21, 21, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 190px;
            height: auto;
            border-radius: 10px;
        }
    </style>
</head>
<body>




    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="Home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Our Specialties</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        h2 {
            background-color: #2a9d8f;
            color: white;
            padding: 20px;
        }
        table {
            width: 100%;
            max-width: 800px;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
        }
        img {
            width: 100px;
            height: auto;
            border-radius: 8px;
        }
        caption {
            font-size: 1.5em;
            margin: 10px 0;
        }
    </style>
</head>

<section id="menu">
    <h2>Menu</h2>
    <div class="menu-grid">
        
        <div class="menu-item">
            <h3><font color="red">CHICKEN GRAVY</font></h3>
            <img src="chk.png">
            <p><strong>RS.110</strong></p>
        
    </div>
        <div class="menu-item">
            <h3><font color="blue">MUTTON GRAVY</font></h3>
            <img src="mtn.png">
            <p><strong>RS.130</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="yellow">FISH FRY</font></h3>
            <img src="fh.png">
            <p><strong>RS.100</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="aqua">BRIYANI</font></h3>
            <img src="ckb.png">
            <p><strong>RS.180</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="blue">GULAB JAMUN</font></h3>
            <img src="gb.png">
            <p><strong>RS.90</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="green">ICE CREAM</font></h3>
            <img src="icm.png">
            <p><strong>RS.85</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="purple">CURD RICE</font></h3>
            <img src="crd.png">
            <p><strong>RS.95</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="gray">PIZZA</font></h3>
            <img src="pza.png">
            <p><strong>RS.130</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="brown">CHOCOLATE MILK SHAKE</font></h3>
            <img src="mlk.png">
            <p><strong>RS.110</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="violet">FRENCH FRIES</font></h3>
            <img src="fncf.png">
            <p><strong>RS.75</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="green">BURGER</font></h3>
            <img src="bgr.png">
            <p><strong>RS.150</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="golden">CUPPUCCINO</font></h3>
            <img src="cfe.png">
            <p><strong>RS.90</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="red">CHAPATHI ROLE</font></h3>
            <img src="cpr.png">
            <p><strong>RS.130</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="black">EGG NOODLES</font></h3>
            <img src="egl.png">
            <p><strong>RS.175</strong></p>
        </div>
        <div class="menu-item">
            <h3><font color="green">EGG PUFFS</font></h3>
            <img src="epf.png">
            <p><strong>RS.70</strong></p>
        </div>
    </div>
</section>


</body>
</html>


administration.html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Nourish Bistro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('resturant.png');
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: #2a9d8f;
            padding: 20px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #264653;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
        }
        .nav-links a {
            display: inline-block;
            padding: 10px 15px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #2a9d8f;
        }
        .admin-section {
            padding: 20px;
        }
        .admin-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .admin-card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .admin-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        .admin-card h3 {
            font-size: 18px;
            margin: 10px 0;
        }
        .admin-card p {
            font-size: 14px;
            color: #555;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Meet Our Administration</h1>
        <p>The team Dhanush Resturant success</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="Home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Administration Section -->
    <div class="admin-section">
        <h2>Our Dedicated Team</h2>
        <div class="admin-grid">
            <div class="admin-card">
                <img src="P.PNG" alt="Admin 1">
                <h3>DHANUSH C</h3>
                <p>C.E.O</p>
                <p>EMAIL:dhanush757@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="vt.png" alt="Admin 2">
                <h3>VENKATESH</h3>
                <p>Head Chef</p>
                <p>EMAIL:venkatesh@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="D.png" alt="Admin 3">
                <h3>DHANUSH</h3>
                <p>CHEIF GUEST</p>
                <p>EMAIL:dhanush@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="sr.png" alt="Admin 4">
                <h3>SAI RAM</h3>
                <p>MARKETING MANAGER</p>
                <p>sairam@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="CH.png" alt="Admin 5">
                <h3>CHARAN REDDY</h3>
                <p>FINANCE MANAGER</p>
                <p>EMAIL:charan@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="cht.png" alt="Admin 5">
                <h3>RAHUL ROYAL</h3>
                <p>RESTURANT FOUNDER</p>
                <p>EMAIL:rahul@gmail.com</p>
            </div>
        </div>
    </div>
</body>
</html>

contact.html
<!DOCTYPE html>
<html>
<head>
    <html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title><b>Welcome to DHANUSH MEES</b></title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
           
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: rgba(148, 145, 143, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #2a9d8f;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: rgb(34, 16, 16);
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #0caded;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(223, 21, 21, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 190px;
            height: auto;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="Home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Our Specialties</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('resturant.png');
            background-size: cover;
            background-attachment: fixed;
        }
        h2 
        table {
            width: 100%;
            max-width: 800px;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
        }
        img {
            width: 100px;
            height: auto;
            border-radius: 8px;
        }
        caption {
            font-size: 1.5em;
            margin: 10px 0;
        }
    </style>
</head>
<div class="contact-section">  
     
    <div class="contact-details">
        <h2><font Address</h2>
            <font color="red">ADDRESS:</font>
        <p>517001 Estate Main Road</p>
        <p>CHITTOOR</p>
 
        <h2>
            <font color="red">Contact Us:</font>
        </h2>
        <p>9908061390</p>
        <h2>Email</h2>
        <p><a href="mailto:dhanushmess">dhanushmess@gmail.com</a></p>
        <h3>Developed and designed by C.Dhanush</h3>
    </div>

```

## OUTPUT:
![alt text](<Screenshot 2024-12-15 232339.png>)
![alt text](<Screenshot 2024-12-15 232356.png>)
![alt text](<Screenshot 2024-12-15 232416.png>)
![alt text](<Screenshot 2024-12-15 232430.png>)
![alt text](<Screenshot 2024-12-15 232458.png>)
![alt text](<Screenshot 2024-12-15 232509.png>)
![alt text](<Screenshot 2024-12-15 232517.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
