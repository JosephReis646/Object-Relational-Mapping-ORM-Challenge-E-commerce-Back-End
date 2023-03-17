# Project Title: E-commerce API

## Description
This project is an E-commerce API built with Node.js, Express, and Sequelize ORM. The API provides functionality for managing categories, products, and tags in an E-commerce application.

## User Story
As an E-commerce business owner, I want to have an API that allows me to create, read, update, and delete categories, products, and tags so that I can manage my store inventory efficiently and offer a seamless shopping experience to my customers.
## Acceptance Criteria
The API should support CRUD operations for categories, products, and tags.
The API should use Sequelize ORM for managing data models and their associations.
The API should handle errors gracefully and provide clear error messages when needed.
The API should be well-documented, making it easy for other developers to use and maintain.

## Installation
1. Clone this repository to your local machine.  
git clone https://github.com/yourusername/ecommerce-api.git
2. Navigate to the project directory.
3. Install the required dependencies.
4. Create a .env file in the root directory of the project, and add your database credentials.
5. Run the following command to create the necessary database and tables: npm run seed
6.  Start the development server.

## Usage
You can use Insomnia or any other API client to interact with the API. The available endpoints are:

Categories
Get all categories: GET /api/categories
Get a category by ID: GET /api/categories/:id
Create a category: POST /api/categories
Update a category: PUT /api/categories/:id
Delete a category: DELETE /api/categories/:id
Products
Get all products: GET /api/products
Get a product by ID: GET /api/products/:id
Create a product: POST /api/products
Update a product: PUT /api/products/:id
Delete a product: DELETE /api/products/:id
Tags
Get all tags: GET /api/tags
Get a tag by ID: GET /api/tags/:id
Create a tag: POST /api/tags
Update a tag: PUT /api/tags/:id
Delete a tag: DELETE /api/tags/:id
Refer to the project documentation for more information on request and response formats, and any additional parameters that may be required.

Remember to replace the placeholders in the URLs with actual values. For example, replace :id with a specific ID when making a request to a specific category, product, or tag.

Happy coding!
## Contributing
If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request. We welcome contributions of all kinds, including bug fixes, feature requests, and documentation improvements.

## License
This project is licensed under the MIT license. See the LICENSE file for more information.

## Github Repository
https://github.com/JosephReis646/Object-Relational-Mapping-ORM-Challenge-E-commerce-Back-End
## Demo Video
https://drive.google.com/file/d/1RJnCXKLcU1E_0N5ISFLQeIWFnZOwh5rl/view
