# goit-nodejs-hw-01

A simple Node.js project for contact management.

## Dependencies

This project utilizes the following npm packages:

- **nanoid**: For generating unique identifiers.
- **commander**: For handling

## Usage

Display All Contacts
Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table):

//https://monosnap.com/file/cpwK7RY6QBtxZnZ3Ueeb2U8TILDSoL

```node index.js --action="list"

```

Get Contact by ID
Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує:

//https://monosnap.com/file/3eB6dBlNcB1wRZ9TFoqBP35KchTtvz

```node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6

```

Add New Contact
Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту:

//https://monosnap.com/file/j9jEfyseLZmy4cFZmnQQ13Vd6Duha3

```
node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22

```

Remove Contact by ID
Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує:

//https://monosnap.com/file/bxpjpzFOtnf1furfgulDrA17flXLyn

```
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH

```
