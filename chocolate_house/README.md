# Chocolate House Application

## Description
A simple CLI application to manage a fictional chocolate house’s seasonal flavor offerings, ingredient inventory, customer flavor suggestions, and allergy concerns.

## Setup and Run Instructions

### Prerequisites
- Python 3.x
- Docker (optional)

### Steps to Run Locally
1. Clone the repository.
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Initialize the database:  
   `python db.py`
4. Run the application:  
   `python main.py`

### Steps to Run with Docker
1. Clone the repository.
2. Build and run the container:  
   `docker-compose up --build`

### Testing
1. Run the unit tests:  
   `python -m unittest discover -s tests`

## SQL Queries
You can find SQL queries in `models.py` for interacting with the database.

## ORM Implementation
Simple SQLite queries have been abstracted using Python classes in `models.py`.

## Docker Commands
- Build Docker container:  
  `docker build -t chocolate_house .`
- Run Docker container:  
  `docker run -it chocolate_house`

