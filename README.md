
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Untuk Naya ❤️</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            height: 100vh;
            width: 100vw;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #000;
        }

        .background-container {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url('https://files.catbox.moe/vxmarw.jpg');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            filter: blur(4px) brightness(0.6);
            z-index: 1;
        }

        .card {
            position: relative;
            z-index: 2;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 24px;
            padding: 30px 20px;
            width: 90%;
            max-width: 500px;
            text-align: center;
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.5);
            animation: fadeIn 2s ease-in-out;
            margin: 20px;
        }

        h1 {
            font-size: 2rem;
            color: #ffb3c6;
            margin-bottom: 15px;
            text-shadow: 0 0 10px rgba(255, 179, 198, 0.5);
            font-family: 'Dancing Script', cursive, sans-serif;
        }

        p {
            font-size: 1rem;
            color: #ffffff;
            line-height: 1.6;
            margin-bottom: 15px;
            text-shadow: 0 1px 3px rgba(0,0,0,0.8);
        }

        .highlight {
            color: #ffccd5;
            font-weight: bold;
        }

        .heart {
            font-size: 2rem;
            color: #ff4d6d;
            animation: beat 1s infinite;
            display: inline-block;
            margin-top: 10px;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes beat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.2); }
        }

        /* Responsif buat HP layar kecil */
        @media (max-width: 480px) {
            h1 { font-size: 1.6rem; }
            p { font-size: 0.9rem; }
            .card { padding: 25px 15px; }
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>

    <div class="background-container"></div>

    <div class="card">
        <h1>Naya, Sayang...</h1>
        <p>Hai Naya. Putra minta maaf ya. Kalau ada salah kata atau sikap yang bikin kamu sedih, Putra bener-bener nggak bermaksud.</p>
        <p>Putra cuma pengen kamu tau, <span class="highlight">perasaan Putra ke kamu itu tulus</span>. Nggak ada niat buat nyakitin atau bikin kamu kecewa.</p>
        <p>Semoga kamu bisa maafin Putra. Putra bakal berusaha jadi yang lebih baik lagi buat kamu.</p>
        <div class="heart">❤️</div>
    </div>

</body>
</html>
