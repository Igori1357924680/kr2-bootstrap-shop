# PlayTable — магазин гаджетов на Bootstrap

## Контрольная работа №2
Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

В проекте реализована версия сайта интернет-магазина гаджетов и аксессуаров PlayTable с использованием CSS-фреймворка Bootstrap.

## Используемый фреймворк
Bootstrap (версия 5.3.8).

## Способ подключения
Bootstrap подключён через CDN (Content Delivery Network).
В `head` HTML-документа подключен `bootstrap.min.css`, а перед закрывающим тегом `body` — `bootstrap.bundle.min.js`.
Собственный файл `css/custom.css` подключён после Bootstrap для точечного переопределения стилей.

## Структура проекта
```text
kr2-bootstrap-shop/
├── index.html
├── catalog.html
├── product.html
├── order.html
├── css/
│   └── custom.css
├── images/
├── .nojekyll
└── README.md

## Реализованные Bootstrap-компоненты

Сетка: container, row, col-12, col-md-6, col-lg-*, g-4.

Навигация: navbar, navbar-expand-lg, мобильное меню (collapse).

Карточки: card, card-body, card-title, card-text.

Кнопки: btn, btn-primary, btn-outline-primary, btn-lg.

Значки: badge (с цветами bg-danger, bg-success, bg-warning).

Формы: form-control, form-select, input-group, form-check.

Модальное окно: modal, modal-dialog, modal-content.

Сообщения: alert, alert-info.

Дополнительный компонент: accordion (блок FAQ на главной странице).

## Обязательные страницы

index.html — главная (hero, преимущества, популярные товары, аккордеон).

catalog.html — каталог (сетка карточек, фильтры).

product.html — страница товара (таблица характеристик, модальное окно заявки).

order.html — форма оформления заявки.

## Самостоятельные доработки

Использование утилит Bootstrap (shadow-sm, d-flex, flex-column, mt-auto, min-vh-100 и др.) для создания «прилипающего» подвала.

Стилизация карточек в custom.css (эффект легкого поднятия при наведении).

Адаптивная верстка (проверено на мобильных устройствах).

Добавлен .nojekyll для корректной работы GitHub Pages без Jekyll.

## Автор
ФИО: Дуняшин Игорь Александрович
Группа: ЭФБО-12-25