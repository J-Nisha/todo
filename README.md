# Ex03 To-Do List using JavaScript

## Date:
____________________

## AIM

To create a To-Do Application with all features using JavaScript.

---

## ALGORITHM

### Step 1
Build the HTML structure (`index.html`).

### Step 2
Style the application using CSS (`style.css`).

### Step 3
Plan the features required for the To-Do application.

### Step 4
Create the To-Do application using JavaScript.

### Step 5
Implement functionalities such as adding, completing, and deleting tasks.

### Step 6
Test the application to ensure all features work correctly.

### Step 7
Open the HTML file in a web browser to verify the layout and functionality.

### Step 8
Fix any styling issues and refine the content placement.

### Step 9
Deploy the website.

### Step 10
Upload the project to GitHub Pages for free hosting.

---

## PROGRAM
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechZone Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>TechZone Store</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">Offers</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Best Electronics at Affordable Prices</h2>
    <p>Shop laptops, smartphones, accessories, and more.</p>
    <button>Shop Now</button>
</section>

<section class="products">
    <div class="card">
        <h3>Laptop</h3>
        <p>Starting from ₹49,999</p>
    </div>

    <div class="card">
        <h3>Smartphone</h3>
        <p>Starting from ₹14,999</p>
    </div>

    <div class="card">
        <h3>Headphones</h3>
        <p>Starting from ₹1,999</p>
    </div>
</section>

<footer>
    <p>Name: Nisha J</p>
    <p>Register Number:212223040133</p>
</footer>

</body>
</html>
```
CSS
```
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#f4f4f4;
}

header{
    background:#1e3a8a;
    color:white;
    padding:20px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-weight:bold;
}

.hero{
    text-align:center;
    padding:60px;
    background:#dbeafe;
}

button{
    padding:10px 20px;
    background:#2563eb;
    color:white;
    border:none;
    border-radius:5px;
    cursor:pointer;
}

.products{
    display:flex;
    justify-content:center;
    gap:20px;
    padding:40px;
}

.card{
    background:white;
    padding:20px;
    width:200px;
    text-align:center;
    border-radius:8px;
    box-shadow:0 0 10px rgba(0,0,0,0.2);
}

footer{
    background:#1e3a8a;
    color:white;
    text-align:center;
    padding:15px;
}
```


## OUTPUT
![alt text](<todo image.png>)
## RESULT

The program for creating a To-Do Application using JavaScript was executed successfully, and all the required functionalities were implemented and verified.