Functionalities:
Authentication and Authorization:

User authentication and account creation.
Define different user roles (e.g., regular user, administrator) and associated permissions.
Menu Presentation:

Display the menu with available food options.
Show details about each product: name, description, price, etc.
Order Placement:

Users can select products from the menu and add them to the shopping cart.
Ability to specify quantity for each product.
Adding a delivery address and other necessary details.
Order Processing:

Send placed orders to the processing system.
Generate a unique order number for each placed order.
Updating Order Status:

Update order statuses in real-time.
Order status stages may include: "Placed," "Preparing," "Out for Delivery," "Completed."
Stock Management:

Send notifications and alerts to users to inform them about the status of their orders.
Notifications for order placement confirmation, order status updates, delivery confirmation, etc.
User Account Management:

Users can update their account details, such as delivery address or payment information.
Ability to view order history and their statuses.
Integration with Kafka:

Use Kafka for handling events related to placed orders.
Producer for publishing orders and consumer for updating statuses.

Tools:
- Maven
- Springboot
- MySql
- Kafka
- Lombok
- Hibernate
- Junit
- Postman
- RestApis
- Spring Security
- JWT
