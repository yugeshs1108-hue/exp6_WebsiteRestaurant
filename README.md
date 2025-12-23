# Ex.06 Restaurant Website
## Date:17.12.2025

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
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Tasty Bites Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Tasty Bites</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- Hero Section -->
<section id="home" class="hero">
    <h2>Delicious Food, Happy Mood</h2>
    <p>Fresh • Tasty • Hygienic</p>
    <button>Order Now</button>
</section>

<!-- Menu Section -->
<section id="menu" class="menu">
    <h2>Our Menu</h2>

    <div class="menu-items">
        <div class="item">
            <img src="Biriyani.jpg" alt="Biryani">
            <h3>Biryani</h3>
            <p>₹180</p>
        </div>

        <div class="item">
            <img src="pizza.jpg" alt="Pizza">
            <h3>Pizza</h3>
            <p>₹250</p>
        </div>

        <div class="item">
            <img src="burger.jpg" alt="Burger">
            <h3>Burger</h3>
            <p>₹120</p>
        </div>

        <div class="item">
            <img src="rice.jpg" alt="Fried Rice">
            <h3>Fried Rice</h3>
            <p>₹150</p>
        </div>
    </div>
</section>

<!-- About -->
<section id="about" class="about">
    <h2>About Us</h2>
    <p>
        Tasty Bites Restaurant serves delicious food made with love.
        Quality and taste are our priority.
    </p>
</section>

<!-- Contact -->
<section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>📍 Chennai, India</p>
    <p>📞 +91 98765 43210</p>
    <p>📧 tastybites@gmail.com</p>
</section>

<footer>
    <p>© 2025 Tasty Bites Restaurant</p>
</footer>

</body>
</html>


CSS
body {
    margin: 0;
    font-family: Arial, sans-serif;
}

/* Header */
header {
    background-color: #8b0000;
    color: white;
    padding: 15px;
    text-align: center;
}

header nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
}

/* Hero Section */
.hero {
    background: url("images/hero.jpg") no-repeat center/cover;
    height: 400px;
    color: white;
    text-align: center;
    padding-top: 120px;
}

.hero button {
    background-color: #8b0000;
    color: white;
    border: none;
    padding: 12px 25px;
    cursor: pointer;
    font-size: 16px;
}

/* Menu */
.menu {
    padding: 40px;
    text-align: center;
}

.menu-items {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.item {
    width: 200px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    padding: 10px;
    background-color: white;
}

.item img {
    width: 100%;
    height: 140px;
    object-fit: cover;
}

/* About */
.about {
    background-color: #f5f5f5;
    padding: 40px;
    text-align: center;
}

/* Contact */
.contact {
    padding: 40px;
    text-align: center;
}

/* Footer */
footer {
    background-color: #8b0000;
    color: white;
    text-align: center;
    padding: 10px;
}

```

## OUTPUT:
![alt text](<Screenshot 2025-12-23 202401.png>) ![alt text](<Screenshot 2025-12-23 202435.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
