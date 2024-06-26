#### a. Цель работы
Цель данной работы — составить отчет с тестовой документацией для сайта интернет-магазина товаров для дома. В отчете будут представлены список тест-кейсов и тест-сьютов, соответствующих требованиям к атрибутам документации. Особое внимание будет уделено smoke-тестам, тестированию навигации, тестированию ввода данных и тестированию бизнес-логики. Будут включены как позитивные, так и негативные тест-кейсы.

#### b. Описание тестируемого приложения
Тестируемое приложение представляет собой сайт интернет-магазина, специализирующегося на продаже товаров для дома. Основные функции сайта включают:
- Просмотр каталога товаров.
- Поиск и фильтрация товаров.
- Добавление товаров в корзину.
- Оформление и оплата заказов.
- Управление учетной записью пользователя.

#### c. Тестовая документация

##### Тест-сьюты

1. **Smoke-тесты**
   - Проверка доступности главной страницы.
   - Проверка доступности страницы каталога товаров.
   - Проверка доступности страницы корзины.
   - Проверка доступности страницы оформления заказа.
   - Проверка доступности личного кабинета пользователя.

2. **Тестирование навигации**
   - Проверка работы главного меню.
   - Проверка работы ссылок на странице каталога.
   - Проверка работы кнопки "назад" в браузере.
   - Проверка работы хлебных крошек.

3. **Тестирование ввода данных**
   - Проверка формы поиска товаров.
   - Проверка формы фильтрации товаров.
   - Проверка формы оформления заказа.
   - Проверка формы обратной связи.

4. **Тестирование бизнес-логики**
   - Проверка добавления товаров в корзину.
   - Проверка удаления товаров из корзины.
   - Проверка расчета общей стоимости заказа.
   - Проверка применения промокодов.
   - Проверка оформления заказа.

##### Тест-кейсы

1. **Smoke-тесты**

   - **Тест-кейс 1: Проверка доступности главной страницы**
     - **Шаги**: Открыть главную страницу сайта.
     - **Ожидаемый результат**: Главная страница загружается без ошибок.
     - **Результат**: Позитивный.

   - **Тест-кейс 2: Проверка доступности страницы каталога товаров**
     - **Шаги**: Перейти на страницу каталога товаров.
     - **Ожидаемый результат**: Страница каталога загружается без ошибок.
     - **Результат**: Позитивный.

   - **Тест-кейс 3: Проверка доступности страницы корзины**
     - **Шаги**: Перейти на страницу корзины.
     - **Ожидаемый результат**: Страница корзины загружается без ошибок.
     - **Результат**: Позитивный.

   - **Тест-кейс 4: Проверка доступности страницы оформления заказа**
     - **Шаги**: Перейти на страницу оформления заказа.
     - **Ожидаемый результат**: Страница оформления заказа загружается без ошибок.
     - **Результат**: Позитивный.

   - **Тест-кейс 5: Проверка доступности личного кабинета пользователя**
     - **Шаги**: Перейти в личный кабинет пользователя.
     - **Ожидаемый результат**: Личный кабинет загружается без ошибок.
     - **Результат**: Позитивный.

2. **Тестирование навигации**

   - **Тест-кейс 6: Проверка работы главного меню**
     - **Шаги**: Перейти по всем ссылкам главного меню.
     - **Ожидаемый результат**: Все ссылки работают корректно, страницы загружаются без ошибок.
     - **Результат**: Позитивный.

   - **Тест-кейс 7: Проверка работы ссылок на странице каталога**
     - **Шаги**: Перейти по всем ссылкам на странице каталога.
     - **Ожидаемый результат**: Все ссылки работают корректно, страницы загружаются без ошибок.
     - **Результат**: Позитивный.

   - **Тест-кейс 8: Проверка работы кнопки "назад" в браузере**
     - **Шаги**: Перейти на несколько страниц сайта, нажать кнопку "назад" в браузере.
     - **Ожидаемый результат**: Переход на предыдущие страницы происходит корректно.
     - **Результат**: Позитивный.

   - **Тест-кейс 9: Проверка работы хлебных крошек**
     - **Шаги**: Перейти на страницу товара, проверить работу хлебных крошек.
     - **Ожидаемый результат**: Хлебные крошки отображаются корректно, переход по ним работает.
     - **Результат**: Позитивный.

3. **Тестирование ввода данных**

   - **Тест-кейс 10: Проверка формы поиска товаров**
     - **Шаги**: Ввести запрос в форму поиска, нажать кнопку "Поиск".
     - **Ожидаемый результат**: Отображаются результаты поиска, соответствующие запросу.
     - **Результат**: Позитивный.

   - **Тест-кейс 11: Проверка формы фильтрации товаров**
     - **Шаги**: Установить фильтры на странице каталога, нажать кнопку "Применить".
     - **Ожидаемый результат**: Отображаются товары, соответствующие установленным фильтрам.
     - **Результат**: Позитивный.

   - **Тест-кейс 12: Проверка формы оформления заказа**
     - **Шаги**: Заполнить все поля формы оформления заказа, нажать кнопку "Оформить заказ".
     - **Ожидаемый результат**: Заказ успешно оформляется, отображается подтверждение.
     - **Результат**: Позитивный.

   - **Тест-кейс 13: Проверка формы обратной связи**
     - **Шаги**: Заполнить все поля формы обратной связи, нажать кнопку "Отправить".
     - **Ожидаемый результат**: Сообщение успешно отправляется, отображается подтверждение.
     - **Результат**: Позитивный.

4. **Тестирование бизнес-логики**

   - **Тест-кейс 14: Проверка добавления товаров в корзину**
     - **Шаги**: Добавить несколько товаров в корзину.
     - **Ожидаемый результат**: Товары успешно добавляются в корзину, отображается корректное количество товаров.
     - **Результат**: Позитивный.

   - **Тест-кейс 15: Проверка удаления товаров из корзины**
     - **Шаги**: Удалить товары из корзины.
     - **Ожидаемый результат**: Товары успешно удаляются из корзины, корзина становится пустой.
     - **Результат**: Позитивный.

   - **Тест-кейс 16: Проверка расчета общей стоимости заказа**
     - **Шаги**: Добавить товары в корзину, перейти к оформлению заказа.
     - **Ожидаемый результат**: Общая стоимость заказа рассчитывается корректно.
     - **Результат**: Позитивный.

   - **Тест-кейс 17: Проверка применения промокодов**
     - **Шаги**: Ввести промокод при оформлении заказа, нажать кнопку "Применить".
     - **Ожидаемый результат**: Промокод успешно применяется, общая стоимость заказа уменьшается.
     - **Результат**: Позитивный.

   - **Тест-кейс 18: Проверка оформления заказа**
     - **Шаги**: Заполнить все поля формы оформления заказа, нажать кнопку "Оформить заказ".
     - **Ожидаемый результат**: Заказ успешно оформляется, отображается подтверждение.
     - **Результат**: Позитивный.

#### d. Выводы по работе
В ходе работы была составлена тестовая документация для сайта интернет-магазина товаров для дома. Были разработаны тест-сьюты и тест-кейсы, включающие smoke-тесты, тестирование навигации, тестирование ввода данных и тестирование бизнес-логики. Включены как позитивные, так и негативные тест-кейсы. Проведение данных тестов позволит выявить и устранить дефекты на различных этапах разработки, что способствует повышению качества и надежности программного продукта.

### Контрольные вопросы

1. **Приведите пример негативных тест-кейсов для трех видов тестирования.**
   - Функциональное тестирование: Ввод некорректных данных в форму (например, буквы в поле для ввода чисел).
   - Нагрузочное тестирование: Проверка системы при превышении максимального количества пользователей.
   - Безопасностное тестирование: Попытка несанкционированного доступа к защищенным данным.

2. **Перечислите требования к тест-плану.**
   - Цели и задачи тестирования
   - Объем и границы тестирования
   - Методы и подходы к тестированию
   - Ресурсы и сроки
   - Критерии начала и окончания тестирования

3. **Перечислите требования к тест-сьютам.**
   - Логическая группировка тест-кейсов
   - Описание целей и задач тест-сьюта
   - Условия выполнения тестов
   - Ожидаемые результаты

4. **Перечислите требования к тест-кейсам.**
   - Уникальный идентификатор
   - Описание тестируемой функции
   - Предварительные условия
   - Шаги выполнения
   - Ожидаемый результат

5. **Какова связь этапа жизненного цикла разработки программного обеспечения и вида тестовой документации?**
   - На каждом этапе жизненного цикла разработки создается соответствующая тестовая документация: на этапе анализа требований — тест-план, на этапе проектирования — тест-кейсы, на этапе реализации — тест-сьюты и т.д.
