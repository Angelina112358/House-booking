# House-booking
## 1. Описание проекта
Проект "Сайт бронирования домов посуточно для мероприятий" представляет собой онлайн-платформу, которая позволяет пользователям бронировать дома и коттеджи на короткий срок для проведения различных мероприятий. На сайте будет представлен широкий выбор домов различной степени комфортности и размеров, что позволит каждому пользователю подобрать наиболее подходящий вариант.

Одной из ключевых особенностей сайта является наличие калькулятора цены, который позволяет пользователям рассчитать стоимость аренды дома с учетом всех дополнительных услуг и функций. Например, пользователь может выбрать услуги по организации банкета, аренде оборудования, услугам повара и т.д.

Кроме того, на сайте будет представлена страница с мероприятиями, где пользователи смогут найти информацию о различных мероприятиях, которые проходят в ближайшее время, и забронировать дом для их проведения. На этой странице будут представлены не только мероприятия, организованные нашей компанией, но и другие события, которые могут быть интересны нашим пользователям.

Для удобства пользователей на сайте будет реализована система онлайн-бронирования, которая позволит быстро и легко забронировать дом или коттедж на нужные даты. Пользователи смогут выбрать удобный способ оплаты и получить подтверждение бронирования на электронную почту.

В целом, проект "Сайт бронирования домов посуточно для мероприятий" позволит пользователям быстро и удобно найти подходящий вариант для проведения своего мероприятия, а также сэкономить время и силы на организацию всего процесса.

## 2. Ссылка на mock up в figma
https://www.figma.com/file/BHTsLFUy15FkOqYTsWpHSZ/House-booking?node-id=0-1&t=gDt21jCkbzXH8DTw-0

## 3. Описание ключевых функций проекта
1. Функция расчета стоимости аренды дома с учетом всех дополнительных услуг и функций.
2. Функция онлайн-бронирования домов и коттеджей на нужные даты.
3. Функция личного кабинета для пользователей, где они могут просматривать свои бронирования, изменять их и отменять.
4. Функция административной панели для управления списком домов и коттеджей, ценами, услугами, мероприятиями и бронированиями.
6. Функция сортировки домов по стоимости позволяет пользователям выбрать дом, который соответствует их бюджету. При выборе этой функции, пользователи могут увидеть список всех доступных домов, отсортированных по возрастанию или убыванию цены. Это помогает пользователям выбрать наиболее подходящий вариант для них.
7. Функция сортировки домов по времени (ближайшая дата) позволяет пользователям выбрать дом, который доступен в ближайшее время. При выборе этой функции, пользователи могут увидеть список всех доступных домов, отсортированных по возрастанию или убыванию времени. Это помогает пользователям выбрать дом, который подходит для их планируемой даты пребывания.

## 4. Описание моделей проекта
1. Модель данных для информации о домах:
- Идентификатор дома
- Название дома
- Адрес дома
- Описание дома
- Количество спален
- Количество ванных комнат
- Площадь дома
- Стоимость аренды в день
- Дата доступности

2. Модель данных для информации о пользователях:
- Идентификатор пользователя
- Имя пользователя
- Электронная почта пользователя
- Пароль пользователя
- Адрес пользователя
- Номер телефона пользователя

3. Модель данных для информации о бронировании:
- Идентификатор бронирования
- Идентификатор дома
- Идентификатор пользователя
- Дата начала бронирования
- Дата окончания бронирования
- Общая стоимость бронирования

4. Модель данных для информации о отзывах:
- Идентификатор отзыва
- Идентификатор дома
- Идентификатор пользователя
- Оценка дома (от 1 до 5)
- Текст отзыва

5. Модель данных для информации о платежах:
- Идентификатор платежа
- Идентификатор бронирования
- Сумма платежа
- Дата платежа

## 5. Основные теги html
1. \<header> - для создания верхней части веб-сайта, содержащей логотип, название сайта и навигационное меню.
2. \<nav> - для создания навигационного меню, содержащего ссылки на разделы веб-сайта.
3. \<section> - для создания основного содержимого веб-сайта, содержащего информацию о доступных домах для бронирования.
4. \<article> - для создания отдельных статей о каждом доме, содержащих фотографии, описания, цены и варианты бронирования.
5. \<aside> - для создания дополнительной информации, такой как реклама и ссылки на социальные сети.
6. \<footer> - для создания нижней части веб-сайта, содержащей контактную информацию, ссылки на политику конфиденциальности и условия использования, а также информацию об авторских правах.
7. \<h1-6> - для создания заголовков страниц и разделов.
8. \<p> - для создания текстового содержимого на странице.
9. \<img> - для добавления изображений на страницу.
10. \<ul> - для создания маркированных списков.
11. \<ol> - для создания нумерованных списков.
12. \<a> - для создания гиперссылок на другие страницы или ресурсы.
13. \<form> - для создания формы обратной связи или формы для бронирования домов.
14. \<input> - для добавления полей ввода на форму.
15. \<button> - для создания кнопок на странице, которые могут выполнять определенные действия, такие как отправка формы или перенаправление на другую страницу.
16. \<label> - для маркировки полей ввода на форме.
17. \<select> - для создания раскрывающегося списка на форме.
18. \<option> - для создания вариантов в раскрывающемся списке на форме.
19. \<textarea> - для создания более крупного поля ввода на форме для длинных ответов.
20. \<div> - для группировки элементов вместе и применения к ним стилей как к группе.

