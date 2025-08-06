<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WebKuu</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&family=Roboto&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(-45deg, #74ebd5, #ACB6E5, #74ebd5, #ACB6E5);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
            color: #fff;
            padding: 20px;
        }

        h1 {
            font-family: 'Orbitron', sans-serif;
            font-size: 3rem;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.4);
            margin-bottom: 20px;
            animation: fadeInDown 1s ease-out;
        }

        p {
            font-size: 1.2rem;
            max-width: 600px;
            line-height: 1.6;
            text-shadow: 1px 1px 4px rgba(0,0,0,0.2);
            animation: fadeInUp 1.2s ease-out;
            margin-bottom: 30px;
        }

        a.button {
            text-decoration: none;
            padding: 12px 25px;
            background: #ffffff;
            color: #333;
            font-weight: bold;
            border-radius: 30px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            transition: all 0.3s ease;
        }

        a.button:hover {
            background: #333;
            color: #fff;
        }

        @keyframes fadeInDown {
            from { opacity: 0; transform: translateY(-30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }

            p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <h1>SELAMAT DATANG DI WEBKUU</h1>
    <p>Belajar membuat web itu menyenangkan, apalagi kalau tampilannya keren dan bisa dibuka di mana saja!</p>
    <a href="https://www.example.com" class="button">Kunjungi Sekarang</a>
</body>
</html>
