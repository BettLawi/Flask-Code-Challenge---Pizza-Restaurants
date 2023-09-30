# Flask-Code-Challenge---Pizza-Restaurants
The Pizza Restaurants is a Flask-based web application that provides functionality for managing pizza restaurants and their menus. It allows users to view restaurants, pizzas, create new pizza entries, and delete restaurants along with their associated menu items.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Routes](#routes)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Contributions](#contributions)

## Installation
```
# Clone the repo
$ git clone <repo link>
```
```
# Navigate to directory
$ cd <directory name>
```
```
# Install dependencies and create virtual environment
$ pipenv install & pipenv shell
```

 ## Usage
 ```
 # Run the application
 $ flask run 
 ```
 # Access the API
 You can use tools like Postman or a web browser to interact with the API endpoints as described in the [Routes](#routes) section below.

## Routes
- GET`restaurants`: Gets a list of all restaurants
- GET `/restaurants/<id>`: Get details of a specific restaurant by ID.
- DELETE `/restaurants/<id>`: Delete a restaurant by ID along with its menu items.
- GET `/pizzas`: Get a list of all pizzas.
- POST `/restaurant_pizzas`: Create a new menu item associated with an existing restaurant and pizza.


# Technologies used
- Python
- Flask

# License
[MIT](LICENSE)

# Contributions
Authored by Lawi Bett


