### Commercial_Website1

### Date:

### AIM:
To create a commercial website using CSS Flexbox.

### ALGORITHM
STEP 1
Create an HTML file (index.html)

STEP 2
Create a CSS file (style.css)

STEP 3
Include a navigation bar with links to different sections.

STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

STEP 5
Include social media links at the footer with copyright information.

STEP 6
Define global styles for fonts, colors, and layout.

STEP 7
Style the header, navigation bar, and sections.

STEP 8
Use Flexbox for layout design.

STEP 9
Add hover effects and transitions for interactivity.

STEP 10
Add Images and Media.

STEP 11
Use optimized images for a professional look.

STEP 12
Open the HTML file in a browser to check layout and functionality.

STEP 13
Fix styling issues and refine content placement.

STEP 14
Deploy the website.

STEP 15
Upload to GitHub Pages for free hosting.

### PROGRAM
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ShopEase - Online Shopping</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }

        /* Navigation Bar */
        header {
            background-color: #222;
            color: white;
            padding: 20px;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }

        nav h2 {
            color: orange;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 25px;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        /* Hero Section */
        .hero {
            background-color: #2874f0;
            color: white;
            text-align: center;
            padding: 60px 20px;
        }

        .hero h1 {
            font-size: 35px;
            margin-bottom: 15px;
        }

        .hero button {
            padding: 12px 25px;
            background-color: orange;
            border: none;
            margin-top: 20px;
            cursor: pointer;
        }

        /* Products Section */
        .products {
            display: flex;
            justify-content: center;
            align-items: stretch;
            flex-wrap: wrap;
            gap: 20px;
            padding: 40px 20px;
        }

        .product {
            background-color: white;
            padding: 20px;
            width: 250px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 2px 8px #ccc;
        }

        .product img {
            width: 100%;
            height: 160px;
            object-fit: contain;
        }

        .product h3 {
            margin: 15px 0;
        }

        .product p {
            color: green;
            font-weight: bold;
        }

        .product button {
            background-color: #2874f0;
            color: white;
            border: none;
            padding: 10px 20px;
            margin-top: 15px;
            cursor: pointer;
        }

        /* Footer */
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px;
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            nav {
                flex-direction: column;
                gap: 15px;
            }

            nav ul {
                flex-direction: column;
                text-align: center;
                gap: 12px;
            }

            .hero h1 {
                font-size: 25px;
            }

            .products {
                flex-direction: column;
                align-items: center;
            }

            .product {
                width: 90%;
            }
        }
        .product img {
    width: 100%;
    height: 160px;
    object-fit: contain;
}
    </style>
</head>

<body>

    <!-- Navigation -->
    <header>
        <nav>
            <h2>ShopEase</h2>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Welcome to ShopEase</h1>
        <p>Discover amazing products at affordable prices!</p>
        <button>Shop Now</button>
    </section>

    <!-- Products -->
    <section class="products">

        <div class="product">
            <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?w=500"
     alt="Headphones">
            <h3>Headphones</h3>
            <p>₹999</p>
            <button>Buy Now</button>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?w=500"
     alt="Smart Watch">
            <h3>Smart Watch</h3>
            <p>₹1,499</p>
            <button>Buy Now</button>
        </div>

        <div class="product">
            <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=500"
     alt="Sports Shoes">
            <h3>Sports Shoes</h3>
            <p>₹1,999</p>
            <button>Buy Now</button>
        </div>

    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 ShopEase. All Rights Reserved.</p>
        <p>Email: support@shopease.com</p>
    </footer>

</body>
</html>
```
### OUTPUT

<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/42790b2d-cb6f-483f-a1ac-ef1d1fa93e3a" />

### RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
