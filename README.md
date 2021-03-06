# GameShop Backend
Учебный проект, представляющий собой backend часть онлайн-магазина товаров. В качестве примера взят магазин игровых товаров.

## Стэк
Проект выполнен с целью изучения TypeScript и NestJs, база данных - PostgreSQL, ORMFramework - TypeOrm

## Запуск проекта и просмотр документации
Для запуска проекта необходимо создать PostgreSQL базу данных (например через pgAdmin), указать все необходимые данные в файле .env, скачать все необходимые зависимости и запустить проект (npm run start:dev). Для просмотра API документации перейти на localhost:3000/api/docs

## Кратко о проекте
Реализовано:
1. Продукция (товары), её изменение/добавление/удаление
2. Регистрация и авторизация пользователей через JWT-токены
3. Ограничение доступа по ролям и токену авторизации (Guards)
4. Работа с пользователями и ролями: их изменение/добавление/удаление.

## Скриншот сайта
![Скриншот API документации](https://i.postimg.cc/SRsLvk5h/Swagger.png)
