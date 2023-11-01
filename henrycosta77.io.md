<!DOCTYPE html>
<html>
<head>
    <title>Redes Sociais</title>
    <style>
        body {
            background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT201sNpWAZE17aBWiSkWk03SJLKYeJ5kjACw&usqp=CAU');
            background-size: cover;
            background-repeat: no-repeat;
            text-align: center;
            font-family: Arial, sans-serif;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 18px;
            background: linear-gradient(to right, #ff2670, #00a8ff);
            border: none;
            color: white;
            border-radius: 5px;
            margin: 10px;
            cursor: pointer;
            animation: neon 1.5s infinite;
        }

        .button:hover {
            animation: none;
        }

        @keyframes neon {
            0%, 100% {
                filter: brightness(150%);
                text-shadow: 0 0 10px #ff2670, 0 0 20px #00a8ff, 0 0 30px #ff2670;
            }
            50% {
                filter: brightness(120%);
                text-shadow: 0 0 5px #ff2670, 0 0 10px #00a8ff, 0 0 15px #ff2670;
            }
        }
    </style>
</head>
<body>
    <a href="https://instagram.com/madnessteaa?igshid=OGQ5ZDc2ODk2ZA==" target="_blank">
        <button class="button">Instagram</button>
    </a>
    <a href="https://www.twitch.tv/madnesstea?sr=a" target="_blank">
        <button class "button">Twitch</button>
    </a>
    <a href="https://youtube.com/@madnesstea?si=s5keuXGzZvFMO1p2" target="_blank">
        <button class="button">YouTube</button>
    </a>
    <a href="https://discord.com/invite/T7UVz4vJ" target="_blank">
        <button class="button">Discord</button>
    </a>
</body>
</html>
