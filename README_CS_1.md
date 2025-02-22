### Определение ролей пользователей:
- Администратор:
    - Управление всеми аспектами системы (заказы, клиенты, курьеры, блюда).
    - Назначение курьеров для заказов.
    - Просмотр отчетов о заказах и оплате.
- Пользователь:
    - Создание и управление заказами.
    - Выбор блюд из меню.
    - Оплата заказов.
    - Просмотр статуса заказа.
- Курьер:
    - Получение информации о заказах для доставки.
    - Обновление статуса заказа.
    
### Определение объектов для хранения данных:
- Пользователи (Users):
    - Идентификатор пользователя
    - Имя, email, телефон
    - Роль (администратор, клиент, курьер)
- Заказы (Orders):
    - Идентификатор заказа
    - Статус заказа (создан, оплачен, в пути, доставлен)
    - Время создания заказа
    - Идентификатор клиента
    - Идентификатор курьера
- Блюда (Dishes):
    - Идентификатор блюда
    - Название
    - Цена
    - Категория (пицца, суши и т.д.)
- Оплата (Payments):
    - Идентификатор оплаты
    - Статус оплаты (ожидание, завершена)
    - Идентификатор заказа