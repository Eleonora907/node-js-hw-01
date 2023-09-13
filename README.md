# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)
node index.js --action="list"
https://monosnap.com/file/v1mfARhOs9Ff372vOInJk7utu8kaNs

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.
node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
https://monosnap.com/file/GLpNsd1ZDrplKb82xE2KA6Gc7AB0Pw

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту
node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/IsermKNzfzutWFlvP513S8Yt9XLEgD

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.
node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
https://monosnap.com/file/hsuALM7fmDs9TZHFDFGk4NyvVaLaNh