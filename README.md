Recipe Scraper
This project is a web scraper designed to fetch and store recipes from kulinaria.ge into a MongoDB database. It uses asynchronous requests to efficiently gather data and the Beautiful Soup library to parse HTML content.

Table of Contents
Features
Installation
Usage
Database Queries
License
Features
Fetches a list of dessert recipes from the specified category on Kulinaria.
Extracts detailed information for each recipe, including:
Ingredients
Preparation steps
Portion size
Subcategory link
Stores the recipes in a MongoDB database.
Provides functions to retrieve statistics from the database, such as:
Average number of ingredients per recipe
Average number of steps to cook
Recipe with the most portions
Author with the most recipes
Installation
Clone the repository.
Install the necessary libraries.
Set up MongoDB on your local machine.
Usage
Run the main script to start the scraping process.
After completion, the script will print various statistics about the recipes collected.
Database Queries
You can use the provided functions to retrieve specific statistics from the MongoDB database, such as average ingredient counts, average cooking steps, and top recipes and authors.

License
This project is licensed under the MIT License - see the LICENSE file for details.

