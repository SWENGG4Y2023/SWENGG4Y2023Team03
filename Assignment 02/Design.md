# Design Document for Asset Manager App

## 1. Introduction
The Asset Manager App is a web-based application designed to assist organizations in managing their IT assets effectively. This document provides an overview of the system architecture, database design, user interface design, and integration points.

## 2. System Architecture
The Asset Manager App follows a three-tier architecture consisting of the following layers:

### 2.1 Presentation Layer
The presentation layer is responsible for handling user interactions and displaying the user interface. It includes the following components:
- HTML/CSS for structuring and styling the web pages
- JavaScript for client-side interactivity
- React framework for building dynamic user interfaces

### 2.2 Application Layer
The application layer contains the core logic of the Asset Manager App. It handles business processes and communicates with the database. The components in this layer include:
- RESTful APIs for handling HTTP requests and responses
- Business logic modules for processing data and implementing business rules
- Authentication and authorization modules for user access control

### 2.3 Data Layer
The data layer manages the storage and retrieval of data used by the Asset Manager App. It consists of the following components:
- Relational Database Management System (RDBMS)
- Database schema design to store asset information, user data, and related entities
- Database access layer for interacting with the database and executing SQL queries

## 3. Database Design
The Asset Manager App utilizes a relational database to store and manage data. The database design includes the following entities:

### 3.1 Asset
- Asset ID (Primary Key)
- Asset Name
- Description
- Category
- Status
- Assigned User
- Purchase Date
- Warranty Expiry Date

### 3.2 User
- User ID (Primary Key)
- Name
- Email
- Role
- Password (encrypted)

### 3.3 Category
- Category ID (Primary Key)
- Category Name

### 3.4 Status
- Status ID (Primary Key)
- Status Name

### 3.5 Relationships
- Assets are associated with a Category (many-to-one relationship).
- Assets have a Status (many-to-one relationship).
- Assets can be assigned to a User (many-to-one relationship).

## 4. User Interface Design
The user interface of the Asset Manager App should be intuitive, user-friendly, and responsive. The design principles include:

### 4.1 Navigation
- A consistent and easy-to-use navigation menu should be available across all pages.
- Clear links and buttons should guide users through the application.

### 4.2 Asset Management
- The asset management interface should provide options to view, create, update, and delete assets.
- Filtering and sorting options should be available for efficient asset search.

### 4.3 User Management
- User management features should include user registration, login, and user role assignment.
- Only authorized users should have access to administrative functions.

### 4.4 Reporting
- The reporting interface should allow users to generate customized reports based on various criteria such as asset status, category, or assigned user.

## 5. Integration Points
The Asset Manager App may integrate with the following systems:

### 5.1 Active Directory/LDAP
- Integration with the organization's Active Directory or LDAP server for user authentication and synchronization.

### 5.2 Barcode/QR Code Scanners
- Integration with barcode or QR code scanning devices to facilitate asset identification and management.

### 5.3 Email Notifications
- Integration with an email system to send notifications for asset assignments, warranty expirations, or overdue returns.

## 6. Deployment Architecture
The Asset Manager App can be deployed in a cloud-based environment using the following architecture:

- Application Server: A scalable server infrastructure to host the application and handle HTTP requests.
- Database Server: A separate server to host the relational database and manage data storage and retrieval.
- Load Balancer: Distributes incoming traffic to multiple application servers for load balancing and high availability.
- CDN (Content Delivery Network): Caches static assets for improved performance and global availability.

## 7. Activity Diagrams

### 7.1 Asset Management Process
![Asset Management Process](/Assignment%2002/Diagrams/Activity%20diagram.png)

This activity diagram illustrates the steps involved in the asset management process, including asset creation, updating, and deletion.


This activity diagram showcases the user authentication process, including user registration, login, and role assignment.

## 8. Conclusion
The design document provides a comprehensive overview of the Asset Manager App's architecture, database design, user interface design, integration points, and activity diagrams. It serves as a reference for developers, testers, and other stakeholders involved in the development and deployment of the application.

Please note that the activity diagrams are placeholders, and you should replace the "path/to/asset_management_process.png" and "path/to/user_authentication_process.png" with the actual paths to your respective activity diagrams.
