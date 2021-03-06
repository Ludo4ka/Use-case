# Use-cases 

## Use-case для сайта https://www.klm.com 

#### Use-case1  Регистрация пользователя на сайте   
Цель: Зарегистрироваться на сайте https://www.klm.com  
Пред.условия: Покупатель имеет доступ к интернету, зашёл на сайт https://www.klm.com Выбран регион и язык.  
Действующие лица: Покупатель  
Последовательность действий:  
1.	Покупатель нажимает кнопку «Зарегистрироваться» на главной странице сайта.
2.	Покупатель попадает на страницу Добавления карты лояльности, выбирает положение переключателя (switcher) на активный(выбрали карту лояльности)/неактивный(отказались от карты лояльности). Нажимает кнопку «Create account».
3.	Сайт отображает 1 стр. форму регистрации "Здравствуйте! Как Вас зовут?". Заполнить поля: "Имя", "Фамилия" латинскими буквами. Нажать "Продолжить".
4.	Сайт отображает 2 стр.  формы регистрации "Расскажите немного о себе". Заполнить  поля "Дата рождения", "Пол". Нажать "Продолжить".
5.	Сайт отображает 3 стр. формы регистрации "Где Вы живете?". Заполнить поля "Страна проживания", "Язык", при желании "Телефон". Нажать "Продожить".
6.	Сайт отображает 4 стр. формы регистрации "Как мы можем с Вами связаться". Заполнить поле "Электронный адрес". Нажать "Продолжить".
7.	Сайт отображает 5 стр. формы регистрации "Вы хотели бы получать наши обновления?". В checkbox выбрать пункты. Нажать "Продолжить".
8.	Сайт отображает 6 стр. формы регистрации "Создайте пароль". Вбить пароль. Нажать "Продолжить".
9.	Сайт отображает 7 стр. формы регистрации о принятии правил и условий Flying Blue. Принять правила. Нажать "Продолжить".
10.	Система регистрирует полкупателя и появляется сообщение с номером карты (10 цифр).
11.	В базе данных создается запись о новом пользователе.

#### Use-case2  Авторизация пользователя на сайте  
Цель: Авторизоваться пользователю на сайте  
Пред.условия: зайти на сайт https://www.klm.com  
Действующие лица: Пользователь  
Последовательность действий:  
1.	Пользователь нажимает «Вход в систему» на главной странице сайта и запускает систему авторизации.
2.	Система открывает сессию пользователя, предлагает ввести логин (номер карты или email) и пароль.
3.	Пользователь вводит логин и пароль. Нажимает "Войти в систему".
4.	Система проверяет логин и пароль. Система идентифицировала пользователя и его права, создала запись в истории авторизаций.
5.	Пользователь попадает в личный кабинет и  видит имя своего профиля в правом верхнем углу.

#### Use-case3 Бронирование билета на сайте  
Цель: Забронировать билет и перейти на сайт оплаты https://payments.klm.com  
Пред.условия: Покупатель авторизовался на сайте https://www.klm.com, видит на главной странице сайта форму «Бронирование».  
Действующие лица: Покупатель.  
Последовательность действий:
1.	Покупателть заполняет  поля формы «Бронирование» на главной странице сайта и нажимает «Смотреть предложения».
2.	Сайт предоставляет покупателю форму календаря с тарифами рейсов.
3.	Покупатель нажимает на  выбранные ячеки календаря (дата отправления, дата возвращения)
4.	Сайт отображает в отдельном блоке  рейсы, которые доступны в эти дни.
5.	Покупатель выбирает конкретный рейс, нажимает на зеленую кнопку с тарифом.
6.	Сайт отображает варианты билетов на выбранный рейс (Эконом/бизнесс класс, тарифы: Light, Standart, Flex). 
7.	Покупатель выбирает вариант билета и нажимает кнопку "Выбрать". 
8.	Сайт отображает страницу "Ваше путешествие в (город)" с выбранными рейсами и билетами.
9.	Покупатель нажимает "Продолжить".
10.	Сайт открывает 1 стр. "Персональные данные" с запросом дополнительной информации о пассажире.
11.	Покупатель заполняет поля и нажимает кнопку "Подтвердить".
12.	Сайт открывает 2 стр. "Персональные данные" с запросом контактов.
13.	Покупател заполняет поля и нажимает кнопку "Подвтердить". 
14.	Сайт открывает 3 стр. "Персональные данные " с запросом присоединиться к программе лояльности.
15.	Покупатель заполняет необходимые данные и нажимет "Присоединиться". На этой же страницы знакомиться с "Дополнительные формальности" и нажимает кнопку "Продолжить"
16.	Сайт открывает стр. "Дополнительные опции". Покупатель выбирает/невыбирает доп.опции и нажимает кнопку "Продолжить". 

#### Use-case4 Регистрация на рейс на сайте  
Цель: Получить на e-mail подтверждение регистрации на рейс и регистрационные данные.  
Пред.условия: Пользователь авторизовался на сайте https://www.klm.com  
Действующие лица: Пассажир.  
Последовательность действий:  
1.	Пассажир выбирает в главном меню «Регистрация».
2.	Система напоминает, что зарегистрироваться на рейс можно за 30 ч.
3.	Система предлагает выбрать способ регистрации (по номеру билета/коду бронирования или номеру программы лояльности).
4.	Пассажир выбирает способ регистрации, вводит номер рейса и нажимает "Зарегистрироваться".
5.	Сайт открывает  страницу регистрации рейса.
6.	Пассажир заполняет форму регистрации.
7.	Система выполняет сценарий регистрации на рейс и высылает пассажиру на e-mail подтверждение регистрации и регистрационные данные.

#### Use-case5 Бронирование жилья на сайте  
Цель: Забронировать проживание.  
Пред.условия: Турист зашел на сайт https://www.klm.com  
Действующие лица: Турист  
Последовательность действий:  
1.	Турист нажал на блок «Забронировать проживание» на главной странице сайта.
2.	Сайт перекинул туриста на сайт https://sp.booking.com
