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
ADMIN.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Admin Dashboard</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>Admin Dashboard</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Logout</a>
  </nav>
</header>

<section class="dashboard">
  <h2>Available Dishes</h2>
  <ul>
    <li>Grilled Chicken</li>
    <li>Pasta Alfredo</li>
    <li>Paneer Butter Masala</li>
    <li>Veggie Pizza</li>
    <li>Chicken Biryani</li>
  </ul>

  <h2>Add New Dish</h2>
  <form>
    <input type="text" placeholder="Dish Name">
    <input type="text" placeholder="Price">
    <button type="submit">Add Dish</button>
  </form>

  <h2>Employees on Shift</h2>
  <ul>
    <li>PRANAV- chief Chef</li> <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 222811.png">
    <li>SARA - Waitress</li> <IMG SRC="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 221640.png">
    <li>SUZAN - Manager</li> <IMG SRC="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 222914.png">
    <li>JOHN - Chief Executive Chef</li> <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 221626.png">
    <li>MANASA - Executive Chef</li> <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 223022.png">
    <li>PREETHI - Chief Chef</li> <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 222746.png">
  </ul>
</section>

<footer>
  <p>© 2025 FARHAAN  Restaurant</p>
</footer>
</body>
</html>
```
CONTACT.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Restaurant - Contact</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1> FARHAAN Restaurant</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Administration</a>
  </nav>
</header>

<section class="contact">
  <h2>Contact Us</h2>
  <p>📍 5/453 -1,Noel street, VELLORE</p>
  <p>📞 +91 6369537112</p>
  <p>📧 EMAIL : sbrest1902@gmail.com</p>
  <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 223819.png">
</section>

<footer>
  <p>© 2025 FARHAAN Restaurant</p>
</footer>
</body>
</html>
```
INDEX.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-5">
  <title>Restaurant - Menu</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>FARHAAN Restaurant</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Administration</a>
  </nav>
</header>

<section class="menu">
  <h2>Our Menu</h2>
  <ul>
    <li>Grilled Chicken - 320</li> <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 222746.png"> <p>Grilled chicken is chicken cooked over direct heat on a grill, resulting in a seared, charred exterior and a moist interior. It is often seasoned with herbs, spices, or marinades before cooking, creating a flavorful dish that can be served as a main course, side dish, or appetizer. Grilled chicken is a versatile and popular dish known for being a good source of lean protein.  </p>
    <li>Pasta Alfredo - 450</li> <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 222811.png"> <p>The Alfredo Pasta is an Italian pasta dish made using fresh pasta, vegetables, chicken pieces combined with butter, cream and cheese. As the cheese melts, it results in a creamy, rich cheese sauce that coats the pasta. It is without a doubt one of the most delicious and simple dishes to prepare at home.</p>
    <li>Paneer Butter Masala - 250</li> <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 222850.png"> <p>Paneer butter masala is a rich and creamy North Indian curry featuring tender cubes of paneer (Indian cottage cheese) simmered in a silky tomato and cashew-based sauce. It is known for its luxurious texture and harmonious blend of flavors, making it a favorite dish in Indian restaurants and homes worldwide</p>
    <li>Veggie Pizza - 320</li> <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 222914.png"> <p>Pizza is a popular Italian dish consisting of a flattened bread dough base topped with tomato sauce and cheese, often with additional ingredients like vegetables and meats, then baked at a high temperature. The concept is a flat, open-faced baked pie that is customizable with a wide variety of toppings and sauces, resulting in diverse flavors and textures.  </p>
    <li>Chicken Biryani - 280</li> <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 222936.png"> <p>Chicken Biryani is a flavorful one-pot dish originating from the Indian subcontinent, made by layering marinated chicken with aromatic basmati rice, spices, and sometimes vegetables like potatoes, then slow-cooking it using the dum pukht ("steam-cooked") method in a sealed pot. The chicken is marinated in yogurt, ginger-garlic paste, and a complex blend of whole and ground spices, infusing it with rich flavors and ensuring tenderness.</p>
    <li>Caesar Salad - 320</li> <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 222954.png"> <p>A Caesar salad (also spelled Cesar, César and Cesare), also known as Caesar's salad, is a green salad of romaine lettuce and croutons dressed with lemon juice (or lime juice), olive oil, eggs, Worcestershire sauce, anchovies, garlic, Dijon mustard, Parmesan and black pepper.</p>
    <li>Seafood Platter - 800</li> <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 223022.png"> <p>The classic seafood platter is a true crowd-pleaser. It typically includes an array of freshly shucked oysters, succulent steamed or chilled shrimp, tender crab legs, and a selection of dipping sauces such as tartar sauce, cocktail sauce, and mignonette</p>
    
  </ul>
</section>

<footer>
  <p>© 2025 SB Restaurant</p>
</footer>
</body>
</html>
```
MENU.HTML 
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Restaurant - Home</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>FARHAAN RESTAURANT</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact</a>
      <a href="admin.html">Administration</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to FARHAAN Restaurant</h2>
    <p>Enjoy the finest dishes made with love "Your table is calling"</p>
  </section>

  <section class="dishes">
    <h2>Our Special Dishes</h2>
    <div class="dish-grid">
      <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 221459.png" alt="Dish 1">
      <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 221544.png" alt="Dish 2">
      <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 221608.png" alt="Dish 3">
      <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 221626.png" alt="Dish 4">
      <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 221640.png" alt="Dish 5">
      <img src="c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot 2025-12-18 221820.png" alt="Dish 6">
    </div>
  </section>

  <footer>
    <p>© 2025 FARHAAN Restaurant</p>
  </footer>
</body>
</html>
```
# OUTPUT:
![WhatsApp Image 2025-12-19 at 20 13 55_bd722d4b](https://github.com/user-attachments/assets/8cd57310-9ec1-44ed-8ffb-a0fb684627e3)
![WhatsApp Image 2025-12-19 at 20 13 55_14bcd75d](https://github.com/user-attachments/assets/c17456e8-69ad-4e54-869a-b30d25a580d0)
![WhatsApp Image 2025-12-19 at 20 13 56_9a5e2fdf](https://github.com/user-attachments/assets/7f4c07a6-b976-4c97-908c-b18fe2814ca7)
![WhatsApp Image 2025-12-19 at 20 14 03_cbc4646d](https://github.com/user-attachments/assets/09c4eb66-717d-4302-904c-7c17f3d7e957)
![WhatsApp Image 2025-12-19 at 20 13 58_11e58d4b](https://github.com/user-attachments/assets/154e1da7-a599-48ff-8435-1918b13ce495)
![WhatsApp Image 2025-12-19 at 20 13 58_028e1fc0](https://github.com/user-attachments/assets/1631598b-4e65-4124-9def-630d6c92049a)





# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
