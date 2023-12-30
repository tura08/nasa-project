# NASA Project with SpaceX API Integration

## Description

This project is a full-stack web application that connects to a MongoDB database and integrates real data from the SpaceX API. It was built as part of a coding course, following step-by-step instructions, and showcases skills in both frontend and backend development. The frontend was initially provided as a .zip file and later integrated with the backend.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- React
- SpaceX API
- etc.

## Installation and Setup

To run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/nasa-project.git
   ```
2. Navigate to the project directory:
   ```
   cd nasa-project
   ```
3. Install dependencies for both the server and client:
   ```
   npm run install
   ```
4. Set up a `.env` file in the `server` directory with your MongoDB connection string.

## Usage

To start both the server and client concurrently, run:

```
npm run watch
```

This script will start the server using `npm run server` and the client using `npm run client`.

For deployment, use:

```
npm run deploy
```

This will build the client and start the server for production.

## Features

- Integration with SpaceX API to fetch real-time data.
- Secure MongoDB database connection using environment variables.
- Responsive frontend design using React.

## Acknowledgments

Special thanks to Adam Odziemkowski and Andrei Neagoie (Zero to Mastery Academy: NodeJS Developer course) which guided me through this project. This project wouldn't have been possible without the invaluable resources and support provided by them.
