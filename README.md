# 🛠️ Rest API Example

This project is a **simple Java Spring Boot REST API example** designed
for students and beginners to understand how REST APIs work.

A REST API allows clients (like web or mobile apps) to communicate with
the server using **HTTP requests** such as GET, POST, PUT, DELETE. This
project shows how to build and structure a RESTful backend easily.

------------------------------------------------------------------------

## 🚀 What You'll Learn

By exploring this project, you will learn:

-   🔹 How to build a REST API using **Spring Boot**
-   🔹 How to implement **CRUD operations**
-   🔹 How HTTP methods (GET, POST, PUT, DELETE) work
-   🔹 How to structure a backend application
-   🔹 How to interact with the API using tools like **Postman**

------------------------------------------------------------------------

## 🧠 What is REST API?

**REST (Representational State Transfer)** is an architectural style for
building web APIs.

  HTTP Method   Action
  ------------- ----------------------
  GET           Retrieve data
  POST          Create new data
  PUT           Update existing data
  DELETE        Remove data

This example project helps you understand these basics in practice.

------------------------------------------------------------------------

## SCREENSHOTS
### POSTMAN

a. READ DATA (GET)
<img width="608" height="758" alt="image" src="https://github.com/user-attachments/assets/009ddce0-2e4f-4e00-a477-3449b71bc280" />


b. ADD DATA (POST)
<img width="502" height="821" alt="image" src="https://github.com/user-attachments/assets/a3df3826-2f0d-45e6-a959-2189217fbc3e" />

<img width="524" height="820" alt="image" src="https://github.com/user-attachments/assets/d9e809d1-247f-4d7b-bfad-20f7d7b0488b" />

<img width="567" height="839" alt="image" src="https://github.com/user-attachments/assets/8fcafd68-62ba-4049-8620-c6d87735156b" />


c. DELETE
DELETEING -:
<img width="668" height="756" alt="image" src="https://github.com/user-attachments/assets/f2f553f8-bb80-4751-bbde-bf6d7e5aadde" />



### CODE IN ECLLIPSE
<img width="826" height="571" alt="image" src="https://github.com/user-attachments/assets/db369e5c-bc00-49c9-8e24-933977168be1" />



### RUNNING PROJECT
<img width="1078" height="294" alt="image" src="https://github.com/user-attachments/assets/614973d0-3088-416a-bd15-2dda562daf34" />


<img width="834" height="465" alt="image" src="https://github.com/user-attachments/assets/2c547ba9-5e80-478d-826d-e6bb5ac43213" />

<img width="833" height="590" alt="image" src="https://github.com/user-attachments/assets/07a58688-05a3-4798-b9e0-26332bb3e0aa" />

<img width="831" height="198" alt="image" src="https://github.com/user-attachments/assets/083f687e-134b-4083-9dec-3b7b8ff0165e" />

## 🗂️ Project Structure

A typical Spring Boot REST API project looks like this:

    src/main/java/...  
    ├── controller/      # API endpoints
    ├── model/           # Data models/entities
    ├── repository/      # Database access
    ├── service/         # Business logic
    └── Application.java # Main application

Screenshot (Ecllipse) -:

<img width="336" height="449" alt="image" src="https://github.com/user-attachments/assets/59f86082-38fb-4ee6-acad-c829c83b1873" />



------------------------------------------------------------------------

## 🛠️ How to Run the Project

### 1️⃣ Clone the repository

``` bash
git clone https://github.com/agxmm01/Rest-API-example.git
cd Rest-API-example
```

### 2️⃣ Build & Run

Just go to RestExampleApplication.java and click on run

The backend server will start on:

👉 http://localhost:8080

------------------------------------------------------------------------

## 📍 How to Test the API

You can test the REST API using tools like:

-   Postman
-   cURL
-   VSCode REST Client

Try sending these requests:

  Request                             Description
  ---------------------------         -------------
  GET /students/yourEndpoint           Read data
  POST /students/yourEndpoint          Create data
  PUT /students/yourEndpoint/{id}      Update data
  DELETE /students/yourEndpoint/{id}   Delete data

Replace `/yourEndpoint` with the actual api defined in the code(in controller class). 

------------------------------------------------------------------------

## 🎯 Why This is Useful

This project is perfect for beginners to understand backend development
with Java and Spring Boot. It is simple, hands‑on, and practical for
real‑world learning.

------------------------------------------------------------------------

## 👨‍💻 Author

Developed by **Aaryan Gill**
