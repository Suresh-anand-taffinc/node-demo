# Node.js Express Application

This is a simple Node.js application using Express. It serves a basic API with a health check endpoint.

## Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [Docker](https://www.docker.com/) (optional for containerized deployment)

---

## Setup & Run Locally

### 1. Clone the Repository

git clone <repository-url>
cd node-app

2. Install Dependencies

npm install
npm install express

3. Run the Application

npm start

The application will start on port 8080.
4. Test the Application
Using Browser or Curl:

Open http://localhost:8080/ → Should return "Hello, DevOps Intern!"
Check health endpoint:    curl http://localhost:8080/health

