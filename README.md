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

```json
"dependencies": {
    "body-parser": "^1.20.3",
    "express": "^4.21.1",
    "node-cron": "^3.0.3",
    "mime-types": "~2.1.34",
    "negotiator": "0.6.3"
}
