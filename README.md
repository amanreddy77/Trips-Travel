# Trips & Travel Planner
A full-stack application where users can plan trips, visit places, and choose a travel partner if needed based on the same date plans.

## Watch Demo



## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies](#technologies)
- [Schema Diagram](#schema-diagram)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [License](#license)

## Project Overview
The Trips & Travel Planner is a full-stack application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. The application allows users to plan trips, explore various destinations, and connect with travel partners who have similar plans on the same dates. It features user authentication, trip management, and a responsive design for a seamless user experience.

## Features
- **User Authentication and Authorization** (JWT)
- **User Profile Creation and Management**
- **Trip Planning and Management**
- **Destination Exploration**
- **Travel Partner Matching**
- **Commenting and Reviewing Trips**
- **Liking Trips and Comments**
- **Admin and Moderator Dashboards**
- **Email Notifications for Trip Updates**

## Technologies
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js, MongoDB
- **Authentication**: JWT, Passport.js
- **Email Notifications**: Nodemailer
- **File Storage**: Azure Blob Storage
- **Encryption**: Crypto-js



## Getting Started
### Prerequisites
Before running the application, ensure you have the following installed:
- **Node.js**
- **MongoDB** or a MongoDB Atlas account

### Installation
1. **Clone the repository**
    ```bash
    git clone https://github.com/your-username/trips-travel-planner.git
    ```
2. **Go to the project directory and install dependencies for both the client and server**
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```
3. **Create a `.env` file in both the client and server directories and add the environment variables as shown in the `.env.example` files.**

4. **Start the server**
    ```bash
    cd server
    npm start
    ```
5. **Start the client**
    ```bash
    cd client
    npm start
    ```

### Configuration
Run the `setup_tool.sh` script from the server directory with execution permissions. This script is used for configuring admin accounts, setting up initial destinations, and other settings.
```bash
./setup_tool.sh
```

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### contact for help and suggestions
[Email Me](mailto:reddyaman77.ar@gmail.com) 
[github](amanreddy77)
