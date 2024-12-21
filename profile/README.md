# AuraMart

AuraMart is a modern, scalable, and secure online shopping platform designed to provide users with a seamless e-commerce experience. Built with a client-server architecture, the platform utilizes React for the frontend, Spring Boot for the backend, and MySQL for data storage. It supports features like product browsing, shopping cart and wishlist management, order processing, inventory management, user authentication, feedback, and offers management.

## Features

### User Features
- Product Browsing: View detailed information on products, categorized for easy access.
- Search and Filter: Advanced search and filter options by category, size, color, price, and brand.
- Cart and Wishlist Management: Add, update, or remove items from the shopping cart and wishlist.
- Order Management: Place orders, track statuses, and view order histories.
- Feedback Submission: Leave product ratings and reviews.
- Secure Payment Gateway: Seamless and secure payment integration.

### Admin Features
Inventory Management: Add, update, or delete product details, and track stock levels.
Order Management: Process and manage orders efficiently.
Offer Management: Create and apply discounts or promotional campaigns.

## System Architecture 

### Client Side (Frontend)
-**Framework**: React
-**Styling**: Tailwind CSS or Material UI (MUI)
-**State Management**: Redux or React Context API
-**HTTP Requests**: Axios

### Server Side (Backend)
-**Framework**: Spring Boot
-**Security**: Spring Security with JWT-based authentication
-**Database Interaction**: Spring Data JPA for ORM functionality

### Database
**Type**: MySQL
**Key Entities**:
**User**: Stores customer and admin details.
**Product**: Tracks product information, stock, and categories.
**Order**: Manages order statuses, payment confirmations, and histories.
**Cart**: Tracks items added by users for purchase.
**Wishlist**: Stores items users intend to buy later.
**Feedback**: Contains product reviews and ratings.

### API Communication
**Protocol**: RESTful APIs
**Format**: JSON

### Containerization
**Tool**: Docker for containerizing the application components.
**Orchestration**: Docker Compose for multi-container manageme

Thank you for visiting AuraMart!
