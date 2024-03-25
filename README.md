<!DOCTYPE html>
<html>
<head>
  <title>AL HASAN SHOP</title>
  <style>
    /* CSS Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #666;
    }

    .header {
      background-color: #355;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    .hero {
      background-image: url('selling-hero-image.jpg');
      background-size: cover;
      background-position: center;
      height: 500px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
    }
    
    header-logo {
      display: flex;
      align-items: center;
    }

    .header-logo img {
      width: 40px;
      height: 40px;
      margin-right: 15px;
    }

    .header-menu {
      display: flex;
      align-items: center;
    }

    .dropdown {
      position: relative;
      display: inline-block;
    }

    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #355;
      min-width: 100px;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
      z-index: 1;
    }

    .dropdown:hover .dropdown-content {
      display: block;
    }

    .dropdown-content a {
      color: #fff;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
    }

    .product-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 50px 0;
    }

    .product {
      width: 300px;
      margin: 20px;
      padding: 20px;
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      text-align: center;
      transition: transform 0.3s ease-in-out;
    }

    .product:hover {
      transform: scale(1.1);
    }

    .product img {
      max-width: 100%;
      height: auto;
      margin-bottom: 20px;
    }

    .product h3 {
      color: #333;
      margin-bottom: 10px;
    }

    .product p {
      color: #777;
      margin-bottom: 20px;
    }

    .product .price {
      color: #000;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .footer {
      background-color: #355;
      color: #fff;
      padding: 20px;
      text-align: center;
      font-size: 14px;
    }

    .footer p {
      margin: 0;
    }

    .footer a {
      color: #fff;
      text-decoration: none;
    }

    .button {
      background-color: #355;
      color: #fff;
      padding: 10px 10px;
      text-decoration: none;
      display: inline-block;
      font-size: 20px;
      border: none;
      border-radius: 4px;
      transition: background-color 0.3s ease-in-out;
    }

    .button:hover {
      background-color: #222;
    }

    /* JavaScript */
    document.addEventListener("DOMContentLoaded", function(event) {
      // JavaScript code to handle any dynamic behavior or interactions
      // You can add your JavaScript code here
    });
  </style>
</head>
<body>
    <div class="header">
    <div class="header-logo">
        <a href="https://htmlcssjscode266.netlify.app/">
      <img src="https://cdn-icons-png.flaticon.com/512/1170/1170678.png" alt="Shopping Cart Icon">
      </a>
   </div>
    <h1>✩ 𝐀𝐋 𝐇𝐀𝐒𝐀𝐍 𝐒𝐇𝐎𝐏 ✩</h1>
    <h3>𝗪𝗲𝗹𝗰𝗼𝗺𝗲 𝘁𝗼 𝗔𝗹 𝗛𝗮𝘀𝗮𝗻 𝗦𝗵𝗼𝗽,<h3>you will easily find the best products at the best prices here</h3>
   </div>
    <div class="header-menu">
      <div class="dropdown">
        <button class="button">Menu &#9776;</button>
        <div class="dropdown-content">
          <a href="#">About</a>
          <a href="#">Login</a>
          <a href="#">Best Products</a>
        </div>
       </div>
    <form action="#" method="get">
      <input type="text" name="search" placeholder="Search...">
      <button type="submit">Search</button>
    </form>
  </div>
  <div class="product-container">
    <div class="product">
      <a href="https://amzn.to/3O4EmKg">
        <img src="https://m.media-amazon.com/images/I/610pghkO81L._SX679_.jpg" alt="product 2">
      </a>
      </a>
      <h3>Apple iPhone 14 Pro Max (1 TB) - Space Black</h3>
      <p>full details Clic kHere 👇 </p>
      <p class="price">-9% ₹1,72,990</p>
      <a href="https://amzn.to/3O4EmKg" class="button">Buy Now</a>
      <a href="https://amzn.to/3O4EmKg" class="button">Add to Cart 🛒</a>
    </div>
    <div class="product">
      <a href="https://amzn.to/3PN1Btz">
        <img src="https://m.media-amazon.com/images/I/41iKrrClH5L._SX300_SY300_QL70_FMwebp_.jpg" alt="Product 3">
      </a>
      <h3>Samsung Galaxy S23 Ultra 5G (Cream, 12GB, 512GB Storage)</h3>
      <p>full details Clic kHere 👇 </p>
      <p class="price">-17% ₹1,34,999</p>
      <a href="https://amzn.to/3PN1Btz" class="button">Buy Now</a>
      <a href="https://amzn.to/3PN1Btz" class="button">Add to Cart 🛒</a>
    </div>
    <div class="product">
      <a href="https://amzn.to/46BQ0DI">
        <img src="https://m.media-amazon.com/images/I/6137nCoO7aS._SX679_.jpg" alt="Product 2">
      </a>
      <h3>QAZ SQ8 Portable Mini Body Nanny CAM 720p NO WiFi Security Camera | Spy Gadget</h3>
      <p>full details Clic kHere 👇 </p>
      <p class="price">65% ₹1,049</p>
      <a href="https://amzn.to/46BQ0DI" class="button">Buy Now</a>
      <a href="https://amzn.to/46BQ0DI" class="button">Add to Cart 🛒</a>
    </div>
    <div class="product">
      <a href="https://amzn.to/3pCFdIG">
        <img src="https://m.media-amazon.com/images/I/31npD8OiHiL._SX300_SY300_QL70_FMwebp_.jpg" alt="Product 3">
      </a>
      <h3>Chic Buddy Infinity Cube Fidget Toy Stress Relieving Fidgeting Game for Kids and Adults,Cute Mini Unique Gadget for Anxiety Relief and Kill Time (Macaron Blue)</h3>
      <p>full details Clic kHere 👇 </p>
      <p class="price">24% ₹289</p>
      <a href="https://amzn.to/3pCFdIG" class="button">Buy Now</a>
      <a href="https://amzn.to/3pCFdIG" class="button">Add to Cart 🛒</a>
    </div>
    <div class="product">
      <a href="https://amzn.to/3O4E1ao">
        <img src="https://m.media-amazon.com/images/I/31UqUeF7UoL.jpg" alt="Product 2">
      </a>
      <h3>tripanto,Foldable Multitool Key chain (7 in 1), Cutting Pliers with Screw Driver and Safety Equipments, Unique Keychain for Mens</h3>
      <p>full details Clic kHere 👇 </p>
      <p class="price">34% ₹529</p>
      <a href="https://amzn.to/3O4E1ao" class="button">Buy Now</a>
      <a href="https://amzn.to/3O4E1ao" class="button">Add to Cart 🛒</a>
    </div>
    <div class="product">
      <a href="https://amzn.to/3NH2RvF">
        <img src="https://m.media-amazon.com/images/I/416D2INKqgL._SX300_SY300_QL70_FMwebp_.jpg" alt="Product 3">
      </a>
      <h3>Sounce Shutter Remote Control with Bluetooth Wireless Technology - Create Amazing Photos and Videos Hands-Free - Works with Most Smartphones and Tablets (iOS and Android) (Black)</h3>
      <p>full details Clic kHere 👇 </p>
      <p class="price">
-43% ₹169</p>
      <a href="https://amzn.to/3NH2RvF" class="button">Buy Now</a>
      <a href="https://amzn.to/3NH2RvF" class="button">Add to Cart 🛒</a>
    </div>
    <div class="product">
      <a href="https://amzn.to/44h0DdB">
        <img src="https://m.media-amazon.com/images/I/518IViwQ-jS._SY300_SX300_.jpg" alt="Product 2">
      </a>
      <h3>GOCART WITH G LOGO Men's Nylon Outdoor Tactical Waist Bag EDC Molle Belt Waist Pouch Security Purse Phone Carrying Case (Brown)</h3>
      <p>full details Clic kHere 👇 </p>
      <p class="price">-56% ₹399</p>
      <a href="https://amzn.to/44h0DdB" class="button">Buy Now</a>
      <a href="https://amzn.to/44h0DdB" class="button">Add to Cart 🛒</a>
    </div>
    <div class="product">
      <a href="https://amzn.to/44rgJ3Y">
        <img src="https://m.media-amazon.com/images/I/41tMSpX+ebL._SY300_SX300_.jpg" alt="Product 3">
      </a>
      <h3>ibimble Car Accessories Solar Car Perfumes And Fresheners |Double Ring Crystal Auto Rotate Car Perfume Air Car Fresheners(Black)</h3>
      <p>full details Clic kHere 👇 </p>
      <p class="price">67% ₹499</p>
      <a href="https://amzn.to/44rgJ3Y" class="button">Buy Now</a>
      <a href="https://amzn.to/44rgJ3Y" class="button">Add to Cart 🛒</a>
    </div>
    <div class="product">
      <a href="https://amzn.to/3OeFpHP">
        <img src="https://m.media-amazon.com/images/I/61WQUXT+sGL._SX679_.jpg" alt="Product 2">
      </a>
      <h3>rts All in One Combo Card Reader for Pen Drive.Cameras. mobiles. PC. Laptop. Notebook. Tablet. or Docking Station. MP3s. PDAs,Color May Vary</h3>
      <p>full details Clic kHere 👇 </p>
      <p class="price">92% ₹398</p>
      <a href="https://amzn.to/3OeFpHP" class="button">Buy Now</a>
      <a href="https://amzn.to/3OeFpHP" class="button">Add to Cart 🛒</a>
    </div>
    <div class="product">
      <a href="https://amzn.to/46BG7pB">
        <img src="https://m.media-amazon.com/images/I/41Ck5zA25JL._SX300_SY300_QL70_FMwebp_.jpg" alt="Product 3">
      </a>
      <h3>CIPLAPLAST Rich Look Bathroom Cabinet with Mirror White | Storage Organiser | Strong Plastic Bathroom Shelves Wall Mounted | Bathroom Accessories| Mirror Cabinet- (Made in India)</h3>
      <p>full details Clic kHere 👇 </p>
      <p class="price">53% ₹1,399</p>
      <a href="https://amzn.to/46BG7pB" class="button">Buy Now</a>
      <a href="https://amzn.to/46BG7pB" class="button">Add to Cart 🛒</a>
    </div>
    <div class="product">
      <a href="https://amzn.to/44B6GcM">
        <img src="https://m.media-amazon.com/images/I/61bLcyrITDL._SX679_.jpg" alt="Product 2">
      </a>
      <h3>Novium HOVERPEN 2.0 - Futuristic Luxury Pen Made With Aerospace Alloys, Unique Aesthetic, Free Spinning Executive Pen, Cool Gadgets, Valentines Day Gifts for Men & Women (Mars Magma, Basic)</h3>
      <p>full details Clic kHere 👇 </p>
      <p class="price">13% ₹13,999</p>
      <a href="https://amzn.to/44B6GcM" class="button">Buy Now</a>
      <a href="https://amzn.to/44B6GcM" class="button">Add to Cart 🛒</a>
    </div>
  </div>
  <div class="footer">
    <p>&copy; 2023 AL HASAN SHOP. All rights reserved. | <a href="#">Terms and Conditions</a> | <a href="#">Privacy Policy</a></p>
  </div>
</body>
</html>
