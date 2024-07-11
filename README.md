# Alpha-Next Backend

This project is a basic API for competitor analysis using Node.js, Express, Sequelize, and MySQL. The API allows for the creation and viewing of competitor profiles, which include metrics such as website traffic and top-performing pages.

## Table of Contents

- [Installation](#installation)
- [Database Setup](#database-setup)
- [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [Dependencies](#dependencies)

## Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd alpha_next
2. **Install dependencies:**
    ```bash
    npm install

## Database Setup
 1. **Edit the config file** 
 locate config/config.json file and update with your database credentials
 2. **Run the migration**
npx sequelize-cli db:migrate

## Running the Application
    Start the server:
    ```bash
    npm run start

## API Endpoints
    Documentation: https://documenter.getpostman.com/view/2108248/2sA3e5cT45

## Dependencies

1. **Express:** Web framework for Node.js.
2. **mysql2:** MySQL client for Node.js.
3. **Sequelize:** Promise-based Node.js ORM for MySQL.
4. **Sequelize-cli:** Command-line interface for Sequelize.
5. **Nodemon:** Utility that automatically restarts the server when file changes are detected.
6. **@faker-js/faker:** Library for generating fake data.


