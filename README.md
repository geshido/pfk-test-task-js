Тестовое задание на позицию инженера-программиста (Frontend)
===

Описание задачи
---

Используя данные сайта [openweathermap.org](http://openweathermap.org) реализовать Single Page Application для просмотра погоды в городах.

Интерфейс приложения должен позволять:

* Добавлять и удалять города из списка избранного
* На главной странице показывать текущую температуру в добавленных в избранное городах
* При клике на город показывать почасовой прогноз на ближайшие дни

На каждой странице приложения не должно запрашиваться с GraphQL больше данных, чем необходимо для рендера

Используемые технологии:

* React
* MobX
* UI-framework - [Material UI](https://material-ui.com/)
* GraphQL клиент - [Apollo](https://www.apollographql.com/)

GraphQL прокси
---

https://github.com/MiroYar/my-apollo-openweathermap-server

    http://127.0.0.1:4000/graphql - точка подключения после запуска сервера


Для исследования схемы данных можно использовать extension [ChromeiQL](https://chrome.google.com/webstore/detail/chromeiql/fkkiamalmpiidkljmicmjfbieiclmeij)

Результат оформить в виде репозитория на GitHub.
