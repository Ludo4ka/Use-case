# Use-case
Примеры use-case
Use-case для KLM 
Пример 1. Регистрация пользователя на сайте klm.com.
Цель: Зарегистрироваться на сайте https://www.klm.com
Пред.условия: Пользователь имеет доступ к интернету, зашёл на сайт https://www.klm.com
Действующие лица: Пользователь
Последовательность действий:
1.	Пользователь нажимает кнопку «Зарегистрироваться» на главной странице сайта
2.	Пользователь попадает на страницу Создания учетной записи и нажимает  кнопку «Create account»
3.	Сайт отображает форму регистрации
4.	Пользователь заполняет все поля формы, соглашается с правилами Flying Blue.
5.	Система регистрирует пользователя и появляется сообщение с номером карты (10 цифр).
6.	В базе данных создается запись о новом пользователе
Альтернативные пути: 
4а Ошибки в заполнении формы регистрации
4а 1. Сайт сообщает об ошибках в заполнении формы
4а 2. Переход на шаг 3
4b. Пользователь с таким логином/e-mail уже зарегистрирован
4b. 1. Сайт сообщает, что пользователь с таким логином/ e-mail уже существует
4b 2. Переход на шаг 3
4c Несогласие с Правилами и условиями Flying Blue.
4c 1.  Сайт не дает возможность продолжить регистрацию, без согласия с правилами и условиями Flying Blue
4с 2. Переход на шаг 3


Пример 2. Авторизация пользователя на сайт https://www.klm.com
Цель: Авторизоваться пользователю на сайте
Пред.условия: зайти на сайт https://www.klm.com
Действующие лица: Пользователь
Последовательность действий:
1.	Пользователь нажимает «Вход в систему» на главной странице сайта и запускает систему авторизации
2.	Система открывает сессию пользователя, предлагает ввести логин и пароль.
3.	Пользователь вводит логин и пароль.
4.	Система проверяет логин и пароль.
5.	Система идентифицировала пользователя и его права, создала запись в истории авторизаций.
6.	Пользователь попадает в личный кабинет, видит информацию о своем профиле.

Альтернативные пути: 
3а. Пользователь вводит неверный логин или пароль 
3а 1. Всплывает сообщение «These login details appear to be incorrect. Please verify the information and try again»
3а 2. Переход на шаг 3.
3а Пользователь нажимает «Напомнить пароль»
3а 1. Появляется попап «Введите Ваш номер Flying Blue или электронный адрес, и мы вышлем Вам временный пароль.»
3а 2. Пользователь вводит номер карты или электронный адрес
3а 3. Пользователь выбирает куда отправить временный пароль (на email или на телефон)
3а 4. Система требует ввести свои данные для подтверждения запроса
3а 5. Пользователь получает данные для авторизации 
3а 6. Переход на шаг 3.

Пример 3. Бронирование билета на сайт https://www.klm.com
Цель: Забронировать билет на сайте
Пред.условия: Пользователь авторизовался на сайте https://www.klm.com, видит на главной странице сайта форму «Бронирование»
Действующие лица: Пользователь, система бронирования 
Последовательность действий:
1.	Пользователь заполняет все обязательные поля  формы «Бронирование» на главной странице сайта и нажимает «Смотреть предложения»
2.	Система предоставляет пользователю все доступные варианты рейсов по заданному запросу пользователя
3.	Пользователь выбирает конкретный рейс, нажимает кнопку «Посмотреть информацию о рейсе»
4.	Пользователь бронирует рейс, нажав кнопку «Бронировать»
5.	Система требует ввести свои данные для подтверждения запроса бронирования
6.	Пользователь вводит данные и подтверждает запрос.
7.	Система выполняет сценарий «Бронирование»
8.	Появляется попап «Ваш билет забронирован! Перейти к оплате?»



Пример 4. Регистрация на рейс на сайте https://www.klm.com
Цель: Зарегистрироваться на рейс
Пред.условия: Пользователь авторизовался на сайте https://www.klm.com
Действующие лица: Пользователь, система регистрации на рейс
Последовательность действий:
1.	Пользователь выбирает в главном меню «Регистрация»
2.	Система напоминает, что зарегистрироваться на рейс можно за 30 ч.
3.	Система предлагает выбрать способ регистрации (по номеру билета/коду бронирования или номеру программы лояльности)
4.	Пользователь выбирает способ регистрации и попадает на страницу регистрации рейса
5.	Пользователь заполняет форму регистрации.
6.	Система выполняет сценарий регистрации на рейс и  высылает пользователю на e-mail подтверждение регистрации и регистрационные данные.


Пример 5. Бронирование жилья на сайт https://www.klm.com
Цель: Забронировать проживание 
Пред.условия: Пользователь зашел на сайт https://www.klm.com
Действующие лица: Пользователь
Последовательность действий:	
1.	Пользователь нажал на блок «Забронировать проживание» на главной странице сайта.
2.	Пользователя перекинуло на сторонний сайт https://sp.booking.com/
3.	Пользователь бронирует жилье на сайте https://sp.booking.com/

