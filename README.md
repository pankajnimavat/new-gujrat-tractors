# new-gujrat-tractors
new-gujrat-tractors
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>New Gujrat Tractors | Premium Industrial & Road Roller Parts Kolkata</title>
    <style>
        /* Modern CSS Variables for Styling */
        :root {
            --primary-color: #e67e22; /* Industrial Orange */
            --secondary-color: #2c3e50; /* Deep Machinery Navy */
            --light-bg: #f8f9fa;
            --dark-text: #333333;
            --white: #ffffff;
            --gray: #7f8c8d;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            color: var(--dark-text);
            line-height: 1.6;
            background-color: var(--white);
        }

        /* Header & Navigation */
        header {
            background-color: var(--secondary-color);
            padding: 15px 5%;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo h1 {
            color: var(--primary-color);
            font-size: 24px;
            font-weight: 700;
        }

        .logo span {
            color: var(--white);
            font-size: 14px;
            display: block;
            font-weight: 300;
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 25px;
        }

        nav ul li a {
            color: var(--white);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: var(--primary-color);
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(44, 62, 80, 0.85), rgba(44, 62, 80, 0.85)), url('https://unsplash.com') no-repeat center center/cover;
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: var(--white);
            padding: 0 20px;
        }

        .hero h2 {
            font-size: 42px;
            margin-bottom: 15px;
            letter-spacing: 1px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 25px;
            max-width: 600px;
        }

        .btn {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 12px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
            display: inline-block;
        }

        .btn:hover {
            background-color: #d35400;
        }

        /* Main Container layout */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 60px 20px;
        }

        .section-title {
            text-align: center;
            font-size: 32px;
            color: var(--secondary-color);
            margin-bottom: 40px;
            position: relative;
        }

        .section-title::after {
            content: '';
            width: 60px;
            height: 3px;
            background-color: var(--primary-color);
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
        }

        /* About Section */
        .about-grid {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 40px;
        }

        .about-text p {
            margin-bottom: 15px;
            font-size: 16px;
            color: #555;
        }

        .badge-box {
            background-color: var(--light-bg);
            padding: 20px;
            border-left: 5px solid var(--primary-color);
            border-radius: 4px;
        }

        .badge-box h4 {
            color: var(--secondary-color);
            margin-bottom: 10px;
        }

        /* Products Categories Section */
        .products-section {
            background-color: var(--light-bg);
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .product-card {
            background-color: var(--white);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: transform 0.3s;
            border: 1px solid #eef2f3;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        .product-info {
            padding: 20px;
        }

        .product-info h3 {
            color: var(--secondary-color);
            margin-bottom: 10px;
            font-size: 18px;
        }

        .product-info p {
            color: var(--gray);
            font-size: 14px;
            margin-bottom: 15px;
        }

        .tag {
            display: inline-block;
            background-color: #ebf5fb;
            color: #2980b9;
            padding: 4px 10px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
        }

        /* Factsheet Table */
        .factsheet-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }

        .factsheet-table th, .factsheet-table td {
            padding: 15px 20px;
            text-align: left;
            border-bottom: 1px solid #e0e0e0;
        }

        .factsheet-table th {
            background-color: var(--secondary-color);
            color: var(--white);
            font-weight: 600;
        }

        .factsheet-table tr:nth-child(even) {
            background-color: var(--light-bg);
        }

        /* Contact Section */
        .contact-box {
            background: var(--secondary-color);
            color: var(--white);
            padding: 40px;
            border-radius: 8px;
            text-align: center;
        }

        .contact-box h3 {
            font-size: 28px;
            margin-bottom: 15px;
            color: var(--primary-color);
        }

        .contact-details {
            margin: 25px 0;
            font-size: 18px;
        }

        .contact-details p {
            margin-bottom: 10px;
        }

        /* Footer */
        footer {
            background-color: #1a252f;
            color: var(--gray);
            text-align: center;
            padding: 20px;
            font-size: 14px;
            border-top: 1px solid #2c3e50;
        }

        /* Responsive Breakpoints */
        @media (max-width: 768px) {
            .nav-container {
                flex-direction: column;
                text-align: center;
            }
            nav ul {
                margin-top: 15px;
            }
            nav ul li {
                margin: 0 10px;
            }
            .about-grid {
                grid-template-columns: 1fr;
            }
            .hero h2 {
                font-size: 32px;
            }
        }
    </style>
</head>
<body>

    <!-- Header Navigation -->
    <header>
        <div class="nav-container">
            <div class="logo">
                <h1>NEW GUJRAT TRACTORS</h1>
                <span>Verified Industrial Supplier | Kolkata</span>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#factsheet">Factsheet</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Banner Section -->
    <section class="hero">
        <h2>Reliable Heavy Machinery & Spares</h2>
        <p>Serving the industrial market with premium Road Rollers, Drive Gears, and customized Machined Components for over a decade.</p>
        <a href="#contact" class="btn">Get Best Price</a>
    </section>

    <!-- About Section -->
    <section id="about" class="container">
        <h2 class="section-title">About Our Company</h2>
        <div class="about-grid">
            <div class="about-text">
                <p><strong>New Gujrat Tractors</strong> is an established and highly trusted retailer based out of Kolkata, West Bengal. With over <strong>10 years</strong> of verified experience and industrial presence, we have carved a niche in providing top-tier machinery components and spare parts.</p>
                <p>We pride ourselves on sourcing robust, heavy-duty parts that withstand the toughest structural environments. Whether you operate precision rack pinions or require comprehensive replacement spares for commercial road rollers, our catalog is optimized to meet strict industrial standards.</p>
            </div>
            <div class="badge-box">
                <h4>Why Choose Us?</h4>
                <p>✔️ 10+ Years Trust Asset</p>
                <p>✔️ Verified IndiaMART Member</p>
                <p>✔️ Structured Proprietorship Firm</p>
                <p>✔️ Located in West Bengal's Hub</p>
            </div>
        </div>
    </section>

    <!-- Products & Categories Section -->
    <section id="products" class="products-section">
        <div class="container">
            <h2 class="section-title">Explore Our Categories</h2>
            <div class="product-grid">
                
                <!-- Category 1 -->
