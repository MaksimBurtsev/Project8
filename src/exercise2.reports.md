# Баг-репорты


 ```Номер бага``` | ```Название поля``` | ```Определение``` |
| ------ | ------ | ------ |
| 1 | ID | 1 |
| | Заголовок | Ошибка GET-запроса при обновлении главной страницы |
|  | Предусловие | Открыт сайт https://sbermegamarket.ru/|
|  | Шаги воспроизведения | Обновить страницу |
|  | Ожидаемый результат | Отсутствие ошибок |
|  | Фактический результат | GET-запрос https://sbermegamarketru.webim.ru/button.php выдает ошибку 502 (HTTP серверный код ответа на ошибку 502 Bad Gateway указывает, что сервер, действуя как шлюз или прокси, получил неверный ответ от восходящего сервера.) |
|  | Окружение | ОС: Microsoft Windows [Version 10.0.19043.985] Браузер: Firefox [Version 114.0.1] (64-разрядный) |
|  | Приоритет | Low (низкий) |
|  | Серьезность | Trivial (тривиальный) |
| |||
| 2 | ID | 2 |
|  | Заголовок | Ошибка GET-запроса при нажатии на "Войти" |
|  | Предусловие | Открыт сайт https://sbermegamarket.ru/ |
|  | Шаги воспроизведения | Нажать на кнопку "Войти" |
|  | Ожидаемый результат | Отсутствие ошибок |
|  | Фактический результат | GET-запрос https://online.sberbank.ru/CSAFront/api/oidc/sbid?client_id=52cd75e2-76e1-43ba-ade6-938b2c7d4e7a выдает ошибку 400 (Код состояния ответа "HTTP 400 Bad Request" указывает, что сервер не смог понять запрос из-за недействительного синтаксиса.) |
|  | Окружение | ОС: Microsoft Windows [Version 10.0.19043.985] Браузер: Firefox [Version 114.0.1] (64-разрядный) |
|  | Приоритет | Low (низкий) |
|  | Серьезность | Trivial (тривиальный) |
| |||
| 3 | ID | 3 |
|  | Заголовок | TypeError при нажатии на кнопку "Мега Выгода" |
|  | Предусловие | Открыт сайт https://sbermegamarket.ru/ |
|  | Шаги воспроизведения | Нажать на кнопку "Мега Выгода" |
|  | Ожидаемый результат | Отсутствие ошибок |
|  | Фактический результат | Появляется ошибка TypeError: DDManager Custom Event "Viewed Campaign" Error |
|  | Окружение | Microsoft Windows [Version 10.0.19043.985] Браузер: Firefox [Version 114.0.1] (64-разрядный) |
|  | Приоритет | Low (низкий) |
|  | Серьезность | Trivial (тривиальный) |
| |||
| 4 | ID | 4 |
|  | Заголовок | TypeError при нажатии на кнопку "Марафон скидок" |
|  | Предусловие | Открыт сайт https://sbermegamarket.ru/ |
|  | Шаги воспроизведения | Нажать на кнопку "Марафон Скидок" |
|  | Ожидаемый результат | Отсутствие ошибок |
|  | Фактический результат | Появляется ошибка TypeError: DDManager Custom Event "Viewed Campaign" Error |
|  | Окружение | Microsoft Windows [Version 10.0.19043.985] Браузер: Firefox [Version 114.0.1] (64-разрядный) |
|  | Приоритет | Low (низкий) |
|  | Серьезность | Trivial (тривиальный) |
| |||
| 5 | | ID | 5 |
| | Заголовок | TypeError при нажатии на кнопку "Красота" |
| | Предусловие | Открыт сайт https://sbermegamarket.ru/ |
| | Шаги воспроизведения | Нажать на кнопку "Красота" |
| | Ожидаемый результат | Отсутствие ошибок |
| | Фактический результат | Появляется ошибка TypeError: DDManager Custom Event "Viewed Campaign" Error |
| | Окружение | Microsoft Windows [Version 10.0.19043.985] Браузер: Firefox [Version 114.0.1] (64-разрядный) |
| | Приоритет | Low (низкий) |
| | Серьезность | Trivial (тривиальный) |
| |||
| 6 |  | ID | 6 |
| | Заголовок | TypeError при нажатии на значок "Корзина" |
| | Предусловие | Открыт сайт https://sbermegamarket.ru/ |
| | Шаги воспроизведения | Нажать на значок "Корзина" |
| | Ожидаемый результат | Отсутствие ошибок |
| | Фактический результат | Появляется ошибка TypeError: DDManager Custom Event "Clicked ToCart Button (Desktop + Mobile Main Icon)" Error e.getAttribute(...) is null |
| | Окружение | Microsoft Windows [Version 10.0.19043.985] Браузер: Firefox [Version 114.0.1] (64-разрядный) |
| | Приоритет | Low (низкий) |
| | Серьезность | Trivial (тривиальный) |
| |||
| 7 |  | ID | 7 |
| | Заголовок | Uncaught ReferenceError при нажатии на баннер "Жгучие скидки"  |
| | Предусловие | Открыт сайт https://sbermegamarket.ru/ |
| | Шаги воспроизведения | Нажать на баннер "Жгучие скидки" |
| | Ожидаемый результат | Отсутствие ошибок |
| | Фактический результат |  Появляется ошибка Uncaught ReferenceError: TouchEvent is not defined |
| | Окружение | Microsoft Windows [Version 10.0.19043.985] Браузер: Firefox [Version 114.0.1] (64-разрядный) |
| | Приоритет | Low (низкий) |
| | Серьезность | Trivial (тривиальный) |
| |||
| 8 |  | ID | 8 |
| | Заголовок | Uncaught ReferenceError при добавлении в корзину с главной страницы  |
| | Предусловие | Открыт сайт https://sbermegamarket.ru/ |
| | Шаги воспроизведения | Нажать кнопку "Купить" под товаром на главной странице |
| | Ожидаемый результат | Отсутствие ошибок |
| | Фактический результат |  Появляется ошибка Uncaught ReferenceError: product is not defined |
| | Окружение | Microsoft Windows [Version 10.0.19043.985] Браузер: Firefox [Version 114.0.1] (64-разрядный) |
| | Приоритет | Low (низкий) |
| | Серьезность | Trivial (тривиальный) |
| |||
| 9 |  | ID | 9 |
| | Заголовок | Множество ошибок при нажатии на "Стать продавцом" |
| | Предусловие | Открыт сайт https://sbermegamarket.ru/ |
| | Шаги воспроизведения | Нажать на "Стать продавцом" |
| | Ожидаемый результат | Отсутствие ошибок |
| | Фактический результат |  Появляются следующие ошибки: 1. GET https://sbermegamarketru.webim.ru/button.php - 502 Bad Gateway 2. TypeError: DDManager Custom Event "Viewed Product Listing" Error t.digitalData(...) is undefined 3. Запрос из постороннего источника заблокирован: Политика одного источника запрещает чтение удаленного ресурса на «https://vk.com/rtrg?p=VK-RTRG-1421183-77G99&products_event=view_other&price_list_id=1&e=1&i=0&metatag_url=%2F%2Fsbermegamarket.ru%2Finfo%2Fpartners%2F&metatag_title=%D0%A1%D0%B1%D0%B5%D1%80%D0%9C%D0%B5%D0%B3%D0%B0%D0%9C%D0%B0%D1%80%D0%BA%D0%B5%D1%82%20-%20%D0%BF%D0%B0%D1%80%D1%82%D0%BD%D1%91%D1%80%D0%B0%D0%BC%20-%20%D0%9C%D0%B0%D1%80%D0%BA%D0%B5%D1%82%D0%BF%D0%BB%D0%B5%D0%B9%D1%81%20SberMegaMarket.ru». (Причина: Учётные данные не поддерживаются, если заголовок CORS «Access-Control-Allow-Origin» установлен в «*»). 4. Open api access error 5. Запрос из постороннего источника заблокирован: Политика одного источника запрещает чтение удаленного ресурса на https://cms-res.online.sberbank.ru/sberid/BlackList/Button/No_Button.json. (Причина: не удалось выполнить запрос CORS). Код состояния: (null). 6. Uncaught (in promise) TypeError: e is null |
| | Окружение | Microsoft Windows [Version 10.0.19043.985] Браузер: Firefox [Version 114.0.1] (64-разрядный) |
| | Приоритет | Low (низкий) |
| | Серьезность | Trivial (тривиальный) |
| |||
| 10 |  | ID | 10 |
| | Заголовок |  Ошибки при возврате со страницы "Стать продавцом" на главную  |
| | Предусловие | 1. Открыт сайт https://sbermegamarket.ru/ 2. Произведен переход по ссылке "Стать продавцом" на страницу https://sbermegamarket.ru/info/partners/|
| | Шаги воспроизведения | Нажать в браузере кнопку "Назад" |
| | Ожидаемый результат | Отсутствие ошибок |
| | Фактический результат |  1. POST https://sentry-dsn-customers.megamarket.tech/api/6/envelope/?sentry_key=6d82cc11d08a4657a9092ff80b4bd615&sentry_version=7 - 503 Service Unavailable 2. GET https://sbermegamarketru.webim.ru/button.php - 502 Bad Gateway 3. Запрос из постороннего источника заблокирован: Политика одного источника запрещает чтение удаленного ресурса на https://cms-res.online.sberbank.ru/sberid/BlackList/Button/No_Button.json. (Причина: не удалось выполнить запрос CORS). Код состояния: (null). |
| | Окружение | Microsoft Windows [Version 10.0.19043.985] Браузер: Firefox [Version 114.0.1] (64-разрядный) |
| | Приоритет | Low (низкий) |
| | Серьезность | Trivial (тривиальный) |
___