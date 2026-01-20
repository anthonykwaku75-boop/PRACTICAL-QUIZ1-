<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Digital Business</title>

    <style>
        body {
            background-color: #1f2937;
            font-family: "Segoe UI", Arial, sans-serif;
        }

        .container {
            width: 900px;
            margin: 30px auto;
            background-color: #f9fafb;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
        }

        /* Header: left-aligned, small text, with short sentence */
        .header {
            background-image:
                linear-gradient(rgba(0,0,0,0.55), rgba(0,0,0,0.55)),
                url("https://images.unsplash.com/photo-1556761175-5973dc0f32e7");
            background-size: cover;
            background-position: center;
            color: #ffffff;
            padding: 50px 50px;
            text-align: left;
        }

        .header h1 {
            margin: 0;
            font-size: 32px;
            letter-spacing: 2px;
            font-weight: 700;
        }

        .header p {
            margin-top: 10px;
            font-size: 16px;
            letter-spacing: 1px;
            opacity: 0.9;
        }

        /* Content layout */
        .content {
            display: flex;
        }

        .main-content {
            width: 65%;
            padding: 25px;
        }

        .main-content h2 {
            color: #1d4ed8;
        }

        .main-content p {
            text-align: justify;
            line-height: 1.8;
            color: #111827;
        }

        /* Sidebar */
        .sidebar {
            width: 35%;
            background-color: #e0e7ff;
            padding: 25px;
        }

        .sidebar h3 {
            background-color: #3730a3;
            color: white;
            padding: 12px;
            margin-top: 0;
            border-radius: 5px;
        }

        .sidebar ul {
            padding-left: 20px;
            list-style-type: square;
        }

        .sidebar li {
            margin-bottom: 10px;
            color: #1e3a8a;
        }

        /* Footer */
        .footer {
            background-color: #3730a3;
            color: white;
            text-align: center;
            padding: 16px;
            font-size: 14px;
        }

        /* Responsive for smaller screens */
        @media (max-width: 900px) {
            .content {
                flex-direction: column;
            }

            .main-content, .sidebar {
                width: 100%;
            }

            .header h1 {
                font-size: 28px;
                text-align: center;
            }

            .header p {
                text-align: center;
            }
        }
    </style>
</head>

<body>

<div class="container">

    <!-- Header: Left-aligned, small title, short sentence -->
    <div class="header">
        <h1>DIGITAL BUSINESS</h1>
        <p>Empowering modern businesses</p>
    </div>

    <!-- Main content and sidebar -->
    <div class="content">

        <!-- Main Content -->
        <div class="main-content">
            <h2>Digital Marketing</h2>
            <p>
                Digital marketing refers to the promotion of products and services using digital
                technologies such as the internet, social media, search engines, and email.
                Businesses use digital marketing to reach a wider audience, build brand awareness,
                and engage customers in real time. Common strategies include social media marketing,
                search engine optimization, and online advertising.
            </p>

            <h2>E-Commerce</h2>
            <p>
                E-commerce involves buying and selling goods and services through electronic
                platforms such as websites and mobile applications. It allows businesses to
                operate beyond physical locations and serve customers globally. E-commerce
                improves convenience, reduces operational costs, and supports modern business growth.
            </p>

            <h2>Online Entrepreneurship</h2>
            <p>
                Online entrepreneurship focuses on creating and managing businesses that operate
                mainly on digital platforms. Examples include online stores, digital services,
                and content creation. Successful online entrepreneurs rely on innovation,
                technology, and effective digital strategies to compete in the global market.
            </p>
        </div>

        <!-- Sidebar -->
        <div class="sidebar">
            <h3>Key Areas</h3>

            <strong>Marketing Tools</strong>
            <ul>
                <li>Social Media Platforms</li>
                <li>Email Marketing</li>
                <li>Search Engine Optimization</li>
            </ul>

            <strong>E-Commerce Models</strong>
            <ul>
                <li>Business to Consumer (B2C)</li>
                <li>Business to Business (B2B)</li>
                <li>Online Marketplaces</li>
            </ul>

            <strong>Skills Needed</strong>
            <ul>
                <li>Digital Literacy</li>
                <li>Content Creation</li>
                <li>Financial Management</li>
            </ul>
        </div>

    </div>

    <!-- Footer -->
    <div class="footer">
        © Copyright 2026 Digital Business Page
    </div>

</div>

</body>
</html>
