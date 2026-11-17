<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Danger-Fashion | Premium Quality Clothes</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #111;
            color: #fff;
            padding: 15px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
            letter-spacing: 1px;
            color: #ff4757;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin-left: 20px;
            font-size: 15px;
        }
        nav a:hover {
            color: #ff4757;
        }
        .hero {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1441986300917-64674bd600d8?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            color: #fff;
            text-align: center;
            padding: 100px 20px;
        }
        .hero h1 {
            font-size: 42px;
            margin-bottom: 15px;
        }
        .hero p {
            font-size: 18px;
            max-width: 600px;
            margin: 0 auto 25px;
            color: #ddd;
        }
        .btn {
            display: inline-block;
            background-color: #ff4757;
            color: #fff;
            padding: 12px 28px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #e84118;
        }
        .container {
            max-width: 1100px;
            margin: 50px auto;
            padding: 0 20px;
        }
        .section-title {
            text-align: center;
            font-size: 30px;
            margin-bottom: 40px;
            color: #111;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }
        .product-card {
            background: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0,0,0,0.08);
            text-align: center;
            padding-bottom: 20px;
            transition: transform 0.3s;
        }
        .product-card:hover {
            transform: translateY(-5px);
        }
        .product-card img {
            width: 100%;
            height: 260px;
            object-fit: cover;
        }
        .product-card h3 {
            margin: 15px 0 8px;
            font-size: 20px;
        }
        .price {
            color: #ff4757;
            font-size: 18px;
            font-weight: bold;
            margin-bottom: 15px;
        }
        .whatsapp-btn {
            background-color: #25D366;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 14px;
            font-weight: bold;
            display: inline-block;
        }
        .whatsapp-btn:hover {
            background-color: #1ebe57;
        }
        footer {
            background-color: #111;
            color: #fff;
            text-align: center;
            padding: 30px 20px;
            margin-top: 60px;
        }
        footer p {
            margin: 5px 0;
            font-size: 14px;
            color: #bbb;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">Danger-Fashion</div>
        <nav>
            <a href="#home">হোম</a>
            <a href="#products">কালেকশন</a>
            <a href="#contact">যোগাযোগ</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Danger-Fashion</h1>
        <p>Very premium quality clothes at a very low price from a number one brand.</p>
        <a href="#products" class="btn">কালেকশন দেখুন</a>
    </section>

    <div class="container" id="products">
        <h2 class="section-title">আমাদের প্রিমিয়াম কালেকশন</h2>
        <div class="products">
            
            <!-- প্রোডাক্ট ১ -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?auto=format&fit=crop&w=600&q=80" alt="Premium T-Shirt">
                <h3>প্রিমিয়াম কটন টি-শার্ট</h3>
                <p class="price">৳ ৪৫০</p>
                <a href="https://wa.me/8801342213224?text=আমি%20প্রিমিয়াম%20কটন%20টি-শার্টটি%20অর্ডার%20করতে%20চাই।" target="_blank" class="whatsapp-btn">WhatsApp-এ অর্ডার করুন</a>
            </div>

            <!-- প্রোডাক্ট ২ -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1596755094514-f87e34085b2c?auto=format&fit=crop&w=600&q=80" alt="Casual Shirt">
                <h3>স্টাইলিশ ক্যাজুয়াল শার্ট</h3>
                <p class="price">৳ ৮৫০</p>
                <a href="https://wa.me/8801342213224?text=আমি%20স্টাইলিশ%20ক্যাজুয়াল%20শার্টটি%20অর্ডার%20করতে%20চাই।" target="_blank" class="whatsapp-btn">WhatsApp-এ অর্ডার করুন</a>
            </div>

            <!-- প্রোডাক্ট ৩ -->
            <div class="product-card">
                <img src="https://images.unsplash.com/photo-1542272604-787c3835535d?auto=format&fit=crop&w=600&q=80" alt="Denim Jeans">
                <h3>প্রিমিয়াম ডেনিম জিন্স</h3>
                <p class="price">৳ ১১৫০</p>
                <a href="https://wa.me/8801342213224?text=আমি%20প্রিমিয়াম%20ডেনিম%20জিন্সটি%20অর্ডার%20করতে%20চাই।" target="_blank" class="whatsapp-btn">WhatsApp-এ অর্ডার করুন</a>
            </div>

        </div>
    </div>

    <footer id="contact">
        <h3>Danger-Fashion</h3>
        <p>সেরা মানের পোশাক, সাশ্রয়ী মূল্যে।</p>
        <p>📞 WhatsApp / যোগাযোগ: 01342213224</p>
        <p>&copy; 2026 Danger-Fashion. সর্বস্বত্ব সংরক্ষিত।</p>
    </footer>

</body>
</html>
