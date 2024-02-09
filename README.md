# Тестовое задание на позицию Frontend разработчика

Реализовать React клиент который предоставляет информацию о персонажах,
кораблях и событиях из вселенной Звездных войн.

В качестве источника данных использовать открытое graphql API
<https://studio.apollographql.com/public/star-wars-swapi/variant/current/home>

## Описание

Приложение должно состоять из перечисленных ниже страниц. Каждая страница
должна быть доступна по своему уникальному URL и содержать маршрутизацию.
Приложение должно быть реализовано с использованием React. Приложение должно
быть адаптивным и поддерживать различные разрешения экранов. Дизайн приложения
не имеет значения, но должен быть читаемым и понятным, можно использовать любые
библиотеки для стилизации (Material UI, Tailwind и др.).

1) Главная страница со всеми разделами.
2) Отображение списка персонажей: приложение должно отображать список персонажей
   с их именами и изображениями. Пользователь может сортировать список по
   различным критериям, таким как принадлежность, происхождение или роль.
3) Получение данных о персонаже: приложение должно делать запрос API, чтобы
   получить информацию о конкретном персонаже, включая имя, происхождение,
   принадлежность и роли в фильмах и/или сериалах.
4) Отображение списка кораблей: аналогично списку персонажей, приложение должно
   отображать список кораблей с их названиями и изображениями.
5) Получение данных о корабле: аналогично персонажам, приложение должно получать
   информацию о кораблях, включая название, класс, модель и изображения.
6) Отображение списка эпизодов: приложение должно отображать список эпизодов с
   их названиями, годами выпуска и изображение.
7) Получение данных об эпизоде: приложение должно получать данные об
   определенном эпизоде Звездных войн, включая название эпизода, год выпуска,
   актеров, краткий обзор сюжета и изображение.

Для получения изображений можно использовать сторонний ресурс. Например
изображение для эпизода "The Phantom Menance" можно получить по ссылке:
<https://starwars-visualguide.com/assets/img/films/4.jpg>
Так же оттуда можно вытащить и другие изображения. Скачивать и хранить внутри
проекта их не нужно, можно просто использовать ссылку.

## Требования

- Использовать React и TypeScript
- Написать тесты для нескольких компонентов и хуков

Исходный код приложения должен быть выложен на GitHub. А также плюсом
будет если будут настроены GitHub Actions для автоматической сборки и деплоя
приложения на GitHub Pages.

## Рекомендации

- Использовать React Router или TankRouter для реализации маршрутизации.
- Для сборки проекта использовать Vite.
