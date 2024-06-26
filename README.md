﻿

# Simple Calculator

## Project Overview

"Simple Calculator" is a web application developed in Java using the Spring Boot framework. It allows users to perform basic mathematical operations such as addition, subtraction, multiplication, and division. The user interface is straightforward and intuitive, facilitating easy interaction with the application's functionalities.

## Project Assumptions

- **Usability:** The application aims to provide a simple and fast way to perform basic calculations.
- **Intuitiveness:** The user interface is minimalistic and easy to navigate.
- **Extensibility:** The application's codebase is designed to facilitate easy addition of new features and modifications.

## Project Structure

The project consists of the following main components:

- **CalculatorApplication.java:** The main class that launches the Spring Boot server.
- **CalculatorService.java:** A service that performs the mathematical operations.
- **CalculatorController.java:** A REST API controller that handles HTTP requests and delegates them to the service.
- **HomeController.java:** A controller that manages the homepage of the application.
- **index.html:** The HTML file that serves as the front end of the application.
- **styles.css:** A stylesheet that provides styling for the user interface.

## Technologies

- **Java:** Programming language used to write the application logic.
- **Spring Boot:** Framework that simplifies the creation of web applications.
- **HTML/CSS:** Technologies used to create and style the front end of the application.
- **Thymeleaf:** HTML template engine used for rendering pages in Spring Boot.

## How the Application Works

Users visit the homepage of the application, which displays four forms corresponding to the four mathematical operations. After entering two numbers and selecting the appropriate button (e.g., "Add"), the data is sent to the server, processed, and the result is returned and displayed to the user.

### Example of Usage:

1. The user visits the homepage.
2. They enter the numbers 10 and 5 in the addition form.
3. The user clicks the "Add" button.
4. The server processes the request and returns the result of 15.
5. The result is displayed to the user.

## Setup Instructions

To run the application locally:

1. Ensure you have Java JDK and Maven installed on your machine.
2. Clone this repository.
3. Navigate to the root directory of the project via command line.
4. Run (ctrl + F5).
5. Visit `http://localhost:8080` in your web browser to access the application.

