Автоматизация теста к API Яндекс Самокат:
1. Клиент создает заказ.
2. Проверяется, что по треку заказа можно получить данные о заказе. 

Шаги автотеста:
1. Выполнить запрос на создание заказа. 
2. Сохранить номер трека заказа. 
3. Выполнить запрос на получения заказа по треку заказа. 
4. Проверить, что код ответа равен 200.