# Evaluation Task: User Management

## Introduction

In this scenario, you are tasked with creating a comprehensive system designed for children. Parents will use this system to manage their children's accounts.

## Prerequisites

Before you get started, ensure that you have the following technologies and tools installed:

- JavaScript/TypeScript
- Node.js
- Express.js
- Sequelize.js (or any SQL driver of your choice for MySQL or PostgreSQL)
- Jest.js for unit tests and E2E tests (make sure to include tests)
- Docker-Compose for containerizing the backend server and database server

## Task Description

You will be developing a system that caters to children's needs, such as learning children's programming. The system will have two user modes: parent mode and child mode.

**Parent Mode:**

Parents can perform the following actions:
- Register for a parent account
- Log in to their parent account
- Change their password
- Register a new child
- Remove a child using their ID
- Change a child's password
- Assign new courses to a child
- View information about their children

**Child Mode:**

Children can perform the following actions:
- Log in with the account created by their parent
- View their assigned courses
- Change their password

***Notes:***
- Parent passwords must be strong.
- You do not need to create a "courses" table and foreign keys in the child table; just include a course name.
- Usernames for children with the same parent must be unique, so children must log in with their usernames and their parent's username.
- For added security, implement password encryption using cryptographic algorithms such as bcrypt or Argon2. This will help protect user passwords and demonstrate knowledge of encryption algorithms.

## Additional Challenge (Optional)

To further challenge candidates and encourage the use of data structures and algorithms, consider these mandatory tasks:

**Course Enrollment Logic:** Implement a more complex course enrollment system that considers prerequisites. Ensure that children can only enroll in courses if they meet the prerequisites. This may involve using graph data structures and algorithms to manage course dependencies.

## Development Guidelines

Your development task should adhere to the following guidelines:

- Include unit tests for every function you create, as well as E2E tests for every endpoint you create.
- Utilize Docker Compose to set up the API and database.
- Create a "docs" directory that contains OpenAPI documentation.
- Provide end-user documentation in the README.md file.
