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
- **Languages** Russian Native, English Basic

# Jobs

## Reviewli CMS

![Reviewli CMS](https://raw.githubusercontent.com/allexgalbert/reviewlicms/main/DOC/fullLogo.png "Reviewli CMS")

https://github.com/allexgalbert/reviewlicms

## Динамическая Кнопка "Ещё" на каталоге товаров

![Динамическая Кнопка 'Ещё' на каталоге товаров](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/29.gif "Динамическая Кнопка 'Ещё' на каталоге товаров")

Каталог на CodeIgniter 3. Стандартная постраничная пагинация переписана на кнопку "Ещё". За основу взят пагинатор ядра фреймворка. Кнопка работает корректно со стандартной пагинацией, показывает оставшееся количество товара, который можно подгрузить.

## Система работы сайта на динамическом поддомене

![Система работы сайта на динамическом поддомене](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/28.png "Система работы сайта на динамическом поддомене")

Работает на принципе "пустого домена" и отсутствия контента непосредственно на домене domain.com

1. При заходе напрямую в браузере на домен domain.com, покажет заглушку "500 error. нет информации".
2. Система определяет, является ли IP посетителя входящим в список запрещенных IP-адресов. Если входит, то на домене domain.com показывает заглушку "500 error. нет информации".
3. Если посетитель является поисковым роботом (определяется по списку юзерагентов роботов поисковых систем) и является перешедшим по ссылке с другого сайта (определяется по реферреру), то контент сайта показывается на домене domain.com
4. Если поисковый робот поисковых систем зашел напрямую, то покажет контент на домене domain.com
5. Если посетитель перешел по ссылке с другого сайта (определяется по реферреру), то будет редирект на поддомен a.domain.com
6. Всех поисковых роботов поисковых систем редиректит с поддомена a.domain.com на домен domain.com
7. Для всех остальных случаев покажет заглушку "500 error. нет информации".

Таким образом фактически домен domain.com является пустым. Поддомен a.domain.com, который легко сменить на другой, не теряя позиции домена в поисковых системах и SEO. Избавляет от переезда с домена на домен и потерю ссылочной массы.

## Работа с картой OpenStreetMap через библиотеку Leaflet

![Работа с картой OpenStreetMap через библиотеку LeafletJS](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/27.gif "Работа с картой OpenStreetMap через библиотеку LeafletJS")

Реализация рендеринга карты OpenStreetMap через javascript-библиотеку Leaflet. Установка маркеров, с названием и попапом. Вывод одного или нескольких маркеров на карту. Центрирование карты. Масштаб на маркер. Кастомизированные иконки маркеров. Прослушивание событий. Удаление маркеров. Поле поиска. Нечеткий поиск. Автодополнение при поиске. Автоматическое определение текущей геолокации пользователя. Использованы библиотеки Leaflet, Esri-Leaflet, Esri-Leaflet-Geocoder.

## Яндекс-карты, вывод городов и адресов на карту

![Яндекс-карты, вывод городов и адресов на карту](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/26_1.gif "Яндекс-карты, вывод городов и адресов на карту")

Создание Яндекс-карты с точками городов, и отдельным выводом меню городов. При клике на город, карта увеличивается, появляется возможность посмотреть точки (конкретные адреса) в этом города.

## Работа с API Новой Пошты

![Работа с API Новой Пошты](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/25.gif "Работа с API Новой Пошты")

Система доставки почты на Украине, Новая Пошта (https://novaposhta.ua). Включает в себя обширные API-методы, по работе с посылками, клиентами, и доставкой. На магазине спортивного питания, в адреса клиента, был внедрён функционал полного создания адреса, на основе выбора областей, городов, и отделений, компании Новая Пошта. Актуальные данные забираются запросами из сервиса, подставляются в форму, сохраняются. Сделана возможность редактирования.

## Бот-переводчик для Telegram

![Бот-переводчик для Telegram](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/24_1.png "Бот-переводчик для Telegram")

Бот работает в связке VK-Telegram. Состоит из 2 частей. Первая часть это бот для VK, его можно добавить в любой чат, и он может читать все сообщения в чате. Вторая часть это бот для Telegram, он занимается тем, что собирает сообщения из чата VK, переводит на английский язык, и пересылает в Telegram. Кроме английского языка, доступны любые другие языки, потому что перевод работает на базе API Google Translate.

## Биржа фриланса

![Биржа фриланса](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/23.png "Биржа фриланса")

На чистом PHP реализована биржа фриланса. Каталог проектов, вакансий, фрилансеров, услуг. Категории, портфолио, стоимость. Вход через соцсети. http://1000developers.com

## Каталог моделей парусных кораблей

![Каталог моделей парусных кораблей](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/22.png "Каталог моделей парусных кораблей")

Сайт демонстрации и предзаказа деревянных моделей кораблей. Каталог моделей, страницы моделей, описание, фотографии, статичные страницы, формы заказа. Многоязычный интерфейс. http://lsmodel.ru

## Магазин сантехники

![Магазин сантехники](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/20.png "Магазин сантехники")

Доработка личного кабинета. Размещение на главной 3 товара-акции, доработка блока "Распродажа". Доработка категорий. Доработка меню. Доработка страницы покупки товара. http://santeh-shop.com.ua

## Агрегатор отзывов

![Агрегатор отзывов](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/19.png "Агрегатор отзывов")

Система отзывов на объекты по карте, в городах Москва и Санкт-Петербург. Оставление отзывов по 4м каналам: через Веб, QR-code, СМС, АТС. Создание объектов (название, описание, адрес, фотографии). Создание опроса (типы вопросов: одиночный выбор, множественный выбор, цифровая шкала, ответ текстом). Статистика по отзывам. Комментарии к отзывам. Создание и рассылка акций по пользователям системы. http://otzivchivo.ru

## Каталог музыкальных исполнителей

![Каталог музыкальных исполнителей](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/18.png "Каталог музыкальных исполнителей")

Сайт музыкального сообщества. На каждого артиста своя страница с фото, плейлист треков, подборка видео, биография, выборка последних постов с твиттера и фейсбука, данного артиста, последние новости цитаты и концерты. Создан на Kohana. http://albertaugustine.com

## Проект для компании "Фотострана"

![Проект для компании Фотострана](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/17.png "Проект для компании Фотострана")

Организация взаимодействия рекламных партнеров фотостраны. Контентные страницы: О проекте, Статистика, Возможности, Стоимость, Кейсы, FAQ, Контакты. Административная часть: работа с партнерами, кейсами, страницами, событиями. Создан на Kohana.

## Гостиница-отель

![Гостиница-отель](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/16.png "Гостиница-отель")

Доработка административной части сайта congresscomplex.ru. Создание мета-полей для сео-тегов, на каждой странице. Создание полей в админке и базе данных. Доработка редактора CKeditor. Движок кастомный. Фреймворк Codeigniter. http://congresscomplex.ru

## Магазин сантехники Акварим

[![Магазин сантехники Акварим](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/1.png "Магазин сантехники Акварим")](http://aquarome.ru)

Доработка админки, и страниц каталога и товара. Верстка сайта компании Акварим. Онлайн-магазин сантехники. Страницы каталога, спецпредложений, услуги, контакты, о компании, статичные страницы. Вертикальная выкладка товара. http://aquarome.ru

## Инструмент очистки баз данных от мусора

[![Инструмент очистки баз данных от мусора](https://raw.githubusercontent.com/allexgalbert/workflow/main/Portfolio/imgs/2.png "Инструмент очистки баз данных от мусора")](https://github.com/allexgalbert/workflow/tree/main/DatabaseCleaner)

Инструмент очистки баз данных на базе MySQL от мусора, плохих ссылок, спама, вредоносного кода, нецензурного контента. Автоматическая очистка по всем таблицам и полям, по ключевым словам и словосочетаниям. [Код](https://github.com/allexgalbert/workflow/tree/main/DatabaseCleaner)