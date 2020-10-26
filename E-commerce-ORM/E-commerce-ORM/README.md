# E-commerce-ORM

## Description
Interact with the back-end database to view the E-commerce categories, products, tags and product tags!!  support by Insomnia Core,  can help you create (POST), read (GET), update (PUT), and delete (DELETE) data within your databases.

## Table of Contents 
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)

## Installation 
First varify packages are installed after git has finnished cloning the repo. Then type  "npm init -y", "npm install express sequelize mysql2", and "npm install dotenv" into the command line. Then you must create the database within mysql and in order to login. Next type "mysql -u root -p", and then type "source schema.sql". This will ensure the database is created. You may then type "quit" to exit mysql command line. When all packages are installed, update the .env file with your mysql password. After this you will type "echo '.env' >> .gitignore" into the command line in order to hide the .env file. This  protects your log in credentials!!

## Usage
To first start interacting with the ecommerce_db, first go to the command line in the root directory of the repo,  type "node server.js" or "node server" whichever is preferred. Then open Insomnia Core in oder to interact with GET, PUT, POST and DELETE.

![picture](Screen Shot 2020-10-25 at 8.21.39 PM)
## Link to demo video:
https://drive.google.com/file/d/1g8k4E_7zA_ewqIGy57XAHWxcLMGuLxvs/view
## Credits
UofA Coding Bootcamp starter code

## License
Node.js, MySQL, Heroku, Insomnia Core

## Contributing
To contribute, view the open issues tab within the Github repo and following the listed directions if posted. 
