# Інструкції для запуску

## Запуск серверної частини 

1. Вважаючи, що ви знаходитесь у корні проєкту, перейти до теки з серверною частиною додатку: 

   - `cd server`

1. Встановити npm-пакети (один раз, перед першим запуском):

   - `npm i`

1. Запустити серверну частину додатку:

   - `npm start`

## Запуск клієнтської частини

1. Вважаючи, що ви знаходитесь у корні проєкту, перейти до теки з клієнтською частиною додатку: 

   - `cd client`

1. Встановити залежності у форсованому режимі:

   - `npm install --force`

1. ПЕРЕМИКНУТИ версію ноди на 16 за допомогою nvm:

   - `nvm install 16.16.0`

1. Запустити клієнтську версію додатку:

   - `npm start`

- Приложение будет доступно в браузере по адресу [http://localhost:3000](http://localhost:3000) (или на другом свободном порту).

## Примечания

- При работе приложения в dev-режиме понадобятся данные тестовых банковских карт:

  - для оплаты работы с карты buyer`а при создании контеста:
    - Card number: 4111111111111111
    - Expires end: 09/23
    - cvc/cvv: 505
  - для вывода средств на карту creator`а:
    - Card number: 5105105105105100
    - Expires end: 09/23
    - cvc/cvv: 510
###     
- Данные пользователей:

  - для роли buyer (он же customer):
    - email: buyer@gmail.com
    - password: buyer@gmail.com
  - для роли creative (он же creator):
    - email: creative@gmail.com
    - password: creative@gmail.com
