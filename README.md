Тестирование функционала Jira: авторизация, вход в проект, количество задач, вход в задачу, создание новой задачи

# запуск всех тестов
mvn clean test

# запуск тестов по тегам 1,2,3,4,5
mvn clean test -Dgroups=перечень из одного или нескольких через запятую

# построение отчета Allure
mvn allure:serve

# настройки в классе TestParams
параметризация создания задачи

# настройки в проперти:
application.properties - параметризация тестов

browser.properties - настройки браузеров, Selenoid (описание в файле)

listener.properties - настройки листенера скриншотов для Allure (описание в файле)
