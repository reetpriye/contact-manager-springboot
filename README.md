# Smart Contact Manager

## About the Project
The **Smart Contact Manager** is a web-based application designed to help users manage their contacts efficiently. Built using **Spring Boot**, the project provides a modern, intuitive interface for creating, viewing, editing, and deleting contact information. This application is ideal for personal or small business use cases.

## Features
- **User Authentication**: Secure login and registration for users.
- **Contact Management**:
  - Add, update, and delete contacts.
  - View a list of all your contacts with their details.
- **Responsive Design**: Ensures the application works seamlessly on various devices.
- **Search Functionality**: Quickly find contacts using a search bar.

## Tech Stack
The project leverages the following technologies:

### Backend
- **Java**: Core language used for backend logic.
- **Spring Boot**: Framework for rapid application development.

### Frontend
- **HTML/CSS**: For layout and styling.
- **JavaScript**: Adds interactivity to the user interface.

### Build Tool
- **Maven**: For dependency management and build automation.

## Installation and Setup
Follow these steps to set up the project on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/reetpriye/contact-manager-springboot.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd contact-manager-springboot
   ```

3. **Build the Project**:
   Use Maven to build the project:
   ```bash
   mvn clean install
   ```

4. **Run the Application**:
   Start the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```

5. **Access the Application**:
   Open your web browser and go to:
   ```
   http://localhost:8080
   ```

## Project Structure
```
contact-manager-springboot
|
|-- src
|   |-- main
|   |   |-- java
|   |   |   |-- com.example
|   |   |       |-- Application.java  # Main Spring Boot Application
|   |   |
|   |   |-- resources
|   |       |-- application.properties  # Configuration file
|   |       |-- templates  # HTML templates
|   |       |-- static     # CSS, JavaScript, and images
|
|-- pom.xml  # Maven dependencies
|
|-- README.md  # Project documentation
|
|-- mvnw/mvnw.cmd  # Maven wrapper scripts
```

## Contribution Guidelines
Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a meaningful commit message"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code.

---
Happy coding! 🚀

