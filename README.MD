# Todo

# High-Level Architecture

### Backend (Node.js)
    - REST API Endpoints:
        - POST /companies: Register a company. (done)
        - POST /workstations: Register a workstation. (done)
        - POST /notifications: Create a notification. (done)
    - Database:
        - Store company, workstation, and notification details. (done)
    - Push Notifications:
        - Implement a custom push notification service. (done)
### Frontend (Angular)
    - Components:
        - Company Registration Form
        - Workstation Registration Form
        - Notification Dashboard
    - Services:
        - Interact with backend endpoints.
        - Mobile App (React Native & Expo)
    - Screens:
        - Company Registration Screen
        - Workstation Registration Screen
        - Notification Display Screen
    - Notification Service:
        - Use Notifee to handle push notifications.
# Detailed Breakdown
### Backend (Node.js)
    - Company Registration:
        - Endpoint to register a company using the company code. (done)
        - Store company details in a database. (done)
    - Workstation Registration:
        - Endpoint to register a workstation. (done)
        - Each workstation will be associated with a company.
    - Notification Management:
        - Endpoint to create a notification. (done)
        - Notifications will include the origin (workstation). (done)
        - Implement a custom push notification service. (done)
    - Communication with Proprietary API:
        - Handle integration and communication with the proprietary Node.js API. (done)
    - Authentication:
        - Simple authentication mechanism using only the company code.
### Frontend (Angular)
    - Company Registration UI:
        - Form to input and register company details.
    - Notification Management UI:
        - Dashboard to view and manage notifications.
        - Interface to trigger notifications manually if required.
# Mobile App (React Native & Expo)
    - Company Registration:
        - Interface to register companies.
    - Workstation Registration:
        - Interface to register workstations.
    - Notification Handling:
     - Receive and display notifications using Notifee. (done with Expo notifications)
     - Ensure notifications include the origin (workstation). (done)