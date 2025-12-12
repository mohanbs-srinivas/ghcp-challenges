# API Development and CRUD Operations

---

## 1. Setup Your Development Environment

### Install JDK
- Ensure you have the **Java Development Kit (JDK)** installed (JDK 8 or higher).
- Verify installation:
  - `java -version`
  - `javac -version`  
  These commands should display your installed versions.

### Choose an IDE
- IntelliJ IDEA  
- Visual Studio Code (with **Java support** and **GitHub Copilot** enabled)

### Set Up Maven or Gradle
- Maven and Gradle are tools for build automation and dependency management.
- Install **Maven** or **Gradle** if they are not installed already.
- Create your project as a Maven or Gradle project in your IDE.  
  This will generate the required folder structure.

---

## 2. Create a New Java Project

---

## 3. Add Required Dependencies

Dependencies are external libraries needed for your project.  
They are managed through:
- `pom.xml` (for Maven)
- `build.gradle` (for Gradle)

### Spring Boot
- Add **Spring Boot**, a framework for creating RESTful APIs.
- For Maven: include the `spring-boot-starter-web` dependency in your `pom.xml`.
- Spring Boot provides pre-configured templates to simplify development.

---

## 4. Create the Model Class for the Following JSON

```json
[
    {
        "id": "1",
        "name": "Laptop",
        "description": "A high-performance laptop suitable for gaming and work.",
        "price": 1200.00
    },
    {
        "id": "2",
        "name": "Smartphone",
        "description": "A latest-generation smartphone with a large display and powerful camera.",
        "price": 800.00
    },
    {
        "id": "3",
        "name": "Wireless Headphones",
        "description": "Noise-cancelling wireless headphones with long battery life.",
        "price": 200.00
    },
    {
        "id": "4",
        "name": "Smartwatch",
        "description": "A smartwatch with fitness tracking and customizable watch faces.",
        "price": 150.00
    },
    {
        "id": "5",
        "name": "Tablet",
        "description": "A lightweight tablet with a sharp display, ideal for reading and browsing.",
        "price": 300.00
    }
]
```

## 5. Read and Write to the JSON File



## 6. Perform CRUD Operations Using REST Controller

Use Spring Boot REST annotations:

### Endpoints

* **GET /api/items** – Retrieve all items
* **GET /api/items/{id}** – Retrieve an item by ID
* **POST /api/items** – Create a new item
* **PUT /api/items/{id}** – Update an existing item
* **DELETE /api/items/{id}** – Delete an item


## 7. Add Exception Handling


# Improve UI

1. Display the data in a **table format** on the UI
2. Perform **CRUD operations** from the UI


# Add Test Cases

1. Write test cases for:

   * GET
   * POST
   * PUT
   * DELETE
2. Include **edge cases** and **null condition** handling
3. Run the test cases

