# Ex02- Commercial Website
## Name: Arunkumar S A
## Reg No: 212223220009

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Business Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
        }

        /* Navbar */
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #222;
            color: white;
            padding: 15px 50px;
        }

        .navbar ul {
            display: flex;
            list-style: none;
        }

        .navbar ul li {
            margin-left: 20px;
        }

        .navbar ul li a {
            color: white;
            text-decoration: none;
        }

        /* Hero Section */
        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 80vh;
            background: linear-gradient(to right, #007bff, #00c6ff);
            color: white;
            text-align: center;
            flex-direction: column;
        }

        .hero button {
            padding: 10px 20px;
            margin-top: 20px;
            border: none;
            background: #fff;
            color: #007bff;
            cursor: pointer;
            font-weight: bold;
        }

        /* Services Section */
        .services {
            padding: 50px;
            text-align: center;
        }

        .service-container {
            display: flex;
            justify-content: space-around;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .service-box {
            background: #f4f4f4;
            padding: 20px;
            width: 300px;
            margin: 10px;
            border-radius: 5px;
        }

        /* Products Section */
        .products {
            padding: 50px;
            background: #eee;
            text-align: center;
        }

        .product-container {
            display: flex;
            justify-content: space-evenly;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        .product-box {
            background: white;
            width: 250px;
            padding: 20px;
            margin: 10px;
            border-radius: 5px;
        }

        /* Footer */
        .footer {
            display: flex;
            justify-content: center;
            align-items: center;
            background: #222;
            color: white;
            height: 60px;
        }

        /* Responsive */
        @media(max-width: 768px) {
            .navbar {
                flex-direction: column;
            }

            .service-container,
            .product-container {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <div class="navbar">
        <h2>MyBusiness</h2>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Products</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </div>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Welcome to Our Company</h1>
        <p>We provide high quality services for your business growth.</p>
        <button>Learn More</button>
    </section>

    <!-- Services Section -->
    <section class="services">
        <h2>Our Services</h2>
        <div class="service-container">
            <div class="service-box">
                <h3>Web Design</h3>
                <p>Professional and modern website designs.</p>
            </div>
            <div class="service-box">
                <h3>Marketing</h3>
                <p>Grow your business with digital marketing.</p>
            </div>
            <div class="service-box">
                <h3>Consulting</h3>
                <p>Expert advice to scale your company.</p>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section class="products">
        <h2>Our Products</h2>
        <div class="product-container">
            <div class="product-box">
                <h3>Product 1</h3>
                <p>$49.99</p>
            </div>
            <div class="product-box">
                <h3>Product 2</h3>
                <p>$79.99</p>
            </div>
            <div class="product-box">
                <h3>Product 3</h3>
                <p>$99.99</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <div class="footer">
        <p>© 2026 MyBusiness. All Rights Reserved.</p>
    </div>

</body>
</html>
```

## OUTPUT

<img width="1910" height="976" alt="Screenshot 2026-02-24 100301" src="https://github.com/user-attachments/assets/caa2a1cf-0253-4ba2-a207-fede2dd36096" />

<img width="1890" height="813" alt="Screenshot 2026-02-24 100320" src="https://github.com/user-attachments/assets/0954a54b-0c53-4864-bf15-9afd7a03f9de" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
