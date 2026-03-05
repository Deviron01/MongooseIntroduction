# MongooseIntroduction


# 📝 Assignment: Build a Book Inventory System with Mongoose

**Objective**

- Create a Node.js application that connects to MongoDB using Mongoose and performs basic CRUD operations on a book collection.

**Prerequisites**

- VS Code installed
- Node.js installed
- MongoDB installed locally or a MongoDB Atlas account

**Task 1: Project Setup**

- Create a new folder named book-inventory
-  Open it in VS Code
-   Initialize a Node.js project (npm init -y)
-   Install required dependencies: mongoose and dotenv
-  Create the following folder structure:


**Task 2: Database Connection**

- In config/database.js, create a function that connects to MongoDB using Mongoose
-  Use environment variables to store your connection string
- Include proper error handling and connection success messages
- Add event listeners for connection events (connected, error, disconnected)

**Task 3: Create a Book Schema**

***In models/Book.js, create a schema with the following fields:***

- title (string, required)
- author (string, required)
- ISBN (string, unique, required)
- publishedYear (number)
- genre (string)
- price (number, min: 0)
- inStock (boolean, default: true)
- createdAt (date, default: Date.now)


**Deliverables**

- All files with proper code
- Screenshots of successful connection and operations
- A brief explanation of how your code works
- Any challenges you faced and how you solved them

**Submission Guidelines**

- Push your code to a GitHub repository
- Share the repository link
- Include screenshots in a README.md file
- Deadline: Saturday, March 7 2026.

**Evaluation Criteria**

- ✅ Correct MongoDB connection 
- ✅ Proper schema design 
- ✅ Code organization and comments 
- ✅ Error handling


# All the best 🎓🎉🎉
