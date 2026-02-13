<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hasib026 - Coming Soon</title>
    <style>
        :root {
            --primary: #ff0000;
            --dark: #0f0f0f;
            --text: #ffffff;
            --gray: #aaaaaa;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--dark);
            color: var(--text);
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        /* Container */
        .container {
            padding: 20px;
            max-width: 600px;
        }

        /* Logo / Icon */
        .logo-icon {
            font-size: 80px;
            margin-bottom: 20px;
            display: inline-block;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.1); opacity: 0.8; }
            100% { transform: scale(1); opacity: 1; }
        }

        /* Main Text */
        h1 {
            font-size: 3.5rem;
            margin: 0;
            background: linear-gradient(to right, #fff, #888);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        p {
            font-size: 1.2rem;
            color: var(--gray);
            margin: 20px 0 40px 0;
            line-height: 1.6;
        }

        /* Buttons */
        .btn-group {
            display: flex;
            gap: 15px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .btn {
            padding: 15px 35px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .btn-primary {
            background-color: var(--primary);
            color: white;
            box-shadow: 0 4px 15px rgba(255, 0, 0, 0.3);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(255, 0, 0, 0.5);
        }

        .btn-secondary {
            background-color: #333;
            color: white;
            border: 1px solid #444;
        }

        .btn-secondary:hover {
            background-color: #444;
        }

        /* Footer */
        footer {
            position: absolute;
            bottom: 20px;
            font-size: 0.9rem;
            color: #555;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="logo-icon">▶️</div>
        
        <h1>Hasib026</h1>
        
        <p>
            Something amazing is in the works.<br>
            I am getting ready to launch my new channel.<br>
            <strong>Subscribe now so you don't miss the first upload!</strong>
        </p>

        <div class="btn-group">
            <a href="https://youtube.com/@hasib026?si=xolBvgU6OIbyUAUh" target="_blank" class="btn btn-primary">
                Subscribe on YouTube
            </a>
            </div>
    </div>

    <footer>
        &copy; 2026 Hasib026. Launching Soon.
    </footer>

</body>
</html>
