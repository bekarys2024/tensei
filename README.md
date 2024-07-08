<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Заказ Жалюзи</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            width: 100%;
            padding: 20px;
            text-align: center;
            background-color: #ffffff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
            color: #333;
        }
        .content {
            width: 80%;
            max-width: 1200px;
            margin: 20px 0;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .form-section {
            width: 100%;
            max-width: 600px;
            margin-top: 20px;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form label {
            margin-top: 10px;
        }
        form input, form textarea, form button {
            margin-top: 5px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        form button {
            margin-top: 20px;
            background-color: #007BFF;
            color: white;
            cursor: pointer;
        }
        footer {
            width: 100%;
            padding: 20px;
            text-align: center;
            background-color: #ffffff;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
        }
        footer a {
            color: #007BFF;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Заказ Жалюзи</h1>
    </header>
    <div class="content">
        <h2>Контактные данные</h2>
        <p>Телефон: <a href="tel:+787756507923">+7 775 650 7923</a></p>
        <p>Местоположение: <a href="https://2gis.kz/aktobe/geo/70000001088974751" target="_blank">2GIS</a></p>
    </div>
    <div class="form-section">
        <h2>Оставить заявку на замеры</h2>
        <form action="#" method="post">
            <label for="name">Имя</label>
            <input type="text" id="name" name="name" required>
            
            <label for="phone">Номер телефона</label>
            <input type="tel" id="phone" name="phone" required>
            
            <label for="address">Адрес</label>
            <textarea id="address" name="address" rows="3" required></textarea>
            
            <button type="submit">Отправить</button>
        </form>
    </div>
    <footer>
        <p>Наше местоположение: <a href="https://2gis.kz/aktobe/geo/70000001088974751" target="_blank">2GIS</a></p>
    </footer>
</body>
</html>
