# Цель: вход в ЛК по СМС.
## Основной сценарий: 
1. Пользователь открывает вкладку вход личный кабинет
2. Система отображает поля, которые надо заполнить для авторизации (Емайл/логин, пароль, вход с помощью СМС кода) 
3. Пользователь выбирает вход с помощью СМС-кода
4. Пользователь вводит телефон
5. Пользователь нажимает кнопку **«Отправить код»**
6. Система отправляет СМС код на указанный номер
7. Пользователь вводит СМС код на странице входа в ЛК
8. Система проверяет корректность кода и предоставляет доступ в ЛК
## Альтернативный сценарий: 
1. Пользователь открывает личный кабинет
2. Система отображает поля, которые надо заполнить для авторизации (Емайл/логин, пароль, вход с помощью СМС кода) 
3. Пользователь выбирает вход с помощью СМС-кода
4. Пользователь вводит телефон
5. Пользователь нажимает кнопку **«Отправить код»**
6. Система отправляет СМС код на указанный номер
7. Пользователь вводит СМС код на странице входа в ЛК
8. Система проверяет корректность введенного СМС кода, указывает на то, что допущена ошибка и предоставляет возможность повторного ввода или отправку нового СМС кода
9. Пользователь повторно вводит СМС код
10. Система проверяет корректность кода и предоставляет доступ в ЛК

Исключение:
Если система несколько раз (например, 3 раза) отправила СМС код, и он был введен не верно, система блокирует отправку кодов на данный номер (например, на сутки)
