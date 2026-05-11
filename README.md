# Patient Management System

A CRUD-based web application for managing patient records.
Built using Java and Maven, the system allows users to create, read, update, and delete patient information through a structured backend architecture.
Overview

This project demonstrates a basic healthcare record management workflow.
It is designed to showcase backend development concepts including layered architecture, database interaction, and RESTful design principles.
Features

    Create new patient records
    View patient details
    Update existing patient information
    Delete patient records
    Structured service and repository layers
    Database persistence

Tech Stack

    Java
    Maven
    Spring Boot (if used)
    JPA / Hibernate (if used)
    MySQL / H2 (adjust accordingly)
    RESTful APIs

Project Structure

text

    patient-management/
    ├── src/
    │   ├── main/
    │   │   ├── java/
    │   │   │   └── com.example.patientmanagement
    │   │   │       ├── controller
    │   │   │       ├── service
    │   │   │       ├── repository
    │   │   │       └── model
    │   │   └── resources/
    │   │       └── application.properties
    └── pom.xml

The project follows a layered architecture:

    Controller – Handles HTTP requests
    Service – Contains business logic
    Repository – Manages database operations
    Model – Defines entity structure

