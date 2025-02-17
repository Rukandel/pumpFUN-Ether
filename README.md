# Клон pump fun 
Клон сделан в рамках проектной работы по предмету интернет-программирование. За пример для "подражания" взят сервис https://pump.fun/ работающий на Solana. Задачей работы было разобраться в коде сервиса и перенести его на Etherium, учитвая особенности и различия архитектур и ЯП. Клиентская часть выполнена в минимальном функционале, акцент сделан на смартах и работе с фреймворками на бэке.
## Технлогический стек

- Solidity (Смарты и тесты)
- Javascript  & Next JS (бэк и тесты)
- [Hardhat](https://hardhat.org/) (Фрэймворк для работы с Эфиром)
- [Ethers.js](https://docs.ethers.io/v5/) (Документация по работе с блокчейном)
- [Next.js](https://nextjs.org/) (Фрэймворк фронта)



## Установка
### 1. Скачать репозиторий

### 2. Установить зависимости:
`$ npm install`

### 3. Запустить тесты
`$ npx hardhat test`

### 4. Запуск ноды 
`$ npx hardhat node`

### 5. Задеплоить
In a separate terminal execute:

`$ npx hardhat ignition deploy ignition/modules/Factory.js --network localhost`

If you have previously deployed you may want to append `--reset` at the end:

`$ npx hardhat ignition deploy ignition/modules/Factory.js --network localhost --reset`

### 6. Запустить клиент
`$ npm run dev`
