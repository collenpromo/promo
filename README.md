<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elite Gaming Rewards</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Montserrat:wght@800&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-deep: #0a0f1d;
            --bg-card: #161b2c;
            --accent-cyan: #00f2ff;
            --accent-blue: #3d5afe;
            --text-main: #e0e6ed;
            --text-dim: #94a3b8;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-deep);
            color: var(--text-main);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background-color: rgba(10, 15, 29, 0.9);
            backdrop-filter: blur(10px);
            padding: 15px 0;
            text-align: center;
            border-bottom: 1px solid rgba(0, 242, 255, 0.2);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo-text {
            font-family: 'Montserrat', sans-serif;
            font-size: 20px;
            color: var(--accent-cyan);
            text-transform: uppercase;
            letter-spacing: 3px;
            text-shadow: 0 0 10px rgba(0, 242, 255, 0.3);
        }

        .hero {
            padding: 80px 20px;
            text-align: center;
            background: radial-gradient(circle at top, #1e293b 0%, #0a0f1d 70%);
        }

        .hero h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 3rem;
            margin-bottom: 20px;
            background: linear-gradient(to right, #fff, var(--accent-cyan));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hero p {
            max-width: 700px;
            margin: 0 auto;
            color: var(--text-dim);
            font-size: 1.2rem;
        }

        .container {
            max-width: 900px;
            margin: -40px auto 60px;
            padding: 0 20px;
        }

        .casino-card {
            background-color: var(--bg-card);
            border-radius: 20px;
            display: flex;
            align-items: center;
            padding: 40px;
            border: 1px solid rgba(255, 255, 255, 0.05);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4);
            transition: all 0.3s ease;
        }

        .casino-card:hover {
            border-color: var(--accent-cyan);
            box-shadow: 0 0 20px rgba(0, 242, 255, 0.1);
            transform: translateY(-5px);
        }

        .brand-logo {
            flex: 0 0 180px;
        }

        .brand-logo img {
            max-width: 100%;
            filter: drop-shadow(0 0 5px rgba(255,255,255,0.1));
        }

        .brand-info {
            flex: 1;
            padding: 0 40px;
        }

        .brand-info h2 {
            font-family: 'Montserrat', sans-serif;
            font-size: 24px;
            margin: 0 0 5px;
        }

        .bonus-highlight {
            font-size: 1.5rem;
            font-weight: 800;
            color: #fff;
            margin: 10px 0;
        }

        .tag {
            display: inline-block;
            background: rgba(0, 242, 255, 0.1);
            color: var(--accent-cyan);
            padding: 4px 12px;
            border-radius: 5px;
            font-size: 0.8rem;
            font-weight: 700;
            text-transform: uppercase;
        }

        .cta-section {
            flex: 0 0 180px;
        }

        .play-btn {
            display: block;
            background: var(--accent-cyan);
            color: #000;
            text-decoration: none;
            padding: 16px 20px;
            border-radius: 12px;
            font-weight: 800;
            text-align: center;
            text-transform: uppercase;
            transition: all 0.3s;
            box-shadow: 0 0 15px rgba(0, 242, 255, 0.2);
        }

        .play-btn:hover {
            background: #fff;
            box-shadow: 0 0 25px rgba(0, 242, 255, 0.4);
            transform: scale(1.03);
        }

        .footer {
            text-align: center;
            padding: 80px 20px;
            border-top: 1px solid rgba(255,255,255,0.05);
        }

        .footer h3 {
            font-family: 'Montserrat', sans-serif;
            color: var(--text-main);
            margin-bottom: 15px;
        }

        .footer p {
            color: var(--text-dim);
            max-width: 600px;
            margin: 0 auto;
            font-size: 0.85rem;
        }

        @media (max-width: 768px) {
            .casino-card {
                flex-direction: column;
                text-align: center;
                padding: 30px;
            }
            .brand-info {
                padding: 20px 0;
            }
            .hero h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>

<header>
    <div class="logo-text">Exclusive Offers</div>
</header>

<section class="hero">
    <h1>Premier Gaming 2026</h1>
    <p>Secure access to the most lucrative verified offers in the industry.</p>
</section>

<div class="container">
    <div class="casino-card">
        <div class="brand-logo">
            <img src="https://i.imgur.com/bDTbw0X.png" alt="Spinlynx">
        </div>
        <div class="brand-info">
            <span class="tag">Editor's Choice</span>
            <h2>Spinlynx</h2>
            <div class="bonus-highlight">400% Match up to €2,000</div>
            <p style="color: var(--text-dim); margin: 0;">+ 200 Exclusive Free Spins</p>
        </div>
        <div class="cta-section">
            <a href="https://go.newsspinlynx.com/visit/?bta=35240&brand=spinlynx" class="play-btn">Claim Now</a>
        </div>
    </div>
</div>

<footer class="footer">
    <h3>Professional Excellence</h3>
    <p>Our verification process ensures that every partner brand adheres to the highest standards of player safety and transaction transparency.</p>
    <p style="margin-top: 30px;">© 2026 Exclusive Offers | Verified Rewards Portal</p>
</footer>

</body>
</html>
