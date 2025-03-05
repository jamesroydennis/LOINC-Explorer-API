# LOINC Code Explorer API

This project provides a RESTful API for exploring and querying LOINC (Logical Observation Identifiers Names and Codes) data. It simulates core functionalities of RELMA, a tool used for LOINC code management. Built with .NET Core, it showcases efficient data querying, API design, and database optimization techniques.

## Project Description

This API allows users to retrieve and explore LOINC codes, providing detailed information and search capabilities. It aims to demonstrate proficiency in:

* API design and development with .NET Core Web API.
* Database design and optimization for efficient LOINC data retrieval.
* Implementation of search and filtering functionalities.
* Unit testing and API documentation using Swagger/OpenAPI.

## Technologies Used

* .NET Core Web API (C#)
* Entity Framework Core
* SQLite
* xUnit
* Swagger/OpenAPI

## Setup Instructions

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd <project_directory>
    ```
3.  **Restore dependencies:**
    ```bash
    dotnet restore
    ```
4.  **Build the project:**
    ```bash
    dotnet build
    ```
5.  **Run the API:**
    ```bash
    dotnet run
    ```
6.  **Access Swagger/OpenAPI documentation:**
    * Open your browser and navigate to `http://localhost:<port>/swagger` (replace `<port>` with the port number).
7.  **Run Unit Tests:**
    ```bash
    dotnet test
    ```

## LOINC Data

* LOINC data can be obtained from the official LOINC website.
* The project includes a data import process to populate the local database.

## Design Considerations

* Database schema optimized for efficient LOINC code retrieval.
* API endpoints designed for clear and concise data access.
* Implementation of search and filtering capabilities.
* Unit tests to ensure code quality and reliability.

## Interview Preparation

* Be prepared to discuss LOINC data structures and querying strategies.
* Explain database optimization techniques used.
* Discuss the functionality and design of RELMA.
* Demonstrate the API's functionality and unit tests.
