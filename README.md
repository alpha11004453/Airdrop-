# Airdrop-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybernetic Links</title>
    <style>
        /* Background and Font Styling */
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            color: #fff;
            background: linear-gradient(135deg, #1e0038, #4a007a, #120048);
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }
        
        /* Container Styling */
        .container {
            text-align: center;
            max-width: 600px;
            animation: fadeIn 1s ease-in-out;
        }
        
        /* Title Styling */
        h1 {
            font-size: 3em;
            color: #00ffbf;
            text-shadow: 0 0 15px #00ffbf, 0 0 30px #00ffbf;
            margin-bottom: 30px;
            letter-spacing: 2px;
        }

        /* Button Container Styling */
        .button-container {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        /* Button Styling */
        .cyber-button {
            text-decoration: none;
            color: #00e5ff;
            font-size: 1.2em;
            font-weight: bold;
            padding: 15px 20px;
            border: 2px solid #00e5ff;
            border-radius: 15px;
            background: transparent;
            transition: all 0.3s ease-in-out;
            position: relative;
            overflow: hidden;
            display: inline-block;
            box-shadow: 0 0 10px rgba(0, 229, 255, 0.3), 0 0 20px rgba(0, 229, 255, 0.5);
        }

        /* Button Hover Effects */
        .cyber-button:hover {
            background: #00e5ff;
            color: #111;
            box-shadow: 0 0 15px #00e5ff, 0 0 30px #00e5ff, 0 0 45px #00e5ff;
            border-color: #00ffbf;
        }

        /* Glowing Border Effect */
        .cyber-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(0, 229, 255, 0.3), transparent);
            transition: 0.7s;
        }

        /* Sliding Effect */
        .cyber-button:hover::before {
            left: 100%;
        }

        /* Additional Button Glow Animation */
        .cyber-button::after {
            content: '';
            position: absolute;
            top: -2px;
            left: -2px;
            right: -2px;
            bottom: -2px;
            background: linear-gradient(45deg, transparent, #00e5ff, transparent);
            z-index: -1;
            opacity: 0;
            transition: opacity 0.3s;
            border-radius: 15px;
        }

        .cyber-button:hover::after {
            opacity: 1;
        }

        /* Keyframe Animations */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Abdulwehab Jemal</h1>
        <div class="button-container">
            <a href="https://testnet.humanity.org/login?ref=dune2" class="cyber-button">Humanity Login</a>
            <a href="https://app.gradient.network/signup?code=NUKI0P" class="cyber-button">Gradient Network Signup</a>
            <a href="https://t.me/Tomarket_ai_bot/app?startapp=0002t8Ek" class="cyber-button">ToMarket Bot</a>
            <a href="https://app.nodepay.ai/register?ref=IPbXxRdYeghzDhT" class="cyber-button">NodePay Register</a>
            <a href="https://t.me/catsgang_bot/join?startapp=go_yFPGC86IeQg860ZagK" class="cyber-button">CatsGang Bot</a>
            <a href="https://t.me/major/start?startapp=5834702018" class="cyber-button">Major Bot</a>
            <a href="https://t.me/blum/app?startapp=ref_6ej9GBnCUP" class="cyber-button">Blum App</a>
            <a href="https://t.me/seed_coin_bot/app?startapp=5834702018" class="cyber-button">Seed Coin Bot</a>
        </div>
    </div>
</body>
</html>