# E-commerce Backend

## Description

This is a back-end application for an e-commerce site that uses Express.js API and Sequelize to interact with a MySQL database.

## Installation

To install the necessary dependencies, run the following command:

npm install


## Usage

Before using the application, the database needs to be created. Run the `schema.sql` file in MySQL shell:

source db/schema.sql


Then, you can seed the database by running:


Then, you can seed the database by running:

npm run seed


Finally, to start the server, run:

npm start


## Endpoints

### Products

- GET all products: `/api/products`
- GET a single product: `/api/products/:id`
- POST a new product: `/api/products`
- PUT (update) a product: `/api/products/:id`
- DELETE a product: `/api/products/:id`

### Categories

- GET all categories: `/api/categories`
- GET a single category: `/api/categories/:id`
- POST a new category: `/api/categories`
- PUT (update) a category: `/api/categories/:id`
- DELETE a category: `/api/categories/:id`

### Tags

- GET all tags: `/api/tags`
- GET a single tag: `/api/tags/:id`
- POST a new tag: `/api/tags`
- PUT (update) a tag: `/api/tags/:id`
- DELETE a tag: `/api/tags/:id`

## Example

Here is a video demonstration: [Click Here!]()

## Questions

If you have any questions about the repo, open an issue or contact me directly at [christopherflores9312@gmail.com](mailto:christopherflores9312@gmail.com). You can find more of my work at [christopherflores9312](https://github.com/christopherflores9312/).
