<!DOCTYPE html>
<html lang="az">
<head>
    <meta charset="UTF-8">
    <meta name="Pathways Beylaqan" content="Pathways Beylaqan,pathways peylagan">
    <title>Pathways Beylaqan</title>
    <meta name="Pathways beylaqan" content="Pathways Beylaqan - U.S. Embassy-in dəstəklədiyi ingilis dili proqramı.">
    <meta name="keywords" content="Pathways, Beylaqan, ingilis dili, proqram, ABŞ">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
            animation: fadeIn 1s;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4CAF50;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #2e7d32;
        }
        main {
            margin: 20px;
            padding: 20px;
            background-color: white;
            border-radius: 5px;
            animation: slideIn 1s;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
            animation: fadeIn 1s;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 15px;
            margin: 10px 0;
            transition: transform 0.3s;
        }
        .card:hover {
            transform: scale(1.02);
        }
        img {
            width: 50vw;
            border-radius: 5px;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateY(-20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @media (max-width: 600px) {
            nav a {
                display: block;
                margin: 10px 0;
            }
            main {
                margin: 10px;
                padding: 10px;
            }
        }
    </style>
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const cards = document.querySelectorAll('.card');
            cards.forEach(card => {
                card.addEventListener('click', () => {
                    alert('Bu kartani bosdingiz!');
                });
            });
        });
    </script>
</head>
<body>

<header>
    <img src="athway BEylagan.png" alt="bg">
    <h1>Pathways Beylaqan</h1>
</header>

<nav>
    <!-- İstədiyiniz linkləri burada əlavə edə bilərsiniz -->
</nav>

<main>
    <section id="home">
        <h2>Pathways</h2>
        <p><strong>Pathways-</strong> is a program supported by the U.S. Department of 
            State and the U.S. Embassy to Azerbaijan that offers 
            English language training to students in 8th and 9th
             grade through classes and activities outside of regular
              school hours. By participating in Pathways, students 
              can develop their English language abilities, as well
               as leadership and professional skills. The program
                also exposes students to aspects of U.S. culture and 
                creates pathways to study in the United States by 
                enhancing their educational prospects.</p>
    </section>

    <section id="about" class="card">
        <h2>Pathways Beylaqan aktivitləri</h2>
        <img src="WhatsApp Şəkil 2024-09-22 saat 12.41.30_25e8f70e.jpg" alt="bg">
    </section>

    <section id="contact" class="card">
        <h2>Representtation</h2>
        <img src="WhatsApp Şəkil 2024-09-13 saat 22.10.33_6bc4d34c.jpg" alt="bg">
        <p>Teacher :</p>  
        <p>Gulnar Jafarli</p>
        <p>Gulnara Mammadova</p>
        <p>Students :</p>
        <p><strong>Huseyn</strong>, AYSU, ASMAR, AYDAN, GULCAN, SAMED, ELTUN, NAZRIN, YAGMUR, ALLAHVERDI, TAMELLA, TEYMUR, INSHALLAH, RASUL</p>
    </section>
</main>

<footer>

</footer>

</body>
</html>

