#!/bin/bash

# Step 1: Clone the repository
echo "Cloning the repository..."
git clone https://github.com/godricvasa/SpringCrudRestAPI.git
cd SpringCrudRestAPI

# Step 2: Build the project with Maven
echo "Building the project with Maven..."
./mvnw clean install

# Step 3: Run the Spring Boot application
echo "Running the Spring Boot application..."
./mvnw spring-boot:run`
