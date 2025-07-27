# Web Blog App 🌐
A responsive and stylized web application to manage blog posts. Built using EJS, CSS, Node.js, Express.js, and PostgreSQL.

## Features ✨
- 📝 Add new blog posts
- ✏️ Edit existing posts
- ❌ Delete posts
- 🔍 View posts in a user-friendly interface

# Setup & Configuration ⚙️
Before you begin, ensure that your .env file is configured properly:

```
PG_USER=your_username
PG_HOST=your_host_here
PG_DATABASE=your_database_name_here
PG_PASSWORD=your_database_password_here
PG_PORT="5432"
```
Make sure PGAdmin and PostgreSQL is installed on your machine. For setting up the table in your database:

## Create Table in PostgreSQL 🛠️
1. Open pgAdmin and navigate to your database
2. Enter the following SQL code in the Query Tool to create the posts table:
```
CREATE TABLE posts (
  id SERIAL,
  title VARCHAR(100),
  author VARCHAR(50),
  date_created VARCHAR(10),
  post_body TEXT
);
```

## Running the Application 🚀
To get the app up and running locally:

1. Install the required dependencies:
```
npm install
```
2. Start the application using Nodemon:
```
nodemon index.js
```

The application will be available at: localhost:5432.
