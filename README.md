<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Заклад вищої освіти</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Заклад вищої освіти</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Головна</a></li>
                <li><a href="#about">Про нас</a></li>
                <li><a href="#faculties">Факультети та кафедри</a></li>
                <li><a href="#schedule">Розклад</a></li>
                <li><a href="#materials">Навчальні матеріали</a></li>
                <li><a href="#student-life">Студентське життя</a></li>
                <li><a href="#contacts">Контакти</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Головна сторінка</h2>
            <p>Ласкаво просимо до нашого закладу вищої освіти!</p>
            <div class="news">
                <h3>Новини та оголошення</h3>
                <ul>
                    <li>Новина 1</li>
                    <li>Новина 2</li>
                    <li>Оголошення 1</li>
                </ul>
            </div>
        </section>

        <section id="about">
            <h2>Про нас</h2>
            <p>Інформація про заклад, його історію, місію та керівництво.</p>
        </section>

        <section id="faculties">
            <h2>Факультети та кафедри</h2>
            <p>Інформація про факультети та кафедри, їх спеціальності та викладацький склад.</p>
        </section>

        <section id="schedule">
            <h2>Розклад</h2>
            <p>Інтерактивний розклад занять та екзаменів.</p>
        </section>

        <section id="materials">
            <h2>Навчальні матеріали</h2>
            <p>Лекції, презентації, методичні матеріали та електронна бібліотека.</p>
        </section>

        <section id="student-life">
            <h2>Студентське життя</h2>
            <p>Інформація про гуртки, заходи та студентські організації.</p>
        </section>

        <section id="contacts">
            <h2>Контакти</h2>
            <p>Адреса закладу, контактна інформація, форма зворотного зв'язку.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Заклад вищої освіти. Всі права захищені.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #003366;
    color: white;
    padding: 1em;
}

header .logo {
    display: flex;
    justify-content: center;
    align-items: center;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style-type: none;
    padding: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 40px;
}

section h2 {
    border-bottom: 2px solid #003366;
    padding-bottom: 10px;
}

footer {
    background-color: #003366;
    color: white;
    text-align: center;
    padding: 1em;
    position: fixed;
    bottom: 0;
    width: 100%;
}
