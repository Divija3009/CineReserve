# Overview
CineReserve is a full-stack Movie Ticket Booking System that enables users to browse, book, and manage movie tickets online.
It is built using Flask, PostgreSQL, and RESTful APIs, providing both user and admin functionalities such as:
1. Searching and booking movies across multiple theaters
2. Managing user accounts, reward points, and memberships
3. Handling payments and transaction histories
4. Adding or updating movies, locations, theaters, and showtimes

# Key Features
User Authentication – Sign in, register, and manage user profiles
Movie Booking System – View current and upcoming movies, select multiplex and seats
Payment Gateway Simulation – Save cards, manage payments, and use reward points
Admin Dashboard – Add or update movies, theaters, and showtimes dynamically
Flask REST APIs – Modular backend with endpoint-based architecture
PostgreSQL Integration – Persistent data management via configuration file

# Installation & Setup
## Clone Repository
```
git clone https://github.com/Divija3009/CineReserve.git
```
## Install Dependencies
```
pip install -r requirements.txt
```
## Configure Database
Edit the config.json file and update your PostgreSQL credentials:
```
{
  "postgres": {
    "host": "",
    "port": 5432,
    "dbname": "",
    "user": "",
    "password": ""
  }
}
```
## Run the Application
Run backend and frontend concurrently
```
python concurrent1.py
```
