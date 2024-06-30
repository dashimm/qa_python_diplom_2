## Дипломный проект. Задание 2: API-тесты

### Автотесты для проверки программы, которая помогает заказать бургер в Stellar Burgers

### Реализованные сценарии
Созданы api-тесты, покрывающие проверку на: регистрацию юзера, создание юзера, создание заказа, изменение данных юзера, 
получение конретного заказа

### Структура проекта
tests - пакет, содержащий тесты, разделенные по апи ручкам
helpers и const_data - тестовые данные

### Запуск автотестов

**Установка зависимостей**

$ pip3 install -r requirements.txt

**Allure отчет о тестировании**

$ allure serve allure_results