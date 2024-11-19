Freelancing Application MERN

Prerequisites:

Before setting up the project, make sure you have the following software dependencies installed:

Node.js (v14 or higher)
  Required for running the backend server (Node and Express).
  Download from Node.js official website.
  npm (Node Package Manager)
  Comes with Node.js and is required to install project dependencies.
  To verify, run: node -v and npm -v in your terminal.

MongoDB (Community Edition or MongoDB Atlas for cloud)
  Used for database management to store complaints, user data, and more.
  For local setup, download from MongoDB official website.
  Alternatively, set up a MongoDB Atlas account for a cloud database here.

Git
  Required to clone the project repository from a version control platform (e.g., GitHub).
  Download from Git official website.
  Installation: Follow these steps to set up the project locally:
  Clone the Project Repository
  Open your terminal and navigate to the directory where you want to clone the project. Then run:
  git clone  https://github.com/kashvi456/Freelancing-Application-MERN.git
  
Navigate to Project Directory
  After cloning, navigate to the project directory:
  cd Freelancing-Application-MERN

Install Dependencies
  There are dependencies for both frontend and backend, so follow these steps:
  Frontend: Navigate to the frontend folder and install dependencies.
    cd frontend
    yarn add
  
Backend: Open a new terminal, navigate to the backend folder, and install dependencies.
    cd ../backend
    yarn add

Set Up Environment Variables
  Create .env files in both the frontend and backend folders to configure environment-specific variables. Here’s how:
  Backend Environment Variables: In the backend folder, create a .env file and add the following variables:
  PORT=8001 # Port for backend server

Running the Project
  Once the setup is complete, start the project by running the frontend and backend servers.
  Run the Backend Server:
    In the backend folder, run:
         node server.js
    The backend server should start on http://localhost:8001.

  Run the Frontend Server:
    Open a new terminal, navigate to the frontend folder, and run:
         yarn run dev
    The frontend server should start on http://localhost:1573 or another available port.
