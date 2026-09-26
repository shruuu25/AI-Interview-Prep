# AI Interview Prep

An AI-powered interview preparation platform designed to help users practice interviews, track performance, and improve their technical and communication skills through an interactive web experience.

## Features

* User authentication and account management
* AI-assisted interview preparation
* Interactive interview practice interface
* Performance tracking and visual analytics
* Progress visualization using charts
* PDF-based functionality and report generation
* Responsive and modern user interface
* Secure backend APIs
* MongoDB-based data management
* Payment integration support with Razorpay

## Tech Stack

### Frontend

* React
* Vite
* Tailwind CSS
* Redux Toolkit
* React Router
* Axios
* Recharts
* Firebase
* jsPDF
* Motion

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* Multer
* Axios
* Razorpay

## Project Structure

```text
AI-Interview-Prep/
│
├── client/          # React frontend
│
├── server/          # Node.js and Express backend
│
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites

Make sure the following are installed:

* Node.js
* npm
* MongoDB
* Git

### 1. Clone the repository

```bash
git clone https://github.com/shruuu25/AI-Interview-Prep.git
cd AI-Interview-Prep
```

### 2. Install frontend dependencies

```bash
cd client
npm install
```

### 3. Install backend dependencies

Open another terminal window or return to the project root:

```bash
cd ../server
npm install
```

### 4. Environment Variables

Create a `.env` file inside the `server` directory and add the required configuration for your local environment.

Example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Add any additional API or payment credentials required by the application.

**Never commit real API keys, passwords, database credentials, or secret tokens to GitHub.**

## Running the Application

### Start the backend

```bash
cd server
npm run dev
```

### Start the frontend

In another terminal:

```bash
cd client
npm run dev
```

The Vite development server will provide the local frontend URL in the terminal.

## Development

The project follows a separate frontend and backend architecture:

* `client/` contains the React-based user interface.
* `server/` contains the Express API and database-related functionality.
* MongoDB is used for persistent application data.
* REST APIs connect the frontend with backend services.

## Future Improvements

* Add more AI-driven interview scenarios
* Improve interview feedback and recommendations
* Add additional technical interview categories
* Introduce personalized preparation plans
* Expand analytics and progress tracking
* Improve accessibility and mobile responsiveness

## License

Please refer to the original project's licensing terms and the licenses of the third-party dependencies used in this project.

# AI Interview Prep

An AI-powered interview preparation platform designed to help users practice interviews, track performance, and improve their technical and communication skills through an interactive web experience.

## Features

* User authentication and account management
* AI-assisted interview preparation
* Interactive interview practice interface
* Performance tracking and visual analytics
* Progress visualization using charts
* PDF-based functionality and report generation
* Responsive and modern user interface
* Secure backend APIs
* MongoDB-based data management
* Payment integration support with Razorpay

## Tech Stack

### Frontend

* React
* Vite
* Tailwind CSS
* Redux Toolkit
* React Router
* Axios
* Recharts
* Firebase
* jsPDF
* Motion

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* Multer
* Axios
* Razorpay

## Project Structure

```text
AI-Interview-Prep/
│
├── client/          # React frontend
│
├── server/          # Node.js and Express backend
│
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites

Make sure the following are installed:

* Node.js
* npm
* MongoDB
* Git

### 1. Clone the repository

```bash
git clone https://github.com/shruuu25/AI-Interview-Prep.git
cd AI-Interview-Prep
```

### 2. Install frontend dependencies

```bash
cd client
npm install
```

### 3. Install backend dependencies

Open another terminal window or return to the project root:

```bash
cd ../server
npm install
```

### 4. Environment Variables

Create a `.env` file inside the `server` directory and add the required configuration for your local environment.

Example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Add any additional API or payment credentials required by the application.

**Never commit real API keys, passwords, database credentials, or secret tokens to GitHub.**

## Running the Application

### Start the backend

```bash
cd server
npm run dev
```

### Start the frontend

In another terminal:

```bash
cd client
npm run dev
```

The Vite development server will provide the local frontend URL in the terminal.

## Development

The project follows a separate frontend and backend architecture:

* `client/` contains the React-based user interface.
* `server/` contains the Express API and database-related functionality.
* MongoDB is used for persistent application data.
* REST APIs connect the frontend with backend services.

## Future Improvements

* Add more AI-driven interview scenarios
* Improve interview feedback and recommendations
* Add additional technical interview categories
* Introduce personalized preparation plans
* Expand analytics and progress tracking
* Improve accessibility and mobile responsiveness

## License

Please refer to the original project's licensing terms and the licenses of the third-party dependencies used in this project.

