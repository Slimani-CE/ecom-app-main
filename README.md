# Ecom-App
## Table of Contents

- [Microservices Overview](#microservices-overview)
  - [Project Architecture](#project-architecture)
  - [🔌 Configuration Service Module](#-configuration-service-module)
  - [🌐 Gateway Service Module](#-gateway-service-module)
  - [👥 Customer Service Module](#-customer-service-module)
  - [📦 Inventory Service Module](#-inventory-service-module)
  - [🛒 Order Service Module](#-order-service-module)
  - [📁 Config-Repo](#-config-repo)
  - [🖥️ Ecom-App (Front-end Angular)](#️-ecom-app-front-end-angular)
- [Screenshots](#screenshots)

## Microservices Overview

Ecom-App is a modular and distributed application consisting of several microservices, each responsible for a specific aspect of the e-commerce platform. These microservices work together to provide a seamless and efficient shopping experience.

### Project Architecture
![Architecture](assets/architecture.png)

### 🔌 Configuration Service Module

The **Configuration Service Module** is at the heart of our application. It serves as a centralized configuration manager, allowing us to manage configurations for all other microservices. This module ensures that each service has the correct configuration settings, promoting consistency and scalability.

[Learn more about Configuration Service Module](https://github.com/Slimani-CE/ecom-app-config-service)

### 🌐 Gateway Service Module

The **Gateway Service Module** acts as the front door to our application. It manages incoming requests, routes them to the appropriate microservices, and ensures global CORS (Cross-Origin Resource Sharing) configuration. This module is crucial for handling external and internal requests.

[Learn more about Gateway Service Module](https://github.com/Slimani-CE/ecom-app-gateway-service)

### 👥 Customer Service Module

The **Customer Service Module** is responsible for managing customer-related operations within our e-commerce platform. It handles customer data, including customer creation, retrieval, and updates. This module plays a vital role in providing a personalized experience to our customers.

[Learn more about Customer Service Module](https://github.com/Slimani-CE/ecom-app-customer-service)

### 📦 Inventory Service Module

The **Inventory Service Module** manages the inventory of products in our e-commerce platform. It is responsible for tracking product data, availability, and storage. This module ensures that product information is up to date and that customers can browse and purchase available items.

[Learn more about Inventory Service Module](https://github.com/Slimani-CE/ecom-app-inventory-service)

### 🛒 Order Service Module

The **Order Service Module** is tasked with managing customer orders. It handles the entire order lifecycle, including order creation, tracking, and fulfillment. This module ensures that customers can place orders, and we can efficiently fulfill them.

[Learn more about Order Service Module](https://github.com/Slimani-CE/ecom-app-order-service)

### 📁 Config-Repo

The **Config-Repo** module is a central repository for service configuration. It contains configuration data used by the microservices, ensuring that they have the necessary settings to operate effectively. It complements the Configuration Service Module.

[Learn more about Config-Repo](https://github.com/Slimani-CE/ecom-app-config-repo)

### 🖥️ Ecom-App (Front-end Angular)

The **Ecom-App** is the front-end user interface for our e-commerce platform. Built using Angular, it connects to and interacts with the microservices to provide customers with an engaging shopping experience. It's the face of our platform, allowing users to browse products, place orders, and manage their accounts.

[Learn more about Ecom-App](https://github.com/Slimani-CE/ecom-app-front-end)

## Screenshots

Here are some screenshots of the Ecom-App front-end module:

![Ecom-App Screenshot 1](/assets/screenshot1.png)
*Caption: Products page.*

![Ecom-App Screenshot 2](/assets/screenshot2.png)
*Caption: Customers page.*

![Ecom-App Screenshot 3](/assets/screenshot3.png)
*Caption: Customer orders page*

![Ecom-App Screenshot 4](/assets/screenshot4.png)
*Caption: Order details page*

![Ecom-App Screenshot 5](/assets/screenshot5.png)
*Caption: Dark theme*


