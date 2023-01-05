# QAMID-Coursework-for-4-Modules

**Запуск SUT, авто-тестов и генерация репорта**
*Подключение SUT к MySQL*

1. Запустить Docker Desktop.  
2. Открыть проект в IntelliJ IDEA.   
3. В терминале в корне проекта запустить контейнеры: docker-compose up    
4. Открыть второй терминал.   
5. Запустить приложение: java -jar .\artifacts\aqa-shop.jar   
6. Открыть третий терминал.   
7. Запустить тесты: .\gradlew clean test   
8. Создать отчёт Allure и открыть в браузере: .\gradlew allureServe
