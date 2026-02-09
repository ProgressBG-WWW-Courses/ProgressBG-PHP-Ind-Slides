# ProgressBG-PHP-Ind Course Structure

This document outlines the structure of the Individual PHP Course.

## Course Agenda
The course is divided into 10 main modules, spanning 50 academic hours.

### Course Intro (2 hours)
- **Goal**: Course intro and goals.
- **Topics**:
  - Get to know each other
  - Student's knowledge & codebase review
  - Course roadmap and goals

### Environment Setup (4 hours)
- **Goal**: Set up the development environment and ensure foundational tools are ready.
- **Topics**:
  - Setting up the development environment (PHP 8+, Apache/Nginx, MySQL).
  - Docker for PHP development.
  - Version Control with Git refresher.
  - Code Editor/IDE setup and useful extensions.

### PHP Modern Fundamentals (8 hours)
- **Goal**: Refresh PHP knowledge with modern best practices (PHP 8+).
- **Topics**:
  - PHP syntax and structure.
  - PHP variables, data types, and operators.
  - Control structures (if/else, switch, loops).
  - Functions and arrays.
  - Object-Oriented Programming (OOP) in PHP.
  - Review of PHP 8+ features (Typed properties, Arrow functions, Match expression).
  - Strict typing and type safety.
  - Modern error handling (Try/Catch/Finally).
  - Namespace and Autoloading.
  - Composer dependency manager.

### Server-side scripting using PHP to generate dynamic content. (4 hours)
- **Goal**: Generate dynamic content using PHP.
- **Topics**:
  - Working with forms and user input.
  - File handling and uploads.
  - Session and cookie management.
  - Working with JSON and XML data.
  - Error handling and debugging techniques.

###  Database & PDO (4 hours)
- **Goal**: Ensure secure and efficient database interaction.
- **Topics**:
  - PDO (PHP Data Objects) best practices.
  - Prepared statements and preventing SQL Injection.
  - Transactions and error handling.
  - Data mapping concepts.

### Zend Framework (Laminas) Fundamentals (8 hours)
- **Goal**: Introduction to the Laminas (formerly Zend Framework) ecosystem.
- **Topics**:
  - Understanding the MVC (Model-View-Controller) flow.
  - Module structure and Configuration management.
  - Service Manager and Dependency Injection (DI).
  - Event Manager: Understanding event-driven architecture.
  - Routing and Controllers.
  - View layer and Layouts.
  - Building and validating with Forms and InputFilters.
  - Data transformation using Hydrators.
  - Database interaction with Laminas\Db and the TableGateway pattern.

### Authentication & Authorization (4 hours)
- **Goal**: Implementing security in Laminas applications.
- **Topics**:
  - Authentication strategies (`laminas-authentication`).
  - Authorization using ACL (`laminas-permissions-acl`) or RBAC.
  - Session management security.

### API Development & Integration (4 hours)
- **Goal**: Building and consuming APIs.
- **Topics**:
  - RESTful API principles.
  - Building API endpoints in Laminas.
  - Content negotiation and JSON handling.
  - Consuming 3rd party APIs with `Laminas\Http\Client` or Guzzle.

### Revolut Virtual POS Integration (6 hours)
- **Goal**: Specific client request - integrating payment processing.
- **Topics**:
  - Revolut Merchant API overview.
  - Creating Orders.
  - Handling Webhooks for payment status updates.
  - Testing with Revolut Sandbox environment.
  - Security considerations (signature verification).
