# Ex.07 Restaurant Website
# Date:9.12.2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
restaurant.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Farhaan Restaurant</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #eef2f7;
            color: #333;
        }

        header {
            background: #1f3c88;
            color: white;
            text-align: center;
            padding: 15px;
        }

        nav {
            background: #162447;
            text-align: center;
            padding: 10px;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 14px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
        }

        .hero img {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }

        .content {
            background: white;
            padding: 20px;
            margin-top: 20px;
        }

        footer {
            background: #162447;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

<header>
    <h1>FARHAAN RESTAURANT</h1>
    <p>Authentic Taste • Pure Tradition</p>
</header>

<nav>
    <a href="restaurant.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="chef.html">Chefs</a>
    <a href="contact.html">Contact</a>
</nav>

<div class="container">
    <div class="hero">
        <img src="restaurant.jpg" alt="Restaurant">
    </div>

    <div class="content">
        <h2>Welcome to Farhaan Restaurant</h2>
        <p>
            Farhaan Restaurant brings you the rich flavors of Indian cuisine made with
            fresh ingredients and traditional recipes. Our chefs prepare every dish
            with passion and care.
            <br><br>
            From spicy curries to flavorful biryanis, we offer a dining experience
            that reflects India’s diverse food culture.
        </p>
    </div>
</div>

<footer>
    <p>&copy; 2025 Farhaan Restaurant</p>
</footer>

</body>
</html>
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Farhaan Restaurant - Menu</title>

<style>
body {
    font-family: Arial, sans-serif;
    background: #eef2f7;
    margin: 0;
}

header {
    background: #1f3c88;
    color: white;
    text-align: center;
    padding: 15px;
}

nav {
    background: #162447;
    text-align: center;
    padding: 10px;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
}

.container {
    max-width: 1100px;
    margin: 20px auto;
}

.menu-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
}

.item {
    background: white;
    text-align: center;
    padding: 10px;
}

.item img {
    width: 150px;
    height: 150px;
    object-fit: cover;
}
</style>
</head>

<body>

<header>
<h1>FARHAAN RESTAURANT</h1>
<p>Indian Special Menu</p>
</header>

<nav>
<a href="restaurant.html">Home</a>
<a href="menu.html">Menu</a>
<a href="chef.html">Chefs</a>
<a href="contact.html">Contact</a>
</nav>

<div class="container">
<div class="menu-grid">

<div class="item"><img src="Chicken Biryani.jpg"><h3>Chicken Biryani</h3></div>
<div class="item"><img src="Butter Chicken.jpg"><h3>Butter Chicken</h3></div>
<div class="item"><img src="Paneer Tikka.jpg"><h3>Paneer Tikka</h3></div>
<div class="item"><img src="Masala Dosa.jpg"><h3>Masala Dosa</h3></div>

<div class="item"><img src="Butter Naan.jpg"><h3>Butter Naan</h3></div>
<div class="item"><img src="Chole Bhature.jpg"><h3>Chole Bhature</h3></div>
<div class="item"><img src="Idli & Sambar.jpg"><h3>Idli & Sambar</h3></div>
<div class="item"><img src="Tandoori Chicken.jpg"><h3>Tandoori Chicken</h3></div>

<div class="item"><img src="Gulab Jamun.jpg"><h3>Gulab Jamun</h3></div>
<div class="item"><img src="Rasmalai.jpg"><h3>Rasmalai</h3></div>
<div class="item"><img src="Filter Coffee.jpg"><h3>Filter Coffee</h3></div>
<div class="item"><img src="Sweet Lassi.jpg"><h3>Sweet Lassi</h3></div>

</div>
</div>

<footer style="background:#162447;color:white;text-align:center;padding:10px;">
&copy; 2025 Farhaan Restaurant
</footer>

</body>
</html>
```
chef.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Farhaan Restaurant - Our Chefs</title>

<style>
body {
    font-family: Arial;
    background: #eef2f7;
    margin: 0;
}

header {
    background: #1f3c88;
    color: white;
    text-align: center;
    padding: 15px;
}

nav {
    background: #162447;
    text-align: center;
    padding: 10px;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
}

.container {
    max-width: 1000px;
    margin: 20px auto;
}

.grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
}

.card {
    background: white;
    text-align: center;
    padding: 15px;
    display: flex;
    flex-direction: column;
    align-items: center;
}


.card img {
    width: 100%;
    max-width: 220px;
    height: 300px;
    object-fit: cover;
    border-radius: 8px;
}

</style>
</head>

<body>

<header>
<h1>OUR CHEFS</h1>
<p>The heart of our kitchen</p>
</header>

<nav>
<a href="restaurant.html">Home</a>
<a href="menu.html">Menu</a>
<a href="chef.html">Chefs</a>
<a href="contact.html">Contact</a>
</nav>

<div class="container">
<div class="grid">

<div class="card"><img src="Screenshot 2025-12-24 161314.png"><h3>Chef Arjun</h3><p>Head Chef</p></div>
<div class="card"><img src="Screenshot 2025-12-24 161321.png"><h3>Chef Rahman</h3><p>Biryani Specialist</p></div>
<div class="card"><img src="Screenshot 2025-12-24 161347.png"><h3>Chef Meena</h3><p>South Indian Expert</p></div>
<div class="card"><img src="Screenshot 2025-12-24 161326.png"><h3>Chef Rakesh</h3><p>Tandoor Chef</p></div>
<div class="card"><img src="Screenshot 2025-12-24 161347.png"><h3>Chef Ayesha</h3><p>Dessert Specialist</p></div>
<div class="card"><img src="Screenshot 2025-12-24 161347.png"><h3>Chef Sherina</h3><p>North Indian Cuisine</p></div>

</div>
</div>

<footer style="background:#162447;color:white;text-align:center;padding:10px;">
&copy; 2025 Farhaan Restaurant
</footer>

</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Farhaan Restaurant - Contact</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #eef2f7;
            color: #333;
        }

        header {
            background-color: #1f3c88;
            color: white;
            text-align: center;
            padding: 15px;
        }

        header h1 {
            margin: 5px 0;
            font-size: 22px;
        }

        header p {
            margin: 0;
            font-size: 14px;
        }

        nav {
            background-color: #162447;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 14px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 800px;
            margin: 25px auto;
            background: white;
            padding: 20px;
            border-radius: 5px;
        }

        .container h2 {
            text-align: center;
            font-size: 20px;
            margin-bottom: 15px;
        }

        .contact-info {
            font-size: 14px;
            line-height: 1.6;
        }

        .contact-info p {
            margin: 12px 0;
        }

        footer {
            background-color: #162447;
            color: white;
            text-align: center;
            padding: 10px;
            font-size: 13px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

<header>
    <h1>FARHAAN RESTAURANT</h1>
    <p>Reach out to us for reservations and enquiries</p>
</header>

<nav>
    <a href="restaurant.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="chef.html">Chefs</a>
    <a href="contact.html">Contact</a>
</nav>

<div class="container">
    <h2>Contact Information</h2>

    <div class="contact-info">
        <p><strong>Address:</strong><br>
            21, MG Road,<br>
            Indiranagar, Bengaluru – 560038,<br>
            Karnataka, India
        </p>

        <p><strong>Email:</strong><br>
            contact@farhaanrestaurant.com
        </p>

        <p><strong>Phone:</strong><br>
            +91 91234 56789
        </p>

        <p><strong>Business Hours:</strong><br>
            Monday to Sunday – 11:00 AM to 10:30 PM
        </p>
    </div>
</div>

<footer>
    <p>&copy; 2025 Farhaan Restaurant</p>
</footer>

</body>
</html>
```
# OUTPUT:
<img width="1920" height="1016" alt="screencapture-file-D-RESTARAUNT-WEB-restaurant-html-2025-12-24-16_22_13" src="https://github.com/user-attachments/assets/44aa4ffd-f1de-44f1-bbc0-e0b3864f1957" />
<img width="1920" height="1236" alt="screencapture-file-D-RESTARAUNT-WEB-menu-html-2025-12-24-16_22_33" src="https://github.com/user-attachments/assets/3425e417-3d4c-4f78-abd1-a6d3e75367da" />
<img width="1920" height="1081" alt="screencapture-127-0-0-1-5500-chef-html-2025-12-26-10_16_06" src="https://github.com/user-attachments/assets/e828c99f-e345-4e65-a0ff-97c47489640f" />
<img width="1920" height="912" alt="screencapture-file-D-RESTARAUNT-WEB-contact-html-2025-12-24-16_23_02" src="https://github.com/user-attachments/assets/dd0d1b81-fe38-4dfb-b19b-b0182d9cc4a1" />




# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
