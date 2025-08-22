# Job Application Tracker

## What is it?
It is a simple and efficient tool designed to help job seekers track and manage job applications. It ensures you stay organized, keep up with deadlines, and never lose track of your progress in the job search process.

## Features
Job Application List: View all applications, their status, and key details in one place.
Add & Edit Applications: Easily add, update, or delete job applications.
Interview Tracker: Keep track of interview schedules and details.
Job Offer Management: Log and manage job offers, including salary and offer dates.
Personal Profile Storage: Store frequently used details for quick access.
Search & Filter: Find job applications quickly using keywords.
Dashboard Overview: Get a summary of your job search progress at a glance 

## Tech Stack
- **Backend:**
  - Java 17
  - Spring Boot 3.4.0
  - Spring Reactive
  - GraphQL
  - PostgreSQL
- **Frontend:**
  - HTML
  - JavaScript
  - React

## Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/job-winner.git
   ```

2. **Install dependencies:**
   - For backend (Java):
     ```bash
     mvn clean install
     ```
   - For frontend (React):
     ```bash
     npm install
     ```

3. **Set up the database:**
   - Run Docker to start PostgreSQL:
     ```bash
     docker-compose up -d
     ```
   - Apply the database schema:
     ```bash
     src/main/resources/schema.sql
     ```

4. **Start the application:**
   - For backend:
     ```bash
     java -jar target/job-winner-0.0.1-SNAPSHOT.jar
     ```
   - For frontend (React):
     ```bash
     npm start
     ```

The application should now be up and running locally at `http://localhost:8081`.
