Job Application Tracker

Description
It is a free tool designed to help job seekers keep track of their applications and interviews. It provides an easy-to-use interface for managing job details, including company name, role, application status, and more, all in one place. It also helps organize interview schedules and job offers, making the job search process more efficient and less stressful.

Key Features

Job Application List: View all your applications, their current status, and key details in one place.
Add New Application: Quickly add new job applications via an intuitive form.
Edit Existing Application: Update the status or other details of your job applications.
Delete Applications: Remove applications you no longer need or are not pursuing.
Interview Management: Track interview schedules and details, including company and position.
Job Offer Tracker: Keep track of any offers you've received, with details like salary and offer date.
Personal Profile: Store your personal information such as LinkedIn URL, which can be easily copied when needed.
Search & Filter: Use keywords to search for applications, companies, or specific job details quickly.
Overview: Get an at-a-glance view of how many interviews or offers you currently have.
Tech Stack

Backend:
Java 17
Spring Boot 3.4.0
Spring Reactive
GraphQL
PostgreSQL
Frontend:
HTML 
JavaScript 
React

Setup Instructions

Set Up PostgreSQL Database
First, use Docker to bring up the PostgreSQL database:
docker-compose up -d
Then, create the database schema using:
src/main/resources/schema.sql
Access the app at: http://localhost:8081/
Default login credentials:

Username: postgres
Password: example
Build the Application
Use Maven to build the Java application:
mvn clean install

Run the Application
After building, run the application using:
java -jar target/job-winner-0.0.1-SNAPSHOT.jar

Using H2 Database (Initial Setup)
To run the application with an H2 database for the first time:
java -jar target/job-winner-0.0.1-SNAPSHOT.jar --spring.profiles.active=h2 --spring.sql.init.mode=always

Running the Application with Existing Database
If the database already exists, run the application with:
java -jar target/job-winner-0.0.1-SNAPSHOT.jar --spring.profiles.active=h2
