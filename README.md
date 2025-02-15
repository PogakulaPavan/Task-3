# Task-3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Page</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background: #333;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #e67e22;
        }
        .product-container {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            background: white;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        .product-container:hover {
            transform: scale(1.02);
        }
        .product-image img {
            max-width: 300px;
            border-radius: 10px;
        }
        .product-details {
            margin-left: 20px;
        }
        .price {
            font-size: 24px;
            color: #27ae60;
        }
        .add-to-cart {
            background: #e67e22;
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .add-to-cart:hover {
            background: #d35400;
        }
        .reviews, .related-products {
            text-align: center;
            margin: 20px;
            background:white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .related-container {
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        .related-item {
            transition: transform 0.3s;
        }
        .related-item:hover {
            transform: scale(1.1);
        }
        .related-item img {
            max-width: 100px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main class="product-container">
        <div class="product-image">
            <img src="C:\Users\pavan\OneDrive\Pictures\Screenshots\h1.png" alt="Product Image">
        </div>
        <div class="product-details">
            <h1>Product Name</h1>
            <p class="price">$99.99</p>
            <p class="description">This is a detailed description of the product, highlighting its features and benefits.</p>
            <button class="add-to-cart">Add to Cart</button>
        </div>
    </main>   
    <section class="reviews">
        <h2>Customer Reviews</h2>
        <p>&#9733; &#9733; &#9733; &#9733; &#9734; (4.0/5)</p>
        <p>"Great product! Highly recommend."</p>
    </section>   
</body>
</html>
