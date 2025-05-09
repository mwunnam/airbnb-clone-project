# Airbnb Clone Project

## Project Overview

This project is a comprehensive simulation of a real-world application development process, focused on building a robust booking platform. It emphasizes backend systems, database design, API development, and application security. Through this project, complex architectures, workflows, and collaborative team dynamics will be better understood.

## Project Goals

1. **User Management:** Implement a secure system for user registration, authentication, and profile management.
2. **Property Management:** Implement features for listing, creating, updating, and retrieving properties.
3. **Booking System:** Develop a mechanism for booking properties and managing booking details.
4. **Review System:** Enable users to leave reviews and ratings of properties.
5. **Data Optimization:** Ensure efficient data retrieval and storage through proper database management.

## Tech Stack

* Django REST Framework
* PostgreSQL
* GraphQL
* Celery
* Redis
* Docker
* CI/CD Pipelines

---

## Team Roles

* **Backend Developer:** Responsible for creating the API endpoints, database schemas, and application logic.

* **Database Administrator:** Manages the database, optimizes it through indexing and proper design.

* **DevOps Engineer:** Builds CI/CD pipelines for continuous integration and delivery, ensuring stability while introducing new features. Works with developers, system administrators, and operations staff to streamline code releases.

* **QA Engineer:** Ensures the application meets both functional and non-functional requirements through testing, writing test scripts, and automating the testing process.

---

## Technology Stack

* **Django:** A robust Python framework for building RESTful APIs, handling authentication, routing, and more.
* **Django REST Framework:** Facilitates the creation of REST APIs.
* **PostgreSQL:** Relational database used for data storage.
* **GraphQL:** Enables efficient and flexible data queries.
* **Celery:** Handles asynchronous tasks such as notifications and payment processing.
* **Redis:** Manages cache and session data.
* **Docker:** Containerization tool to ensure development consistency and facilitate deployment.
* **CI/CD Pipelines:** Automates testing and deployment processes.

## Database Design

### User

* `name`: User's name for identification.
* `status`: Property owner or renter.
* `review`: Reviews made by the user.
* `likes`: Properties liked by the user.
* `booking`: User's booking history.

### Properties

* `name`: Name of the property.
* `location`: Property location.
* `description`: Detailed description of the property.
* `booking`: Booking status.
* `reviews`: Reviews and ratings.

### Reviews

* `name`: Name of the reviewer.
* `message`: Optional message.
* `rating`: Rating level.

### Payments

* `name`: Name of the payer.
* `time`: Time of payment.
* `amount`: Amount paid.
* `status`: Completed or not.

---

## Feature Breakdown

* **User Management:** Users can create accounts and log in. There will also be a distinction between property owners and renters.

* **Property Management:** Allows users to manage property listings, update details, add images, and manage availability.

* **Booking System:** Users can book listed properties and check their availability.

* **Review System:** Enables users to review and rate properties, anonymously or with their identity.

* **Data Optimization:** Fast, smooth, and efficient property search to match user preferences.

---

## API Security

Django provides robust authentication and authorization mechanisms, which will be implemented to ensure system security.

Security is crucial, especially since user data, booking details, and payment information are handled. Without proper security, such data could be vulnerable to fraud and theft.

## CI/CD Pipelines

Continuous Integration and Continuous Delivery ensures a structured and seamless update and deployment process without disrupting the live system.

GitHub will handle CI, while Docker will manage deployment automation.
