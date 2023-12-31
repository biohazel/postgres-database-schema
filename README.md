# Restaurant Database Design

## Overview
This project involves the design and implementation of a database schema for managing restaurant data. It includes tables for restaurants, addresses, categories, dishes, reviews, and the relationship between categories and dishes. The database is designed for PostgreSQL.

## Database Schema
The schema consists of the following entities and their relationships:
- **Restaurant**: Main entity containing restaurant details.
- **Address**: Stores addresses and is linked to restaurants.
- **Category**: Defines various categories of dishes.
- **Dish**: Contains details about the dishes offered.
- **Review**: Holds customer reviews for restaurants.
- **Categories_Dishes**: A junction table for the many-to-many relationship between categories and dishes.

### Entity Relationship Diagram
An ERD for this database can be visualized using the `dbdiagram.io` code provided in the `dbdiagram.io cod` file.

## SQL Schema
The SQL schema includes `CREATE TABLE` statements for PostgreSQL, defining the structure for each table, including primary keys, data types, and foreign key relationships.

## Data Insertion
Sample data is provided for each table, demonstrating how to insert records into the database. This includes entries for restaurants, addresses, reviews, categories, dishes, and the categories_dishes junction table.

## Usage
This database can be used for managing restaurant data, including details about dishes, categorization of dishes, storing restaurant addresses, and managing customer reviews. It's suitable for web applications, mobile apps, or any platform that requires a backend to manage restaurant-related data.

## Installation
To set up this database:
1. Install PostgreSQL.
2. Create a new database.
3. Execute the SQL schema statements to create the tables.
4. Insert the sample data using the provided `INSERT` statements.

## Contributing
Contributions, suggestions, and improvements are welcome. Please feel free to fork this repository and submit pull requests.

