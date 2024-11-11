# Plantsy

Plantsy is a plant store web app built with React. Users can view, search, add, and mark plants as "sold out". This app uses JSON Server to simulate a backend for plant data and provides an interactive user interface.


## Table of Contents
1. Project Overview
2. Installation
3. Usage
4. Features
5. Technologies Used
6. API Endpoints
7. Contributing
8. License


## Project Overview

Plantsy allows users to:
- View all plants in stock.
- Add new plants to the inventory.
- Mark plants as "sold out".
- Search for plants by name.

The app utilizes React for the frontend and JSON Server for data storage, making it a fully functional web app to simulate an e-commerce platform.


## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/AleoStacy/plantsy.git

# Usage
After the app is running, you can:

View all plants: See the list of plants with their names, prices, and images.
Add new plants: Use the form to add a new plant with a name, image, and price.
Mark plants as "sold out": Toggle the status of plants to "sold out" by clicking a button.
Search for plants: Type the name of a plant in the search bar to filter the list by name.

# Features
Display all available plants.
Add new plants with a form.
Mark plants as "sold out" with a button.
Filter plants by name using a search bar.
Built with React and styled with CSS.

# Technologies Used
React.js: For building the user interface and managing state.
JSON Server: For simulating the backend and storing plant data.
CSS: For styling the app.
JavaScript: For dynamic functionality and handling user events.

# API Endpoints
Add a new plant
- Endpoint: POST /plants
- Request Body:

{
  "name": "Plant Name",
  "image": "http://link-to-image.com",
  "price": 20.99
}
# Mark a plant as "sold out"
- Endpoint: PATCH /plants/:id
- Request Body:

  {
   "sold_out": true
  }
# Delete a plant
Endpoint: DELETE /plants/:id
Example Response:

  {}

# Contributing
Fork the repository.
Create a new branch (git checkout -b feature-name).
Make your changes.
Commit your changes (git commit -am 'Add feature').
Push to your branch (git push origin feature-name).
Open a Pull Request.

# License
