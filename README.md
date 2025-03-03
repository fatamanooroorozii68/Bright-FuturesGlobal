<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>وب‌سایت کمک به بچه‌ها</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>به وب‌سایت کمک به بچه‌ها خوش آمدید</h1>
        <nav>
            <ul>
                <li><a href="#about">درباره ما</a></li>
                <li><a href="#donate">کمک کنید</a></li>
                <li><a href="#contact">تماس با ما</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>درباره ما</h2>
        <p>ما یه سازمان غیرانتفاعی هستیم که به بچه‌های نیازمند کمک می‌کنیم.</p>
    </section>

    <section id="donate">
        <h2>کمک کنید</h2>
        <p>با کمک‌های کوچیکتون، می‌تونین دنیا رو جای بهتری کنین.</p>
        <button>همین حالا کمک کن</button>
    </section>

    <section id="contact">
        <h2>تماس با ما</h2>
        <form>
            <label for="name">نام:</label>
            <input type="text" id="name" name="name">
            <label for="email">ایمیل:</label>
            <input type="email" id="email" name="email">
            <label for="message">پیام:</label>
            <textarea id="message" name="message"></textarea>
            <button type="submit">ارسال</button>
        </form>
    </section>

    <footer>
        <p>تمامی حقوق محفوظ است.</p>
    </footer>
</body>
</html># Bright-FuturesGlobal
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px 0;
    background: white;
    border-radius: 5px;
}

button {
    background: #4CAF50;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
}

button:hover {
    background: #45a049;
}

footer {
    text-align: center;
    padding: 10px;
    background: #333;
    color: white;
    position: fixed;
    width: 100%;
    bottom: 0;
}
