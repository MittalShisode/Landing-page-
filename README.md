# Landing-page-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="index.css">
    <title>Shopping Landing Page</title>
</head>
<body>
    <nav>
        <div class="heading">Shopping Landing Page</div>
        <span class="sideMenuButton" onclick="openNavbar()">
            &#9776
        </span>
        <div class="navbar">
            <ul>
                <li><a href="#Home">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Sign Up</a></li>
            </ul>
        </div>
    </nav>
    <!-- Side navigation bar for responsive website -->
    <div class="sideNavigationBar" id="sideNavigationBar">
        <a href="#" class="closeButton" onclick="closeNavbar()">
            &#x274C
        </a>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Sign Up</a>
    </div>
    <!-- Content -->
    <div class="line" id="Home">
        <div class="side1">
            <h1>Shopping Made Easy</h1>
            <button>
                <a href="https://www.example.com/">
                    Explore More
                </a>
            </button>
        </div>
        <div class="side2">
            <img src="https://images.app.goo.gl/2KpM8aZcLJxKjieQ8" width="500">
        </div>
    </div>
    <section class="about" id="My Projects">
        <div class="content">
            <div class="title">
                <span>Popular Products</span>
            </div>
            <div class="boxes">
                <div class="box">
                    <div class="topic">
                        <a href="" target="_blank">
                            Electronics
                        </a>
                    </div>
                    <p>
                        Explore our wide range of electronics products.
                    </p>
                </div>
                <div class="box">
                    <div class="topic">
                        <a href="" target="_blank">
                            Fashion
                        </a>
                    </div>
                    <p>
                        Stay stylish with our latest fashion trends.
                    </p>
                </div>
                <div class="box">
                    <div class="topic">
                        <a href="" target="_blank">
                            Home Appliances
                        </a>
                    </div>
                    <p>
                        Upgrade your home with our latest appliances.
                    </p>
                </div>
            </div>
        </div>
    </section>
    <section class="contact" id="contact">
        <div class="content">
            <div class="title"><span>Sign Up</span></div>
            <div class="contactMenu">
                <div class="input1">
                    <div class="label1">Your Name</div>
                    <div class="input2">
                        <input type="text" placeholder="Enter your Name here">
                    </div>
                    <div class="label1">
                        <label>Your Email</label>
                    </div>
                    <div class="input2">
                      
                        <input type="text" placeholder="Enter your Email here">
                    </div>
                </div>
            </div>
        </div>
    </section>
    <script src="index.js"></script>
  </body>
  </body>
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

body {
    background-color: #f7f7f7;
    color: #333;
    font-family: "Fira Sans", sans-serif;
}

nav {
    width: 100%;
    height: 80px;
    display: flex;
    justify-content: space-between;
    padding: 20px 5%;
    background-color: #3498db;
}

nav.heading {
    font-size: 30px;
    font-weight: 700;
    color: white;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    padding: 8px 15px;
    border-radius: 10px;
    transition: 0.2s ease-in;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

nav ul li:hover {
    background-color: #2ecc71;
}

.sideMenuButton {
    font-size: 30px;
    cursor: pointer;
}

.sideNavigationBar {
