<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мода UA - Інтернет-магазин одягу</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Мода UA</h1>
            <nav>
                <ul>
                    <li><a href="#">Головна</a></li>
                    <li><a href="#about">Про нас</a></li>
                    <li><a href="#catalog">Каталог</a></li>
                    <li><a href="#contact">Контакти</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="container">
            <h2>Стильний одяг для кожного</h2>
            <p>Обирайте з широкого асортименту найкращих колекцій.</p>
            <a href="#catalog" class="btn">Переглянути каталог</a>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>Про нас</h2>
            <p>Ми пропонуємо якісний одяг для жінок, чоловіків та дітей. Наші колекції створені, щоб підкреслити ваш стиль та комфорт.</p>
        </div>
    </section>

    <section id="catalog">
        <div class="container">
            <h2>Каталог</h2>
            <div class="product-list">
                <div class="product">
                    <img src="img/product1.jpg" alt="Продукт 1">
                    <h3>Футболка жіноча</h3>
                    <p>Ціна: 500 грн</p>
                </div>
                <div class="product">
                    <img src="img/product2.jpg" alt="Продукт 2">
                    <h3>Куртка чоловіча</h3>
                    <p>Ціна: 1500 грн</p>
                </div>
                <div class="product">
                    <img src="img/product3.jpg" alt="Продукт 3">
                    <h3>Дитячий светр</h3>
                    <p>Ціна: 700 грн</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Контакти</h2>
            <p>Телефон: +380 12 345 67 89</p>
            <p>Email: info@modaua.com</p>
            <form action="#">
                <input type="text" placeholder="Ваше ім'я" required>
                <input type="email" placeholder="Ваш Email" required>
                <textarea placeholder="Ваше повідомлення" required></textarea>
                <button type="submit">Відправити</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Мода UA. Всі права захищені.</p>
        </div>
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
    background-color: #333;
    color: #fff;
    padding: 10px 0;
}
.container {
    width: 80%;
    margin: 0 auto;
}
nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    gap: 20px;
}
nav ul li a {
    color: #fff;
    text-decoration: none;
}
.btn {
    background-color: #007bff;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}
