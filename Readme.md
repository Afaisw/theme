# Wallet Dashboard Web Application

The **Wallet Dashboard** is a web-based application that provides an interactive display of customer data and their transaction history. This application is built using Node.js as the backend server, with JSON Server simulating a database, and Pushstate-server serving as the frontend server. Axios is used for data communication.

## Installation

Before using the Wallet Dashboard application, make sure you have Node.js installed on your device. To get started, follow these steps:

1. Open your terminal or command prompt.

2. Navigate to project directory:
   ```bash
   cd wallet-dashboard
   ```

3. Install project dependencies using npm :
    ```bash
    npm install
    ```

## Usage
After successfully installing the project dependencies, follow these steps to run the application:

1. Open a terminal or command prompt.

2. Start the JSON Server as the backend server:
    ```bash
    npm run watch
    ```
    This command initiates the JSON Server, creating a simulated database with customer and transaction data.

3. Open a new terminal or command prompt to have two instances running simultaneously.

4. Start the frontend server:
    ```bash
    npm run start
    ```
    This command launches the Pushstate-server to serve the frontend of your Wallet Dashboard web application.

5. Open your web browser and navigate to http://localhost:3000 to access the Wallet Dashboard, where you can interact with the displayed data.

## Features

**Customer Data** : View detailed customer information, including names, wallet balances, and transaction history.
**Transaction Insights**: Analyze transaction records, including descriptions, amounts, types, and dates.