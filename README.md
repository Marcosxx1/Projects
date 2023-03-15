# Projects
## Repository for courses projects
# Readme
## Description
###  This project is a simple server-side application created using Node.js. The application allows users to view a list of products and their details, which are stored in a JSON file. The application is built using HTML templates and data is dynamically loaded onto the page using JavaScript. The server is created using the built-in HTTP module of Node.js.

## Usage
### To run the application, run the following command:
 
<code>node index.js</code>

## Then navigate to http://localhost:3000/ in your browser to view the homepage.

### The homepage displays an overview of all the products stored in the data.json file. Clicking on a product card takes the user to the product details page. The user can also access the product details page directly by appending ? id=<product_id> to the URL, where <product_id> is the id of the product they wish to view.

### The server also provides an API endpoint at /api which returns all the data in the data.json file.

## Dependencies
### This project requires the following dependencies:

#### fs
#### http
#### url
#### slugify
 
### These can be installed by running the following command:
<code>npm install</code>


## Files
### The project consists of the following files:

1. index.js: The main JavaScript file that creates the server and handles the routing logic.
2. data.json: A JSON file containing the data for the products.
### templates/template-card.html: An HTML template for displaying a single product card.
### templates/template-overview.html: An HTML template for displaying an overview of all the products.
### templates/template-product.html: An HTML template for displaying the details of a single product.
## Credits
### This project was a practice exercise based on the teachings of Jonas Schmedtmann.