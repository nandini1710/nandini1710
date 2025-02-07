<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MysticMiles - Explore Hidden Travel Gems</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Raleway:wght@300&display=swap');
        
        body {
            font-family: 'Raleway', sans-serif;
            background: url('https://source.unsplash.com/1600x900/?mountains,adventure') no-repeat center center/cover;
            text-align: center;
            padding: 20px;
            color: white;
            overflow-x: hidden;
            animation: fadeIn 2s ease-in;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        .container {
            max-width: 750px;
            margin: 50px auto;
            padding: 40px;
            background: rgba(0, 0, 0, 0.75);
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(255, 215, 0, 0.5);
            transform: scale(1);
            transition: transform 0.3s;
        }
        
        .container:hover {
            transform: scale(1.02);
        }
        
        h1 {
            font-family: 'Montserrat', sans-serif;
            color: #ffcc00;
            font-size: 40px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        
        p {
            font-size: 22px;
            margin-bottom: 15px;
        }
        
        .cta-button {
            display: inline-block;
            padding: 15px 30px;
            background: #ffcc00;
            color: black;
            text-decoration: none;
            font-size: 22px;
            border-radius: 8px;
            font-weight: bold;
            transition: background 0.3s, transform 0.2s;
        }
        
        .cta-button:hover {
            background: #ffaa00;
            transform: scale(1.05);
        }
        
        .email-form input {
            padding: 15px;
            font-size: 18px;
            width: 80%;
            margin-top: 15px;
            border-radius: 5px;
            border: none;
            text-align: center;
        }
        
        .email-form button {
            padding: 15px;
            font-size: 18px;
            background: #ffcc00;
            color: black;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }
        
        .email-form button:hover {
            background: #ffaa00;
        }
        
        .hero-image {
            width: 100%;
            border-radius: 15px;
            margin-bottom: 20px;
            box-shadow: 0 0 15px rgba(255, 215, 0, 0.5);
        }
        
        .icon-bar {
            margin-top: 20px;
        }
        
        .icon-bar img {
            width: 50px;
            margin: 10px;
            transition: transform 0.3s;
        }
        
        .icon-bar img:hover {
            transform: scale(1.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://source.unsplash.com/750x400/?hiking,exploration" alt="Travel Adventure" class="hero-image">
        <h1>Welcome to MysticMiles</h1>
        <p>Embark on the ultimate journey, discover the world's hidden treasures, and share your wildest adventures.</p>
        <a href="#" class="cta-button">Follow Us on Social Media</a>
        <p>Be the first to explore uncharted destinations!</p>
        <form class="email-form">
            <input type="email" placeholder="Enter your email" required>
            <button type="submit">Join the Adventure</button>
        </form>
        <div class="icon-bar">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Facebook_Logo_2023.png" alt="Facebook">
            <img src="https://upload.wikimedia.org/wikipedia/en/6/60/Twitter_Logo_as_of_2021.svg" alt="Twitter">
        </div>
    </div>
</body>
</html>
