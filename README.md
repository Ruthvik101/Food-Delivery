# Food Delivery Backend

## Setup

1. Clone the repo:

    ```bash
    git clone <repository-url>
    ```

2. Navigate into the project directory:

    ```bash
    cd food-delivery-backend
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Start the server:

    ```bash
    npm start
    ```

## Overview

A backend for managing restaurant menus, handling orders, and tracking order statuses in a food delivery service.

## Features

- **Menu Management**: Add and retrieve menu items.
- **Order Placement**: Place orders with multiple items.
- **Order Tracking**: Automatic status updates (Preparing → Out for Delivery → Delivered).

## Endpoints

- `POST /menu`: Add or update menu items.
- `GET /menu`: Retrieve menu items.
- `POST /orders`: Place an order.
- `GET /orders/:id`: Get order details.

## Requirements

- **Validation**: Ensure positive prices, valid categories, and valid item IDs.
- **Automation**: Use `node-cron` for status updates.

## Technologies

- **Node.js**
- **Express.js**
- **node-cron** (for automation)

## Dependencies

- body-parser
- express
- node-cron
- mime-types
- negotiator

## Testing with Postman

Postman is used for testing the routes. You can import the Postman collection to quickly test the available endpoints.

## License

This project is licensed under the MIT License. See the following code for the license:

