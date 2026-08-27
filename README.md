# KADE Services

This repository is the parent repository for the backend services of the KADE E-Commerce Platform.

It provides access to the individual microservices responsible for the main business functionalities of the application.

## Services

### User Service

[KADE User Service](https://github.com/Dinuka0512/kade_user_service)

Handles user-related operations and user management.

### Product Service

[KADE Product Service](https://github.com/Dinuka0512/kade_product_service)

Handles product-related operations and product management.

### Order Service

[KADE Order Service](https://github.com/Dinuka0512/kade_order_service)

Handles order-related operations and order management.

## Architecture

```text
                 KADE Backend Services
                         |
          +--------------+--------------+
          |              |              |
          v              v              v
     User Service   Product Service   Order Service
