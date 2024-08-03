# privet-anton.github.io
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privet</title>
    <style>
        /* Стиль кнопки */
        .btn {
            display: inline-block;
            padding: 10px 20px;
            font-size: 16px;
            color: #fff;
            background-color: #eb0808;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        /* Эффект наведения на кнопку */
        .btn:hover {
            background-color: #45a049;
        }
    </style>
    <script>
        // Функция для перехода на другую страницу
        function redirectToPage() {
            // Укажите здесь URL страницы, на которую хотите перенаправить пользователя
            const url = "page1.html"; // Относительный путь к файлу page1.html

            // Переход на указанную страницу
            window.location.href = url;
        }
    </script>
</head>
<body>
    <h1>Привет, Антон!</h1>

    <!-- Кнопка, вызывающая функцию redirectToPage() при нажатии -->
    <button class="btn" onclick="redirectToPage()">Нажми на меня!</button>
</body>
</html>
