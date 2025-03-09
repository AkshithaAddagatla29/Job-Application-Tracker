# Job Application Tracker

## What is it?
Job Winner is a simple and efficient tool designed to help you track and manage job applications. It helps you stay organized and ensures you never miss important deadlines. Key features include:

- Manage job applications by status (viewed, under consideration, etc.)
- Track application deadlines to stay on top of your job search
- Update application statuses and manage application letters
- Organize postings with custom columns and take notes
- Automate folder creation for new applications

## Preview
- View job listings  
- Update application statuses  
- Manage deadlines  

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
