# Shoppy Mart

Shoppy Mart is a Flask application for keeping track of products, locations, and the product movements between the locations.


## The Challenge
Below is the test:  

The goal is to create a web application using Flask framework to manage inventory of a list of products in respective warehouses. Imaging this application will be used in a shop or a warehouse that needs to keep track of various products and various locations

The application should cover following functionalities:
Database Tables:

    Product (product_id)
    Location (location_id)
    ProductMovement (movement_id, timestamp, from_location, to_location, product_id, qty)

Note: Any one, or both of from_location and to_location can be filled. If you want to move things into a location, from_location will be blank, if you want to move things out, then to_location will be blank.
Views:

    Add/Edit/View Product
    Add/Edit/View Location
    Add/Edit/View ProductMovement

Report:

    Balance quantity in each location

Use Cases:

    Create 3/4 Products
    Create 3/4 Locations
    Make ProductMovements
        Move Product A to Location X
        Move Product B to Location X
        Move Product A from Location X to Location Y
        (make 20 such movements)
    Get product balance in each Location in a grid view, with 3 columns: Product, Warehouse, Qty


## Getting Started

To get this application on your local machine, you either clone this repository:  



### Prerequisites

To install the prerequisites for this application, simply run the command below.
Strictly for Python 3, Python 2 may not behave as expected.

```
pip install -r requirements.txt
```

### Running Application

To run this application, navigate to the root folder and run the command below:

```
python run.py
```

You can then view and use the application by opening `localhost:5000` on your browser.
screenshots
https://github.com/rithishrith/flasktask/blob/main/Shoppy%20Mart/Shoppy%20Mart/screenshots/Screenshot%20(1850).png
https://github.com/rithishrith/flasktask/blob/main/Shoppy%20Mart/Shoppy%20Mart/screenshots/Screenshot%20(1851).png
https://github.com/rithishrith/flasktask/blob/main/Shoppy%20Mart/Shoppy%20Mart/screenshots/Screenshot%20(1852).png
https://github.com/rithishrith/flasktask/blob/main/Shoppy%20Mart/Shoppy%20Mart/screenshots/Screenshot%20(1853).png
https://github.com/rithishrith/flasktask/blob/main/Shoppy%20Mart/Shoppy%20Mart/screenshots/Screenshot%20(1854).png
https://github.com/rithishrith/flasktask/blob/main/Shoppy%20Mart/Shoppy%20Mart/screenshots/Screenshot%20(1855).png
https://github.com/rithishrith/flasktask/blob/main/Shoppy%20Mart/Shoppy%20Mart/screenshots/Screenshot%20(1856).png
https://github.com/rithishrith/flasktask/blob/main/Shoppy%20Mart/Shoppy%20Mart/screenshots/Screenshot%20(1857).png
https://github.com/rithishrith/flasktask/blob/main/Shoppy%20Mart/Shoppy%20Mart/screenshots/Screenshot%20(1858).png
https://github.com/rithishrith/flasktask/blob/main/Shoppy%20Mart/Shoppy%20Mart/screenshots/Screenshot%20(1860).png

Thankyou.






