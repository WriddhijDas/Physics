<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wriddhij | Astrophysics</title>
    <style>
        /* This section controls how the site looks */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: radial-gradient(ellipse at bottom, #1b2735 0%, #090a0f 100%);
            color: #ffffff;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            overflow: hidden;
        }

        /* Creating simple stars using CSS shadows */
        .stars {
            width: 1px;
            height: 1px;
            background: transparent;
            box-shadow: 1744px 122px #FFF , 134px 1321px #FFF , 32px 1456px #FFF, 893px 982px #FFF;
            animation: animStar 50s linear infinite;
        }

        .container {
            position: absolute;
            z-index: 10;
            max-width: 600px;
            padding: 40px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            backdrop-filter: blur(5px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            box-shadow: 0 0 20px rgba(0,0,0,0.5);
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            background: -webkit-linear-gradient(#eee, #333);
            text-shadow: 0 0 10px #00d4ff;
        }

        p {
            font-size: 1.2rem;
            line-height: 1.6;
            color: #d1d1d1;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            padding: 15px 30px;
            background-color: #ff0000; /* YouTube Red */
            color: white;
            text-decoration: none;
            font-weight: bold;
            border-radius: 50px;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .btn:hover {
            transform: scale(1.05);
            box-shadow: 0 0 15px #ff4d4d;
        }

        .footer {
            margin-top: 20px;
            font-size: 0.8rem;
            opacity: 0.6;
        }

    </style>
</head>
<body>

    <div class="stars"></div>

    <div class="container">
        <h1>Astrophysics & Beyond</h1>
        
        <p>
            Hello! I am a person who loves <strong>astrophysics</strong> and all the branches that connect to it. 
            <br><br>
            I explore the mysteries of the universe, from black holes to quantum mechanics.
            Thanks for seeing this account!
        </p>

        <a href="https://youtube.com/@wriddhijdas?si=QPpshZp32gqVNCdO" target="_blank" class="btn">
            ▶ Find me on YouTube
        </a>

        <div class="footer">
            &copy; 2026 Wriddhij
        </div>
    </div>

</body>
</html>
