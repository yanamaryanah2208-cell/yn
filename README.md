<!DOCTYPE html>
<html>
<head>
    <title>Happy Birthday! 🎂</title>
    <style>
        body {
            background-color: #fdfaf6;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            font-family: 'Courier New', Courier, monospace;
            color: #555;
            text-align: center;
        }
        .container { padding: 20px; transition: all 0.5s ease; }
        h1 { font-size: 1.5rem; margin-bottom: 20px; }
        .btn {
            background: white;
            border: 1px solid #ddd;
            padding: 10px 20px;
            border-radius: 20px;
            cursor: pointer;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            font-family: inherit;
        }
        .hidden { display: none; }
        .heart { color: #e74c3c; font-size: 2rem; margin-top: 20px; }
    </style>
</head>
<body>

    <div id="p1" class="container">
        <h1>happy birthday my bestofrendo!! ✨</h1>
        <p>hissashinee mugiwara... klik yeah</p>
        <button class="btn" onclick="next(1)">buka ‹𝟹</button>
    </div>

    <div id="p2" class="container hidden">
        <h1>tunggu dulu... 🫧</h1>
        <p>happy birthday grid</p>
        <button class="btn" onclick="next(2)">lanjut ‹𝟹</button>
    </div>

    <div id="p3" class="container hidden">
        <h1>jadi gini...</h1>
        <p>makasih ya .</p>
        <p>udah jadi mai prend</p>
        <p>May your special day be filled with lots of laughter and joy! </p>
        <div class="heart">૮꒰ ˶• ༝ •˶꒱ა</div>
    </div>

    <script>
        function next(current) {
            document.getElementById('p' + current).classList.add('hidden');
            document.getElementById('p' + (current + 1)).classList.remove('hidden');
        }
    </script>
</body>
</html>
