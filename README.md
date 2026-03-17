# Ex.06 Restuarant Website
## Date:23/02/2026

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
about.html 
```
{% load static %}

<!DOCTYPE html>
<html>

<head>
<title>About Us</title>

<link rel="stylesheet" href="{% static 'style.css' %}">

</head>

<body>

<header>
<h1>About Our Restaurant</h1>
</header>

<section class="about">

<img src="{% static 'restaurant-013.avif' %}" alt="Restaurant Image">

<div>

<h2>Our Story</h2>

<p>
Spice Garden Restaurant was started in 2020 with the goal of
serving delicious and healthy food. Our chefs use fresh ingredients
to create authentic dishes loved by our customers.
</p>

<p>
We believe food should bring people together and create
memorable experiences.
</p>

<p>
Our restaurant is known for its warm atmosphere and welcoming service.
Every dish is carefully prepared using traditional cooking techniques
combined with modern flavors to give our guests a unique dining experience.
</p>

<p>
At Spice Garden, we are passionate about quality and freshness.
From aromatic spices to farm-fresh vegetables, every ingredient is
selected with care to ensure the best taste in every bite.
</p>

<p>
Whether you are visiting with family, friends, or colleagues,
our goal is to make every meal special. We are committed to
providing exceptional food, great hospitality, and unforgettable moments.
</p>

</div>

</section>

</body>

</html>
```
menu.html
```
{% load static %}

<!DOCTYPE html>
<html>

<head>
<title>Menu</title>

<link rel="stylesheet" href="{% static 'style.css' %}">

</head>

<body>

<header>
<h1>Our Menu</h1>
</header>

<section class="menu">

<div class="menu-item">
<h3>Chicken Biryani</h3>
<p>Traditional spicy biryani</p>
<span>$12</span>
</div>

<div class="menu-item">
<h3>Veg Fried Rice</h3>
<p>Fresh vegetables and rice</p>
<span>$9</span>
</div>

<div class="menu-item">
<h3>Grilled Chicken</h3>
<p>Served with salad</p>
<span>$14</span>
</div>

<div class="menu-item">
<h3>Pasta Alfredo</h3>
<p>Creamy Italian pasta</p>
<span>$11</span>
</div>

</section>

</body>
</html>
```
index.html
```
{% load static %}

<!DOCTYPE html>
<html>

<head>
<title>Spice Garden Restaurant</title>

<link rel="stylesheet" href="{% static 'style.css' %}">

</head>

<body>

<header>
<h1>Spice Garden</h1>

<nav>
<a href="/">Home</a>
<a href="/menu/">Menu</a>
<a href="/about/">About</a>
<a href="/contact/">Contact</a>
</nav>

</header>


<section class="hero">
<h2>Welcome to Spice Garden</h2>
<p>Fresh • Tasty • Homemade Food</p>

<a href="/menu/">
<button>Explore Menu</button>
</a>

</section>


<section class="special">

<h2>Today's Specials</h2>

<div class="card-container">


<div class="card">
<img src="{% static 'chicken-biryani.webp' %}">
<h3>Chicken Biryani</h3>
<p>$12</p>
</div>


<div class="card">
<img src="{% static 'Vegetable-Burger.webp' %}">
<h3>Veg Burger</h3>
<p>$8</p>
</div>


<div class="card">
<img src="{% static 'italian pasta.jpg' %}">
<h3>Italian Pasta</h3>
<p>$10</p>
</div>


</div>

</section>


<footer>
<p>© 2026 Spice Garden Restaurant</p>
</footer>

</body>
</html>
```
contact.html
```
{% load static %}

<!DOCTYPE html>
<html>
<head>

<title>Contact</title>

<link rel="stylesheet" href="{% static 'style.css' %}">

</head>

<body>

<header>
<h1>Contact Us</h1>
</header>

<section class="contact">

<form>

<label>Name</label>
<input type="text" placeholder="Enter your name">

<label>Email</label>
<input type="email" placeholder="Enter your email">

<label>Message</label>
<textarea placeholder="Write message"></textarea>

<button type="submit">Send Message</button>

</form>

</section>

</body>
</html>
```

## OUTPUT:

<img width="1915" height="1152" alt="Screenshot 2026-03-16 193256" src="https://github.com/user-attachments/assets/7397366a-4dbb-49df-ba69-fb23f8c762c0" />
<img width="1918" height="1072" alt="Screenshot 2026-03-16 192845" src="https://github.com/user-attachments/assets/7bde9967-70ae-4fc8-8f49-58a2c135dc46" />
<img width="1901" height="1099" alt="Screenshot 2026-03-16 192707" src="https://github.com/user-attachments/assets/442d7658-530d-4b95-a622-c045efb1289f" />
<img width="1918" height="1101" alt="Screenshot 2026-03-16 192054" src="https://github.com/user-attachments/assets/5d3f4897-f34d-471c-9628-c9ab2a6e4a1a" />



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
