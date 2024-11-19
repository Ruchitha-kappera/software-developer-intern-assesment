# Software Developer Intern Assessment

This repository contains the backend and frontend code for the software developer intern assessment But I Didn't Create Any Frontend so i Kept the Creation Of Table Code in Frontend.

## Project Structure

- `backend/`: Contains the backend code (Java)
- `frontend/`: Contains the frontend code (MySql)

## Backend Setup and Execution

### Requirements:
- JDK 11 or later
- MySQL Database

### Steps to Set Up the Backend:

1. **Clone the Repository**:
   If you haven’t already cloned the repository:
   ```bash
   git clone https://github.com/Ruchitha-Kappera/software-developer-intern-assesment.git

### DATABASE SETUP:-

CREATE DATABASE assignment;
USE assignment;

CREATE TABLE Registration (
    ID INT AUTO_INCREMENT PRIMARY KEY,            
    Name VARCHAR(255) NOT NULL,                   
    Email VARCHAR(255) NOT NULL UNIQUE,          
    DateOfBirth DATE NOT NULL,                    
    PhoneNumber VARCHAR(15),                      
    Address VARCHAR(255),                         
    RegisteredAt TIMESTAMP DEFAULT CURRENT_TIMESTAMP -- Timestamp of when the record was created
);

### RUN THE JAVA APPLICATION
    javac Main.java
    java Main
### FINALLY TEST THE CRUD OPERATIONS


