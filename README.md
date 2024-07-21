## Тесты для сайта Stellar Burgers
Выполняются в браузере Chrome
Для выполнения требуется установить соответствующий драйвер

Файл test_registration.py содержит следующие проверки:
- регистрация успешна
- Поле «Имя» не пустое; 
- в поле Email введён email в формате логин@домен
- Минимальный пароль — шесть символов.
- для некорректного пароля высвечивается ошибка.

Файл test_login.py содержит следующие проверки:
- вход по кнопке «Войти в аккаунт» на главной,
- вход через кнопку «Личный кабинет»,
- вход через кнопку в форме регистрации,
- вход через кнопку в форме восстановления пароля.

Файл test_logout.py содержит:
- проверку успешного выхода из аккаунта

Файл test_transitions.py содержит следующие проверки:
- переход в личный кабинет по клику на «Личный кабинет»
- переход на главную по клику на «Конструктор» и на логотип Stellar Burgers
- переходы к разделам: «Булки», «Соусы», «Начинки».
