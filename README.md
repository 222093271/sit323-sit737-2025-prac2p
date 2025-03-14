# SIT323/SIT737-2025-Prac2P 
## Task 2.1P: Node.js and Express

## Author
- Inwang ubong Marshal (222092371)

## Project Overview
Establishing a simple web server by combining **Node.js** with **Express.js** for static HTML hosting is the main task addressed in this project. The assignment consists of teaching students Node.js setup procedures and web server creation together with Express.js based webpage hosting practices which form its primary focus.

## Process Undertaken

### 1. Setting Up the GitHub Repository
- Through GitHub, the `sit737-2025-prac2p` repository was established as the new project management space.
- User-employed VS-code functioned as the development environment to enable cloud-based coding and testing.

### 2. Initialising the Node.js Project
- The terminal of VS-code verified the installation of Node.js and npm.
- The `package.json` file for project dependency management was automatically created through the `npm init -y` command execution for initiating a new Node.js project.

### 3. Installing Dependencies
- Installation of the `express` package through `npm install express` produced the necessary component for creating simple web server operations.

### 4. Creating the Web Server
- A `server.js` file was established to shape the Express.js server implementation.
- The server operated on port `3000` while it delivered static files located in the `public` directory.
- The HTML file received its delivery through Express.js `static` middleware.

### 5. Developing the Web Page
- The program uses a `public` directory to function as the static content storage location.
- The server serves the `index.html` located inside `public` through basic HTML content added to its file structure.

### 6. Running the Web Server
- The server started operating through the `node server.js` execution.
- The server successfully operated at `http://localhost:3000` after the output indicated successful server functionality.

### 7. Verifying the Web Page
- A test of the application used **port 3000** forwarding within VS-code.
- A browser was used to load the page which confirmed that the HTML file transmitted correctly.

### 8. Committing and Pushing Code to GitHub
- All project files were added to Git tracking using `git add .`.
- Changes were committed with an appropriate message using `git commit -m "Initial commit: SimpleNode.js web server"`.
- The committed code was pushed to GitHub using `git push origin main`.

### 9. Submission
- The GitHub repository URL was copied and submitted via OnTrack.

## Technologies Used
- **Node.js** - JavaScript runtime environment for executing JavaScript code outside the browser.
- **Express.js** - Framework used to build the web server.
- **VS Code** - Code development environment for coding and testing.
- **Git** - Version control system used to manage project files.
