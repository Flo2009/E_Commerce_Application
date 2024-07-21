
# E_Commerce_DataBase_Application

## Adding Models and Routes 

The application was missing the necessary routes and models. In this project they were added using Sequelize.
The application can be verified using a environment emulation like "Insomnia".


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Badges](#badges)
- [Contributions](#contributions)
- [Questions](#questions)
- [Tests](#tests)

## Installation

Download the application from my GitHub (link below).
Open an integrated terminal is the "dev" folder.
Run "npm install" to install the necassary dependenecies.
Create a .env file within the "dev" folder and enter your DB_NAME,
DB_USER, DB_PASSWORD.
Open an integrated terminal in the "db" folder and connect to your postgres database.
Run the schema.sql.
Return to your "dev" folder terminal and run "node seeds/index.js" to seed your database.
Note: You can adjust the initial seed with your own data if wanted.
Start the server by running "node server.js".
Open Insomnia to test the different routes.



## Usage

Open Insomnia:
Create API request to:

"http://localhost:3001/api/products",
"http://localhost:3001/api/tags",
"http://localhost:3001/api/categories".

You can create GET request, GET to a specific ID by adding the ID nummber
at the end i.e. "http://localhost:3001/api/products/1", POST requests, PUT requests,
DELETE requests. 

You can find the respective "body" variables in the "models". The POST request for the product is described
in the source code.
You can test out the backend app and use it to connect data for your front-end application. 


![Get_All_Products](/src/dev/images/Get_all_products.gif)
![Create_Products](/src/dev/images/Create_products.gif)
![Update_Products](/src/dev/images/Update_product.gif)
![Delete_Products](/src/dev/images/Delete_products.gif)
![Get_All_Category](/src/dev/images/Get_category_all.gif)
![Category_By_ID](/src/dev/images/Category_by_id.gif)
![Update_Category](/src/dev/images/Update_category.gif)
![Post_Delete_Category](/src/dev/images/Post_Delete_Category.gif)
![Tags](/src/dev/images/Get_Tags_all_id.gif)
![Create_Update_Tags](/src/dev/images/Create_Update_Tag.gif)
![Delete_Tags](/src/dev/images/Delete_Tags.gif)

## Credits

https://sequelize.org/,

https://chatgpt.com/

https://stackoverflow.com/

## License

https://opensource.org/license/mit

## Badges

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Contributions

Please contact me through my email (link below) to find out how 
we can collaborate.


## Questions

Flo2009

https://github.com/Flo2009

supersuse81@gmail.com

## Tests

Tests can be found in the video describtion using Insomnia.

https://app.screencastify.com/v3/watch/8ixCJRFYmxOXMRu5QJae


