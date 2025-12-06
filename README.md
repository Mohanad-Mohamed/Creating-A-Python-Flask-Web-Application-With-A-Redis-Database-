# Project 3 - Simple Web Application

# Project Architecture

<img width="1365" height="479" alt="Architecture" src="https://github.com/user-attachments/assets/c3ed4da3-ab29-4e78-8adb-ccf379d89be1" />

## Description
This project is a simple web application built using Flask and Redis. It demonstrates how to create a basic web app that counts the number of times it has been accessed.

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Project 3
   ```
2. Install the required packages:
   ```bash
   pip install -r src/requirements.txt
   ```

## Running the Application
To run the application using Docker:
1. Build the Docker image:
   ```bash
   docker-compose build
   ```
2. Start the application:
   ```bash
   docker-compose up -d
   ```
3. Access the application at `http://localhost:9000`

## Requirements
- Python 3.7
- Flask
- Redis
