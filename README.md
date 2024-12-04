Food Delivery Backend 

Overview

A backend for managing restaurant menus, handling orders, and tracking order statuses in a food delivery service.

Features

Menu Management: Add and retrieve menu items.

Order Placement: Place orders with multiple items.

Order Tracking: Automatic status updates (Preparing → Out for Delivery → Delivered).

Endpoints

POST /menu: Add or update menu items.

GET /menu: Retrieve menu items.

POST /orders: Place an order.

GET /orders/:id: Get order details.

Requirements

Validation: Ensure positive prices, valid categories, and valid item IDs.

Automation: Use node-cron for status updates.
Setup

Clone the repo:

git clone <repo-url>

cd food-delivery-backend

Install dependencies:

npm install
Start the server:

npm start

Technologies

Node.js

Express.js

node-cron (for automation)
