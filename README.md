
# PyObelisk

## Overview

PyObelisk is an advanced network automation and operational management portal designed to streamline and enhance the handling of network-related tasks. 

## Key Features

### Dynamic User Interface
- **Dynamic Survey Forms**: Leveraging JavaScript and JSON schemas to create customizable input forms for various automated workflows.
- **Real-time Updates**: WebSocket implementation provides users with real-time status updates on their jobs and tasks.

### Comprehensive Backend Services
- **Python Environment Management**: Handles identification of Python environments, capturing details such as Python version and OS type. Enables the creation of sandboxed environments for secure script execution.
- **Job Execution and Monitoring**: Facilitates the submission, scheduling, and real-time monitoring of jobs. Includes features for managing outputs and logging.
- **User Authentication**: Implements secure JWT-based authentication, session management, and LDAP integration for user verification.
- **File Handling**: Supports uploading and management of files and packages necessary for job execution, utilizing Base64 encoding for secure transfer.

### Security and Administration
- **Secure Authentication**: Protects sensitive actions with session-based authentication and role checks.
- **SSL/TLS Support**: Ensures all user interactions are over secure connections.
- **Health Check API**: Provides a simple API endpoint for monitoring the health and status of the service.

## Key Libraries and Technologies

- **FastAPI**: Utilized for building high-performance, asynchronous REST APIs.
- **Starlette**: For WebSocket support and session management in an async environment.
- **SQLAlchemy**: For robust database management and operations.
- **PyJWT**: For generating and validating JWT tokens.
- **Uvicorn**: An ASGI server for serving Python applications in production.

## Intent and Usage

PyObelisk aims to bridge the gap between technical network automation tasks and operational management, providing a central interface for streamlined operations. It is particularly suited for environments where network automation is critical to operational efficiency and security.
