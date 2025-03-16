# MEAN Stack Application

## Overview

This is a MEAN stack application (MongoDB, Express.js, Angular, Node.js) that demonstrates a full-stack JavaScript solution for building modern web applications.

## Technologies Used

- **MongoDB**: NoSQL database for storing application data
- **Express.js**: Web application framework for Node.js
- **Angular**: Front-end framework for building dynamic single-page applications
- **Node.js**: JavaScript runtime environment for server-side code

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- MongoDB (v4 or higher)
- Angular CLI (v12 or higher)

### Installation

1. Clone the repository:

   ```
   git clone git@github.com-john:username/project-name.git
   cd project-name
   ```

2. Install server dependencies:

   ```
   npm install
   ```

3. Install client dependencies:

   ```
   cd client
   npm install
   cd ..
   ```

4. Configure environment variables:
   - Create a `.env` file in the root directory
   - Add the following variables:
     ```
     MONGO_URI=mongodb://localhost:27017/your-database
     PORT=3000
     JWT_SECRET=your_jwt_secret
     ```

### Running the Application

1. Start MongoDB:

   ```
   mongod
   ```

2. Start the server:

   ```
   npm run server
   ```

3. Start the Angular client:

   ```
   npm run client
   ```

4. For concurrent development (both server and client):
   ```
   npm run dev
   ```

## Project Structure
