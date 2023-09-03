# Management MERN app

## Dependencies

- GraphQL
- Express.js
- MongoDB
- Mongoose
- React
- Apollo Client

## Description

Simple app where you can add a client or delete the client, then you can create a project, view, update or delete.

## Getting Started

1. Clone the project
2. Install the required dependencies by running `npm install` in the server and client directory
3. To set up the database, create an `.env` file in the root project directory and add the following:

   ```env
   NODE_ENV = 'development'
   PORT=8000
   MONGO_URI=<your_MongoDB_URI_here>
   ```

   For mongo_URI: https://www.mongodb.com/docs/guides/atlas/cluster/

4. To run the server `npm run dev`
5. To run the client `npm run start`
