# Vertex-Hub
Dedicated to making scripts premium (paid and free) , for a fast growing community and marketing life.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vertex Development - Roblox Exploits</title>
    <style>
        :root {
            --primary: #00aaff;
            --dark: #0a0a0a;
            --light: #ffffff;
        }
        * { margin:0; padding:0; box-sizing:border-box; }
        body {
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #0a0a0a, #1a1a1a);
            color: var(--light);
            line-height: 1.6;
        }
        header {
            background: rgba(10,10,10,0.95);
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid var(--primary);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        .logo {
            font-size: 2rem;
            font-weight: bold;
            color: var(--primary);
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://picsum.photos/id/1015/1920/1080') center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .hero h1 {
            font-size: 4rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.5rem;
            max-width: 700px;
            margin: 0 auto 2rem;
        }
        .btn {
            display: inline-block;
            padding: 15px 40px;
            background: var(--primary);
            color: white;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }
        .btn:hover { transform: scale(1.05); background: #0088cc; }
        .pricing {
            padding: 80px 5%;
            background: #111;
        }
        .pricing-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .card {
            background: #1a1a1a;
            border-radius: 12px;
            padding: 30px;
            text-align: center;
            border: 1px solid #333;
            transition: 0.3s;
        }
        .card:hover {
            transform: translateY(-10px);
            border-color: var(--primary);
        }
        .price {
            font-size: 2.5rem;
            color: var(--primary);
            margin: 15px 0;
        }
        footer {
            text-align: center;
            padding: 40px;
            background: #0a0a0a;
            border-top: 1px solid #333;
        }
        .discord {
            color: #7289da;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">VERTEX DEVELOPMENT</div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Features</a>
            <a href="#">Pricing</a>
            <a href="#">Discord</a>
        </nav>
    </header>

    <section class="hero">
        <div>
            <h1>VERTEX DEVELOPMENT</h1>
            <p>The most advanced universal Roblox exploit. Silent aim, hitbox expander, fly, ESP, and more.</p>
            <a href="#pricing" class="btn">Get Access Now</a>
        </div>
    </section>

    <section class="pricing" id="pricing">
        <h2 style="text-align:center; margin-bottom:50px; font-size:2.5rem;">Choose Your Plan</h2>
        <div class="pricing-grid">
            <div class="card">
                <h3>1 Week</h3>
                <div class="price">$1.50</div>
                <p>Full access • All features</p>
                <a href="#" class="btn" style="margin-top:20px;">Buy Now</a>
            </div>
            <div class="card">
                <h3>3 Weeks</h3>
                <div class="price">$3.00</div>
                <p>Full access • All features</p>
                <a href="#" class="btn" style="margin-top:20px;">Buy Now</a>
            </div>
            <div class="card">
                <h3>1 Month</h3>
                <div class="price">$5.00</div>
                <p>Full access • All features</p>
                <a href="#" class="btn" style="margin-top:20px;">Buy Now</a>
            </div>
            <div class="card">
                <h3>3 Months</h3>
                <div class="price">$7.00</div>
                <p>Full access • All features</p>
                <a href="#" class="btn" style="margin-top:20px;">Buy Now</a>
            </div>
            <div class="card">
                <h3>6 Months</h3>
                <div class="price">$10.00</div>
                <p>Full access • All features</p>
                <a href="#" class="btn" style="margin-top:20px;">Buy Now</a>
            </div>
            <div class="card">
                <h3>Lifetime</h3>
                <div class="price">$15.00</div>
                <p>Full access • All features • Updates forever</p>
                <a href="#" class="btn" style="margin-top:20px;">Buy Now</a>
            </div>
        </div>
    </section>

    <footer>
        <p>Vertex Development © 2026 • Universal Roblox Exploit</p>
        <p><a href="https://discord.gg/69e8kgeCyA" class="discord" target="_blank">Join Discord</a></p>
    </footer>
</body>
</html>
