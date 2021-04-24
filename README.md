# Portfolio

- **Age** 40 years old
- **Experience** 12 years of programming experience
  <br><br>
- **Backend** PHP, CodeIgniter, Laravel, MySQL, MariaDB
- **Frontend** HTML, CSS, JavaScript, jQuery, Bootstrap
  <br><br>
- **CMS** WordPress, PhpBB
- **API** Google Maps, Google Translate, Yandex Maps, Facebook, Telegram
- **Projects** Shops, Catalogs, Blogs, Dashboards
  <br><br>
- **Tools** PhpStorm, Workbench, HeidiSQL, Git, Composer
- **Working time** Monday - Friday, 10:00 - 18:00
- **Timezone** Europe/Moscow UTC+3:00 MSK
  <br><br>
- **Hourly Rate** $25/hour
- **Languages** Русский родной, English Basic

# Jobs

## Reviewli CMS

[![Reviewli CMS](https://raw.githubusercontent.com/allexgalbert/reviewlicms/main/DOC/fullLogo.png "Reviewli CMS")](https://github.com/allexgalbert/reviewlicms)

## Динамическая Кнопка "Ещё" на каталоге товаров

[![Динамическая Кнопка 'Ещё' на каталоге товаров](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/10.gif "Динамическая Кнопка 'Ещё' на каталоге товаров")](https://github.com)

Каталог на CodeIgniter 3. Стандартная постраничная пагинация переписана на кнопку "Ещё". За основу взят пагинатор ядра
фреймворка. Кнопка работает корректно со стандартной пагинацией, показывает оставшееся количество товара, который можно
подгрузить. [Код](https://github.com)

## Система работы сайта на динамическом поддомене

[![Система работы сайта на динамическом поддомене](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/9.png "Система работы сайта на динамическом поддомене")](https://github.com)

Работает на принципе "пустого домена" и отсутствия контента непосредственно на домене domain.com

1. При заходе напрямую в браузере на домен domain.com, покажет заглушку "500 error. нет информации".
2. Система определяет, является ли IP посетителя входящим в список запрещенных IP-адресов. Если входит, то на домене
   domain.com показывает заглушку "500 error. нет информации".
3. Если посетитель является поисковым роботом (определяется по списку юзерагентов роботов поисковых систем) и является
   перешедшим по ссылке с другого сайта (определяется по реферреру), то контент сайта показывается на домене domain.com
4. Если поисковый робот поисковых систем зашел напрямую, то покажет контент на домене domain.com
5. Если посетитель перешел по ссылке с другого сайта (определяется по реферреру), то будет редирект на поддомен
   a.domain.com
6. Всех поисковых роботов поисковых систем редиректит с поддомена a.domain.com на домен domain.com
7. Для всех остальных случаев покажет заглушку "500 error. нет информации".

Таким образом фактически домен domain.com является пустым. Поддомен a.domain.com, который легко сменить на другой, не
теряя позиции домена в поисковых системах и SEO. Избавляет от переезда с домена на домен и потерю ссылочной
массы. [Код](https://github.com)

## Работа с картой OpenStreetMap через библиотеку Leaflet

[![Работа с картой OpenStreetMap через библиотеку LeafletJS](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/8.gif "Работа с картой OpenStreetMap через библиотеку LeafletJS")](https://github.com/allexgalbert/workflow/blob/main/MiniSolutions/LeafletJS.html)

Реализация рендеринга карты OpenStreetMap через javascript-библиотеку Leaflet. Установка маркеров, с названием и
попапом. Вывод одного или нескольких маркеров на карту. Центрирование карты. Масштаб на маркер. Кастомизированные иконки
маркеров. Прослушивание событий. Удаление маркеров. Поле поиска. Нечеткий поиск. Автодополнение при поиске.
Автоматическое определение текущей геолокации пользователя. Использованы библиотеки Leaflet, Esri-Leaflet,
Esri-Leaflet-Geocoder. [Код](https://github.com/allexgalbert/workflow/blob/main/MiniSolutions/LeafletJS.html)

## Яндекс-карты, вывод городов и адресов на карту

[![Яндекс-карты, вывод городов и адресов на карту](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/7.gif "Яндекс-карты, вывод городов и адресов на карту")](https://github.com/allexgalbert/workflow/tree/main/YandexMapPoints)

Создание Яндекс-карты с точками городов, и отдельным выводом меню городов. При клике на город, карта увеличивается,
появляется возможность посмотреть точки (конкретные адреса) в этом
города. [Код](https://github.com/allexgalbert/workflow/tree/main/YandexMapPoints)

## Работа с API Новой Пошты

[![Работа с API Новой Пошты](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/6.gif "Работа с API Новой Пошты")](https://github.com)

Система доставки почты на Украине, Новая Пошта (https://novaposhta.ua). Включает в себя обширные API-методы, по работе с
посылками, клиентами, и доставкой. На магазине спортивного питания, в адреса клиента, был внедрён функционал полного
создания адреса, на основе выбора областей, городов, и отделений, компании Новая Пошта. Актуальные данные забираются
запросами из сервиса, подставляются в форму, сохраняются. Сделана возможность редактирования. [Код](https://github.com)

## Бот-переводчик для Telegram

[![Бот-переводчик для Telegram](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/5.png "Бот-переводчик для Telegram")](https://github.com/allexgalbert/workflow/tree/main/TelegramBot)

Бот работает в связке VK-Telegram. Состоит из 2 частей. Первая часть это бот для VK, его можно добавить в любой чат, и
он может читать все сообщения в чате. Вторая часть это бот для Telegram, он занимается тем, что собирает сообщения из
чата VK, переводит на английский язык, и пересылает в Telegram. Кроме английского языка, доступны любые другие языки,
потому что перевод работает на базе API Google
Translate. [Код](https://github.com/allexgalbert/workflow/tree/main/TelegramBot)

## Биржа фриланса

[![Биржа фриланса](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/4.png "Биржа фриланса")](https://github.com)

На чистом PHP реализована биржа фриланса. Каталог проектов, вакансий, фрилансеров, услуг. Категории, портфолио,
стоимость. Вход через соцсети. [Код](https://github.com)

## Агрегатор отзывов

[![Агрегатор отзывов](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/3.png "Агрегатор отзывов")](https://github.com/allexgalbert/workflow/tree/main/PollsQuestions)

Система отзывов на объекты по карте, в городах Москва и Санкт-Петербург. Оставление отзывов по 4м каналам: через Веб,
QR-code, СМС, АТС. Создание объектов (название, описание, адрес, фотографии). Создание опроса (типы вопросов: одиночный
выбор, множественный выбор, цифровая шкала, ответ текстом). Статистика по отзывам. Комментарии к отзывам. Создание и
рассылка акций по пользователям системы. [Код](https://github.com/allexgalbert/workflow/tree/main/PollsQuestions)

## Каталог музыкальных исполнителей

[![Каталог музыкальных исполнителей](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/2.png "Каталог музыкальных исполнителей")](http://albertaugustine.com)

Сайт музыкального сообщества. На каждого артиста своя страница с фото, плейлист треков, подборка видео, биография,
выборка последних постов с твиттера и фейсбука, данного артиста, последние новости цитаты и концерты. Создан на
Kohana. http://albertaugustine.com

# Генератор названий для блогов

- Любой длинны
- Любой тематики
- Гибкое конфигурирование

[Код](https://github.com/allexgalbert/workflow/tree/main/BlogTitleGenerator)

## Генератор названий доменов

- Нейтральное слово + тематическое слово
- Нейтральное слово + '-' + тематическое слово
- Тематическое слово + нейтральное слово
- Тематическое слово + '-' + нейтральное слово
- Тематическое слово + тематическое слово
- Тематическое слово + '-' + тематическое слово

[Код](https://github.com/allexgalbert/workflow/tree/main/DomainNameGenerator)

## Сбор вакансий с Indeed.com

- Из всех категорий
- Параметры вакансии: название, описание, страна, город, зарплата, валюта зарплаты, ссылка на вакансию
- Парсинг зарплаты из строки
- Данные вставляются в базу

[Код](https://github.com/allexgalbert/workflow/tree/main/IndeedParsing)

## Автоматические подписки и отписки в Instagram

- С чужого инстаграм-аккаунта собираем фоловеров, подписываемся на фоловеров, лайкаем несколько фоток у каждого фоловера
- Со своего инстаграм-аккаунта собираем подписчиков и подписки, проходим по списку подписок, отписываемся от аккаунтов
  кто не подписался в ответ

[Код](https://github.com/allexgalbert/workflow/tree/main/InstagramFollowers)

## Определение страны и города посетителя по IP на основе MaxMind, для фреймворка CodeIgniter

- MaxMind-DB-Reader устанавливается как PHP Extension
- Определение 2-значного ISO-код страны посетителя по его IP
- Автоматическое обновление базы GeoLite2-Country.mmdb

[Код](https://github.com/allexgalbert/workflow/blob/main/MiniSolutions/MaxMind.md)

## Реализация SEO на фреймворке CodeIgniter

- Установка метатегов description и keywords
- Глобально
- Для каждой страницы отдельно

[Код](https://github.com/allexgalbert/workflow/blob/main/MiniSolutions/CodeIgniterSeo.md)

## Реализация многоязычности на фреймворке CodeIgniter

- Определение локали и языка браузера пользователя
- Установка языка в урл /lang/ для всех ссылок
- Подгрузка файлов с сообщениями из языковых папок

[Код](https://github.com/allexgalbert/workflow/blob/main/MiniSolutions/CodeIgniterLanguages.md)

## Генератор ФИО, логина, пароля, номера паспорта

- Имени и фамилии
- Логина, по имени и фамилии
- Пароля, по имени и фамилии
- Пароля, как случайную строку
- Номера паспорта

[Код](https://github.com/allexgalbert/workflow/tree/main/PersonGenerator)

## Переводчик текстов на основе Google Api Translator

- Для чатов Вконтакте
- С пересылкой в бот Telegram

[Код](https://github.com/allexgalbert/workflow/tree/main/TelegramBot)

## Система работы с Вконтакте с использованием Selenium

- Сбор групп в поиске, по заданым ключевым словам
- Сбор профилей, с групп
- Отправка мессаги юзеру
- Проверка наличия личных сообщений
- Сбор картинок с пабликов вконтакте

[Код](https://github.com/allexgalbert/workflow/tree/main/VkParsingPosting)

## Автоматизация работы с Yandex DNS как регистратор

- Добавление домена
- Парковка домена
- Добавление, редактирование, и удаление DNS записей

[Код](https://github.com/allexgalbert/workflow/tree/main/YandexDNS)

## Сбор информации об организациях с Яндекс-Карт

- По запросам типа "Москва магазины, Самара аптеки"
- Собираются данные: название, описание, адрес, сайт, категория, телефон, расписание, координаты
- Данные вставляются в базу

[Код](https://github.com/allexgalbert/workflow/tree/main/YandexMapParsing)

## Инструмент очистки баз данных от мусора

[![Инструмент очистки баз данных от мусора](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/1.png "Инструмент очистки баз данных от мусора")](https://github.com/allexgalbert/workflow/tree/main/DatabaseCleaner)

Инструмент очистки баз данных на базе MySQL от мусора, плохих ссылок, спама, вредоносного кода, нецензурного контента.
Автоматическая очистка по всем таблицам и полям, по ключевым словам и словосочетаниям.

[Код](https://github.com/allexgalbert/workflow/tree/main/DatabaseCleaner)