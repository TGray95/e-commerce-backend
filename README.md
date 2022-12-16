# E-commerce Backend

  

  ## Table of Contents

  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Questions](#questions)
  ## Description

  This application allows the user to manipulate a database consisting of products, categories, and tags using api routes. Products, categories, and tags may be retrieved, added, deleted, or edited through api fetch requests.
  ## Installation

  Navigate to the application directory and sign in to mysql, then run 'source db/schema.sql' to create the database. Exit mysql, then run 'npm i', 'npm run seed', then 'npm start' to install dependencies, seed the database, and initialize the server.
  ## Usage

  Once server is running, an api tool such as insomnia.rest may be used to view and edit the database. GET requests to the /api/products/ route will retrieve all product information. GET requests to the /api/products/{id} route will retrieve a product that has the id matching {id}. POST requests to the /api/products/ route will create a new product based on the content of the body of the request. PUT requests to the /api/products/{id} route will edit an existing product based on the request body where the product id matches {id}. DELETE requests to the api/products/{id} route will delete the product with the corresponding id. These routes apply to categories and tags as well.
  
  ## Contributing

  N/A
  ## Tests

  N/A
  ## Questions

  [GitHub](https://github.com/TGray95) <br>
  Send any questions to gray.tony95@gmail.com
