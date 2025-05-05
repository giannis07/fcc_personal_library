# 📚 Personal Library Microservice

This is my solution for the [Personal Library project on freeCodeCamp](https://www.freecodecamp.org/learn/quality-assurance/quality-assurance-projects/personal-library).

## 📌 Overview

The Personal Library API allows users to add, update, and view books in their personal library collection. Each book has fields such as title, author, and whether it has been read or not. The app also supports marking books as read and listing all the books in the library.

## 📡 API Endpoints

### `POST /api/books`
Create a new book entry.

**Request body:**
- `title` (required)
- `author` (required)
- `read` (optional, boolean)

### `GET /api/books`
Retrieve all books in the library.

### `PUT /api/books/:id`
Update an existing book entry.

**Request body:**
- `title` (optional)
- `author` (optional)
- `read` (optional, boolean)

### `DELETE /api/books/:id`
Delete a book entry from the library by its ID.

## ⚙️ Technologies Used

- Node.js
- Express.js
- MongoDB
- Mocha & Chai for testing
- dotenv

## 🧪 Running Tests

Run the unit and functional tests:

npm install  
npm test  

Tests include:

- Creating, updating, and deleting books.
- Validating the format of request bodies.

## 🛠️ Getting Started Locally

1. Clone the repository:  
   git clone https://github.com/giannis07/fcc_personal_library.git  
   cd fcc_personal_library  

2. Install dependencies:  
   npm install  

3. Set up environment variables:  
   Create a .env file with MongoDB URI and any other necessary variables.

4. Start the app:  
   npm start  

5. Run the tests:  
   npm test  

The app will be running on http://localhost:3000 by default.

## 💻 Source Code

GitHub Repository: [fcc_personal_library](https://github.com/giannis07/fcc_personal_library)
