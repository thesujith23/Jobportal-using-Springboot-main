#  Job Portal using Spring Boot & React

This is a full-stack web application for a job portal, built with a **Spring Boot** backend and a **React** frontend. The platform allows users to search for jobs, view company profiles, and apply for positions. It serves as a comprehensive solution for both job seekers and employers.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

---

## 📋 Table of Contents

- [About The Project](#-about-the-project)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Contact](#-contact)

---

## 📖 About The Project

The Job Portal is designed to connect job seekers with employers. It provides a platform where companies can post job openings and review applicants, while job seekers can search for jobs, filter them by various criteria, and submit their applications. The project uses a modern technology stack with a robust Java-based backend and a dynamic, component-based frontend.



---

## ✨ Key Features

-   **User Authentication:** Secure registration and login for job seekers and employers.
-   **Job Search & Filtering:** A powerful search functionality to find jobs by title, location, or company.
-   **Company Profiles:** Companies can create and manage their profiles with descriptions and a list of open positions.
-   **Job Posting:** Employers can post, edit, and delete job listings.
-   **Application System:** Job seekers can apply for jobs directly through the portal.
-   **RESTful API:** A well-structured backend API to manage all application data.

---

## 💻 Tech Stack

The project is divided into a backend service and a frontend application.

### Backend

-   **Java 17:** The core programming language.
-   **Spring Boot:** Framework for building the RESTful API.
-   **Spring Security:** For handling authentication and authorization.
-   **Spring Data JPA:** For data persistence and database interaction.
-   **PostgreSQL:** The relational database for storing application data.
-   **Maven:** For project and dependency management.

### Frontend

-   **React:** A JavaScript library for building the user interface.
-   **CSS3:** For styling the application.

---

## 🚀 Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

-   JDK 17 or later
-   Maven
-   Node.js and npm
-   PostgreSQL database

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/thesujith23/Jobportal-using-Springboot-main.git](https://github.com/thesujith23/Jobportal-using-Springboot-main.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Jobportal-using-Springboot-main
    ```
3.  **Configure the Backend:**
    -   Open the `src/main/resources/application.properties` file.
    -   Update the `spring.datasource.url`, `spring.datasource.username`, and `spring.datasource.password` properties to match your PostgreSQL database configuration.
    -   Build the project using Maven:
        ```bash
        mvn clean install
        ```
    -   Run the Spring Boot application:
        ```bash
        mvn spring-boot:run
        ```
    -   The backend will start on `http://localhost:8080`.

4.  **Configure the Frontend:**
    -   The React frontend code is located within the project. You would typically run it in a separate terminal.
    -   (Assuming a standard React setup) Navigate to the frontend directory:
        ```bash
        cd path/to/your/react-app
        ```
    -   Install dependencies:
        ```bash
        npm install
        ```
    -   Start the development server:
        ```bash
        npm start
        ```
    -   The frontend will be available at `http://localhost:3000`.

---

## 📂 Project Structure

The repository contains the complete Spring Boot application. The React frontend code is typically managed within this structure or in a separate repository.

-   `src/main/java`: Contains the main Java source code (controllers, services, repositories, models).
-   `src/main/resources`: Includes configuration files (`application.properties`) and static assets.
-   `pom.xml`: The Maven project object model file, defining dependencies and build settings.

---

## 📧 Contact

Sujith - [@thesujith23](https://github.com/thesujith23)

Project Link: [https://github.com/thesujith23/Jobportal-using-Springboot-main](https://github.com/thesujith23/Jobportal-using-Springboot-main)
