# E-commerce-Back-End

## Description

This is the backend to an Express.js application that uses Sequelize to interact with a MySQL database. This is used as an E-commerce site would to display and update inventory, for their patrons online.

## Table of Contents

- [Installation](Installation)
- [Usage](usage)
- [Contributors](Contributors)
- [Questions](Questions)

## Installation

To install this application you would need to clone the repository from the following link [E-commerce](https://github.com/veta583518/E-commerce-Back-End). Next you will need to install the dependencies to run this application. - Sequelize, MySQL, and dotenv. You can do so with the following code in the root directory of where you cloned the repository. `npm install`.

[Back to Contents](#table-of-contents)

## Usage

Open the command line in the directory of the application. Run "-npm i sequelize mysql dotenv". This will install the dependencies needed to run this application. You can use the dotenv pakage to use environment variables to store sensitive data, like your MySQL username, password, and database name. Create a new file in the root directory, name it ".env". Add the following to the file and save:

```
DB_NAME='ecommerce_db'
DB_USER=*Your MySQL username*
DB_PW=*Your MySQL password*
```

After this is completed you will need to create the database. You can achieve this by running the following code in the command line to open MySQL shell.
`mysql -u root -p` You will be prompted to enter your MySQL password. Next run `source db/schema.sql`. Verify database was created by running `SHOW DATABASES`. After verified quit MySQL shell. Next you will need to seed the database. In the command line run the code `npm run seed`. To start the server run `npm start`.

[Back to Contents](#table-of-contents)

## Contributors

[Veronica Williams- veta583518](https://github.com/veta583518)

[Back to Contents](#table-of-contents)

## Questions

Feel free to contact me with any questions.

GitHub: [veta583518](https://github.com/veta583518)
Email: [veta583518@gmail.com](mailto:veta583518@gmail.com)

[Back to Contents](#table-of-contents)
