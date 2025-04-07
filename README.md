<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PUBG | Боевая зона</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #1a1a1a;
            color: #e0e0e0;
            margin: 0;
            padding: 0;
            background-image: url('https://i.imgur.com/XYZ1234.jpg'); /* Замените на реальный фон PUBG */
            background-size: cover;
            background-attachment: fixed;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(255, 100, 0, 0.3);
        }
        
        header {
            text-align: center;
            padding: 20px 0;
            border-bottom: 2px solid #ff6600;
        }
        
        h1 {
            color: #ff6600;
            text-shadow: 2px 2px 4px #000;
            font-size: 3em;
            margin: 0;
        }
        
        h2 {
            color: #ff9933;
            border-left: 4px solid #ff6600;
            padding-left: 10px;
        }
        
        .nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }
        
        .nav a {
            color: #ff9933;
            text-decoration: none;
            font-weight: bold;
            padding: 10px 20px;
            border: 1px solid #ff6600;
            border-radius: 5px;
            transition: all 0.3s;
        }
        
        .nav a:hover {
            background-color: #ff6600;
            color: #000;
        }
        
        .content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            margin-top: 30px;
        }
        
        .card {
            background-color: rgba(30, 30, 30, 0.8);
            padding: 20px;
            border-radius: 8px;
            border: 1px solid #333;
            transition: transform 0.3s;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(255, 100, 0, 0.4);
        }
        
        .card h3 {
            color: #ff9933;
            margin-top: 0;
        }
        
        .card p {
            line-height: 1.6;
        }
        
        .btn {
            display: inline-block;
            background-color: #ff6600;
            color: #000;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 10px;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: #ff9933;
        }
        
        footer {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            border-top: 1px solid #333;
            color: #999;
        }
        
        .highlight {
            color: #ff6600;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>PLAYERUNKNOWN'S BATTLEGROUNDS</h1>
            <p>Выживи в эпической битве на 100 игроков!</p>
            
            <div class="nav">
                <a href="#about">Об игре</a>
                <a href="#maps">Карты</a>
                <a href="#weapons">Оружие</a>
                <a href="#tips">Советы</a>
                <a href="#download">Скачать</a>
            </div>
        </header>
        
        <div class="content">
            <div class="card" id="about">
                <h3>ОБ ИГРЕ</h3>
                <p><span class="highlight">PUBG</span> — это королевская битва, где 100 игроков сражаются за звание последнего выжившего. Десантируйтесь на огромную карту, ищите оружие и снаряжение, следите за зоной и побеждайте!</p>
                <p>Игра сочетает напряженный экшен, тактическое планирование и элементы выживания. Каждая партия уникальна благодаря случайным зонам, разбросанному луту и непредсказуемым противникам.</p>
                <a href="https://www.pubg.com" class="btn" target="_blank">Официальный сайт</a>
            </div>
            
            <div class="card" id="maps">
                <h3>КАРТЫ</h3>
                <p>В PUBG доступны несколько уникальных карт, каждая со своей атмосферой и тактиками:</p>
                <ul>
                    <li><a href="#erangel" style="color: #ff9933;">Эрангель</a> — классическая карта с военной тематикой</li>
                    <li><a href="#miramar" style="color: #ff9933;">Мирамар</a> — пустынный ландшафт с городами-призраками</li>
                    <li><a href="#sanhok" style="color: #ff9933;">Санок</a> — компактная джунглевая карта</li>
                    <li><a href="#vikendi" style="color: #ff9933;">Викенди</a> — заснеженный регион с уникальной динамикой</li>
                </ul>
                <a href="https://pubg.fandom.com/wiki/Maps" class="btn" target="_blank">Все карты</a>
            </div>
            
            <div class="card" id="weapons">
                <h3>ОРУЖИЕ И СНАРЯЖЕНИЕ</h3>
                <p>В PUBG огромный арсенал оружия — от пистолетов до снайперских винтовок. Каждое оружие имеет уникальные характеристики:</p>
                <p><span class="highlight">AR</span> (штурмовые винтовки) — универсальное оружие для всех дистанций<br>
                <span class="highlight">DMR</span> — точные полуавтоматические винтовки<br>
                <span class="highlight">SR</span> — мощные снайперские винтовки<br>
                <span class="highlight">SMG</span> — компактное оружие для ближнего боя</p>
                <a href="https://pubg.fandom.com/wiki/Weapons" class="btn" target="_blank">Полный список</a>
            </div>
            
            <div class="card" id="tips">
                <h3>СОВЕТЫ НОВИЧКАМ</h3>
                <p>1. <span class="highlight">Выбирайте место посадки</span> — избегайте горячих точек в начале</p>
                <p>2. <span class="highlight">Слушайте звуки</span> — шаги и выстрелы помогут обнаружить врага</p>
                <p>3. <span class="highlight">Используйте укрытия</span> — не бегите по открытой местности</p>
                <p>4. <span class="highlight">Следите за зоной</span> — не попадитесь вне безопасной зоны</p>
                <p>5. <span class="highlight">Тренируйтесь</span> — используйте тренировочный режим для оттачивания навыков</p>
                <a href="https://www.youtube.com/results?search_query=pubg+guides" class="btn" target="_blank">Видео-гайды</a>
            </div>
        </div>
        
        <div style="margin-top: 40px; text-align: center;" id="download">
            <h2>ГОТОВ К БИТВЕ?</h2>
            <p>Присоединяйся к миллионам игроков по всему миру!</p>
            <a href="https://store.steampowered.com/app/578080/PUBG_BATTLEGROUNDS/" class="btn" style="padding: 15px 30px; font-size: 1.2em;" target="_blank">Играть бесплатно</a>
        </div>
        
        <footer>
            <p>© 2023 PLAYERUNKNOWN'S BATTLEGROUNDS. Все права защищены.</p>
            <p>Этот сайт не является официальным и создан фанатами игры.</p>
        </footer>
    </div>
</body>
</html>
