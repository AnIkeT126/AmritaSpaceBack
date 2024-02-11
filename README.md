# AmritaSpaceBack

AmritaSpaceBack is a backend application for the AmritaSpace project, aimed at providing APIs for managing space-related data. It utilizes MongoDB as the database system for storing and retrieving data.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [API Reference](#api-reference)
6. [Database](#database)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

AmritaSpaceBack is a backend server built using [Node.js](https://nodejs.org/) and [Express](https://expressjs.com/), designed to support the AmritaSpace project. It serves as the backend for managing space-related data and provides RESTful APIs for various functionalities.

## Features

- **User Authentication**: Secure user authentication using JSON Web Tokens (JWT).
- **Data Management**: CRUD operations for managing space-related data such as satellites, missions, and launches.
- **Authorization**: Role-based access control (RBAC) to restrict access to certain routes.
- **Scalability**: Designed to be scalable and easily extendable to accommodate future requirements.

## Installation

To run AmritaSpaceBack locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/AnIkeT126/AmritaSpaceBack.git

2. Navigate to the project directory:

   ```bash
   cd AmritaSpaceBack


3. Install dependencies:

   ```bash
   npm install


4. Set up environment variables:

   Create a .env file in the root directory and configure the following variables:

      ```bash
     
      PORT=3000
      MONGODB_URI=your_mongodb_uri
      JWT_SECRET=your_jwt_secret

5. Start the server:

   ```bash

   npm start





