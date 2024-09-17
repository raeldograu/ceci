<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            background-color: rgb(0, 0, 0);
            color: aliceblue;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        h1 {
            color: blueviolet;
            font-size: 30px;
            text-align: center;
            margin-top: 20px;
        }

        .container {
            display: flex;
            justify-content: center;
            gap: 20px; /* Space between images */
            margin-top: 20px;
        }

        .image-item {
            text-align: center;
        }

        .ft1{
            height: 150px;
            display: block;
            margin: 0 auto;
        }

        
        .ft2{
            height: 150px;
            display: block;
            margin: 0 auto;
        }

        button {
            background-color: rgb(226, 43, 211);
            border-radius: 20px;
            border: 7px solid rgb(66, 21, 215);
            color: white;
            font-size: 16px;
            padding: 10px 20px;
            cursor: pointer;
            margin-top: 10px;
            display: inline-block;
        }

        button:hover {
            background-color: rgb(200, 30, 190);
        }

        section {
            margin-top: 20px;
            text-align: center;
        }

        p {
            color: aliceblue;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <h1>𝒞𝓁𝒾𝒸𝓀 𝓈𝑒 𝓋𝑜𝒸𝑒 𝑔𝑜𝓈𝓉𝑜𝓊 😘</h1>

    <div class="container">
        <div class="image-item">
            <img src="WhatsApp Image 2024-09-17 at 11.50.32.jpeg" class="ft1">
            <br>
            <button onclick="a1()">❤️ 𝔓𝔯𝔦𝔪𝔢𝔦𝔯𝔞 𝔉𝔬𝔱𝔬 ❤️</button>
        </div>

        <div class="image-item">
            <img src="WhatsApp Image 2024-09-17 at 11.52.17.jpeg" class="ft2">
            <br>
            <button onclick="a2()">❤️ รєgยภ๔ค Ŧ๏т๏ ❤️</button>
        </div>
    </div>

    <section id="s1"><p>𝔓𝔯𝔦𝔪𝔢𝔦𝔯𝔞 𝔉𝔬𝔱𝔬</p></section>
    <section id="s2"><p>รєgยภ๔ค Ŧ๏т๏</p></section>

    <script>
        let contador1 = 0;
        let contador2 = 0;

        const vot1 = document.querySelector('section#s1');
        const vot2 = document.querySelector('section#s2');

        function a1() {
            contador1++;
            vot1.innerHTML = `<p>𝔓𝔯𝔦𝔪𝔢𝔦𝔯𝔞 𝔉𝔬𝔱𝔬, <mark>${contador1}</mark>pɛรรѳɑร gѳรtɑʀɑɱ ɗɑ Բѳtѳ!!!</p>`;
        }

        function a2() {
            contador2++;
            vot2.innerHTML = `<p>รєgยภ๔ค Ŧ๏т๏, <mark>${contador2}</mark>pɛรรѳɑร gѳรtɑʀɑɱ ɗɑ Բѳtѳ!!!!</p>`;
        }
    </script>
</body>
</html>
