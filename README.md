<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Love ❤️</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Times New Roman', sans-serif;
        }
        body {
            min-height: 100vh;
            background: linear-gradient(135deg, #ffdde1, #ee9ca7);
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        .card {
            background: white;
            max-width: 600px;
            width: 100%;
            padding: 40px 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        .card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 8px;
            background: linear-gradient(90deg, #ff4d6d, #ff758f);
        }
        h1 {
            color: #d6336c;
            font-size: 28px;
            margin-bottom: 20px;
        }
        .heart {
            color: #ff4d6d;
            font-size: 40px;
            margin: 15px 0;
            animation: beat 1.2s infinite alternate;
        }
        @keyframes beat {
            from {transform: scale(1);}
            to {transform: scale(1.2);}
        }
        p {
            color: #444;
            font-size: 17px;
            line-height: 1.8;
            margin-bottom: 15px;
            text-align: justify;
            text-align-last: center;
        }
        .signature {
            margin-top: 30px;
            color: #d6336c;
            font-weight: bold;
            font-size: 18px;
        }
        .date {
            margin-top: 10px;
            font-size: 14px;
            color: #888;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>To My Dearest Love ❤️</h1>
        <div class="heart">❤️</div>

        <p>
            With every day that passes, my heart grows fuller with joy and gratitude that you are the one God gave to me. 
            I want to tell you that my love for you isn’t just for today — it is for every moment, every second, 
            and for all the days and years yet to come.
        </p>
        <p>
            Thank you for being the light that brightens my world. Thank you for your care, your patience, your understanding, 
            and every little and big sacrifice you’ve made just for us. You are my strength when I am weary, and my joy when I feel down. 
            No words can fully describe how deeply thankful I am that you became part of my life — you made everything more beautiful and meaningful.
        </p>
        <p>
            I promise to keep loving you more and more, to extend my love beyond just words, 
            and to show it through every action and every step we take together. 
            Through all the happy times and the challenges we may face, 
            I will always hold on to you, choose you, and stay right by your side.
        </p>
        <p>
            You are my present, and you are my future. 
            I will love you more than I can ever express, and I will love you for all eternity.
        </p>

        <div class="signature">
            With all my love,<br>
            Emeliza<br><br>
            Madly in love with you; Yamz
        </div>
        <div class="date" id="date"></div>
    </div>

    <script>
        const today = new Date();
        document.getElementById('date').textContent = today.toLocaleDateString('en-US', {year:'numeric', month:'long', day:'numeric'});
    </script>
</body>
</html>
