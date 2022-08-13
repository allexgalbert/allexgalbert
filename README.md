# Био

- **Education** Volga State University of Technology, Radio Engineering Department, 1998-2003
- **Experience** 14 years of programming experience
  <br><br>
- **Backend** PHP, CodeIgniter, Yii, Laravel, MySQL, MariaDB, REST API
- **Frontend** HTML, CSS, Bootstrap, JavaScript, jQuery, Lodash, Axios
- **Tools** RabbitMQ, Redis, Selenium, Docker, Vagrant, Apache, Nginx
  <br><br>
- **API** Google Maps, Google Translate, Yandex Maps, Facebook, Telegram, Vkontakte
- **Projects** Online Shops, Catalogs, Dashboards, E-Commerce, Billing, Real Estate, CMS, Dating
  <br><br>
- **Software** PhpStorm, Workbench, HeidiSQL, Git, Composer
- **Working time** Monday - Friday, 10:00 - 18:00
- **Location** Turkey/Antalya UTC+3 TRT
  <br><br>
- **Hourly Rate** $25/hour
- **Languages** Русский родной, English Intermediate B1
  <br><br>
- **Email** allexgalbert@gmail.com
- **Telegram** https://t.me/allexgalbert
- **LinkedIn** https://www.linkedin.com/in/allexgalbert

# Портфолио

## Сервер очередей на базе RabbitMQ

- Постановка задач на отправку почты пользователям, используя сервер очередей
- Создание задачи, канала, обменника, очереди
- Отправка задачи в обменник
- Установка колбеков. Обработка задачи
- Отправка подтверждения выполнения задачи в RabbitMQ

[Код](https://github.com/allexgalbert/workflow/tree/main/RabbitMQ)

## Reviewli CMS

- Быстрая и простая CMS с открытым исходным кодом
- Немного похожа на Trustpilot или Tripadvisor
- Предназначена для создания каталога сайтов с отзывами о них

[Репозитарий](https://github.com/allexgalbert/reviewlicms)

## Система работы сайта на поддомене

- На домене domain.com контент отсутствует
- На поддомене a.domain.com контент присутствует
- С домена на поддомен происходит редирект
- Поддомен легко меняется на другой: b.domain.com, c.domain.com
- Не теряются позиции домена в поисковых системах и ссылочная масса
- Не нужен переезд с домена на домен

[Код](https://github.com/allexgalbert/workflow/tree/main/BogusSubdomain)

## Вывод адресов на карту OpenStreetMap

- Реализация рендеринга через библиотеки LeafletJS, Esri-Leaflet, Esri-Leaflet-Geocoder
- Установка маркеров с названием и попапом. Вывод одного или нескольких маркеров
- Центрирование карты. Масштаб на маркер. Свои иконки маркеров. Прослушивание событий. Удаление маркеров
- Поле поиска. Нечеткий поиск. Автодополнение при поиске
- Автоматическое определение текущей геолокации пользователя

[Код](https://github.com/allexgalbert/workflow/tree/main/OpenStreetMap)

## Меню городов и вывод адресов на Яндекс-карту

- Создание Яндекс-карты с отдельным меню городов
- Вывод адресов на карту
- При клике на город: карта увеличивается и фокусируется
- У каждого адреса блок: название, адрес, телефон, время работы, сайт

[Код](https://github.com/allexgalbert/workflow/tree/main/YandexMapPoints)

## Сбор информации об организациях с Яндекс-Карт

- По запросам типа "Москва магазины, Самара аптеки"
- Собираются данные: название, описание, адрес, сайт, категория, телефон, расписание, координаты
- Данные вставляются в базу

[Код](https://github.com/allexgalbert/workflow/tree/main/YandexMapParsing)

## Работа с API Нова Пошта

- Нова Пошта это сервис доставки почты на Украине https://novaposhta.ua
- Для магазина на базе CodeIgniter реализован функционал в личном кабинете клиента
- Создание и редактирование адреса на основе выбора областей, городов, и отделений
- Данные собираются по API и сохраняются в базу

[Код](https://github.com/allexgalbert/workflow/tree/main/NovaPoshta)

## Агрегатор отзывов

- Оставление отзывов по каналам: Веб, QR-code, СМС, АТС
- Создание объектов: название, описание, адрес, фотографии
- Создание опроса. Типы вопросов: одиночный выбор, множественный выбор, цифровая шкала, ответ текстом
- Комментарии к отзывам
- Статистика по отзывам

[Структура](https://github.com/allexgalbert/workflow/tree/main/PollsQuestions)

## Генератор названий для блогов

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

## Генератор ФИО, логина, пароля, номера паспорта

- Имени и фамилии
- Логина, по имени и фамилии
- Пароля, по имени и фамилии
- Пароля, как случайную строку
- Номера паспорта

[Код](https://github.com/allexgalbert/workflow/tree/main/PersonGenerator)

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

## Кнопка "Ещё" для каталога на фреймворке CodeIgniter

- Стандартная постраничная пагинация переписана на кнопку "Ещё"
- За основу взят пагинатор ядра фреймворка
- Кнопка работает корректно вместе со стандартной пагинацией
- Показывает оставшееся количество товара, который можно подгрузить

[Код](https://github.com/allexgalbert/workflow/tree/main/CodeIgniterPaginator)

## Геолокация MaxMind для фреймворка CodeIgniter

- MaxMind-DB-Reader устанавливается как PHP Extension
- Определение 2-значного ISO-кода страны пользователя по его IP
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

[Код](https://github.com/allexgalbert/workflow/tree/main/CodeIgniterLanguages)

## Бот VK и Telegram для перевода диалогов

- Первая часть это бот VK который можно добавить в любой чат
- Вторая часть это переводчик на базе Google API Translate для перевода сообщений
- Третья часть отправляет переведенные сообщения в Telegram

[Код](https://github.com/allexgalbert/workflow/tree/main/TelegramBot)

## Система работы с dating.ru с использованием Selenium

- Парсинг профилей по параметрам: пол, возраст, город
- Сбор профилей в бд
- Постинг на профиля по параметрам: пол, колво профилей за раз
- Личные сообщения с автоподстановкаой имени профиля

[Код](https://github.com/allexgalbert/workflow/tree/main/DatingParsingPosting)

## Система работы с VK с использованием Selenium

- Сбор групп в поиске, по заданым ключевым словам
- Сбор профилей, с групп
- Отправка сообщений пользователям
- Проверка наличия личных сообщений
- Сбор картинок с пабликов

[Код](https://github.com/allexgalbert/workflow/tree/main/VkParsingPosting)

## Автоматизация работы с Яндекс.DNS как регистратор

- Добавление домена
- Парковка домена
- Добавление, редактирование, и удаление DNS записей

[Код](https://github.com/allexgalbert/workflow/tree/main/YandexDNS)

## Очистка баз данных MySQL от мусора

- От плохих ссылок, спама, вредоносного кода, нецензурного контента
- Автоматическая очистка по всем таблицам и полям
- По ключевым словам и словосочетаниям

[Код](https://github.com/allexgalbert/workflow/tree/main/DatabaseCleaner)