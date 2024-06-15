# WarehouseAPI
Simple backend for warehouse api


# Warehouse Management API Endpoints

## Inventory Management

### Get Inventory
- **Endpoint:** `GET /inventory`
- **Description:** Retrieve a list of all items in the inventory.

### Update Inventory
- **Endpoint:** `PUT /inventory/{itemId}`
- **Description:** Update the quantity or location of an item in the inventory.

## Barcode Scanning

### Scan Barcode
- **Endpoint:** `POST /barcode/scan`
- **Description:** Scan a barcode to retrieve item details.

## Order Processing

### Create Order
- **Endpoint:** `POST /orders`
- **Description:** Create a new order for items in the warehouse.

### Get Order Status
- **Endpoint:** `GET /orders/{orderId}`
- **Description:** Retrieve the status of an order.

## Warehouse Operations

### Get Warehouse Info
- **Endpoint:** `GET /warehouse`
- **Description:** Retrieve information about the warehouse.

### Update Warehouse Info
- **Endpoint:** `PUT /warehouse`
- **Description:** Update information about the warehouse.