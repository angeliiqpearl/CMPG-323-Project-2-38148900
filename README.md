# CMPG-323-Project-2-38148900
The objective of this project was to develop a CRUD RESTful API for the EcoPower Logistics Company, to assist in the storage of their fundamental logistics data. Numerous methods were created to enhance the API management functionalities. The following is an explanation of the API's content and how it can be used:

The database that we worked with had four entities: Customer, Product, Order, and OrderDetails. 

## The API
Functionality was added to each entity by creating a controller for each one. The functionalities included GET, GET by ID, POST, and DELETE methods. All controllers have these functionalities in place, as well as additional verification methods. If a user attempts to update or delete a nonexistent data entry, an exception will be thrown. Authentication was added to prevent unauthorized access to the API.

## Get started with the API
To run the app service in a browser, the user must append the path '/swagger' to the URL. Otherwise, the app service will not work.
Alternatively, the API can be accessed [here](https://ecopowerapiv1.azurewebsites.net/swagger).

**The following CRUD operations are supported for the Customer Controller:**
- **GET** - Retrieve all customer details.
- **GET by ID** - Retrieve customer details based on the user input for customer id.
- **PUT** - Update existing data for customers.
- **POST** - Insert new customer details.
- **DELETE** - Delete existing entries.

**The following CRUD operations are supported for the Products Controller:**
- **GET** - Retrieve all product details.
- **GET by ID** - Retrieve product details based on user input for product id or order id.
- **PUT** - Update product details.
- **POST** - Insert new product details.
- **DELETE** - Delete existing product entries.

**The following CRUD operations are supported for the Orders Controller:**
- **GET** - Retrieve all orders.
- **GET by ID** - Retrieve order details based on user input for order id or customer id.
- **PUT** - Update order details.
- **POST** - Insert new orders.
- **DELETE** - Delete existing order entries.

**The following CRUD operations are supported for the Order Details Controller:**
- **GET** - Retrieve all order details.
- **GET by ID** - Retrieve order details based on user input for order detail id.
- **PUT** - Update order details.
- **POST** - Insert new order details.
- **DELETE** - Delete existing order detail entries

