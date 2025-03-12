# SIT737-2025-Prac2P 
## Task 2.1P: Node.js and Express

## Author
- Inwang ubong Marshal (222092371)

## Project Overview
This project involves setting up a simple web server using **Node.js** and **Express.js** to serve a static HTML page. The purpose of this task is to familiarize students with setting up a Node.js environment, creating a web server, and hosting a webpage using Express.js.

## Process Undertaken

### 1. Setting Up the GitHub Repository
- A new repository named `sit737-2025-prac2p` was created on GitHub.
- GitHub Codespaces was used as the development environment to facilitate cloud-based coding and testing.

### 2. Initializing the Node.js Project
- Node.js and npm were verified and installed in the GitHub Codespace.
- A new Node.js project was initialized using `npm init -y`, generating a `package.json` file to manage project dependencies.

### 3. Installing Dependencies
- The `express` package was installed using `npm install express`, which is required to set up a lightweight web server.

### 4. Creating the Web Server
- A `server.js` file was created to define the Express.js server.
- The server was configured to listen on port `3000` and serve static files from the `public` directory.
- The Express.js `static` middleware was used to serve the HTML file.

### 5. Developing the Web Page
- A `public` directory was created to store the static content.
- An `index.html` file was added inside `public`, containing basic HTML to be served by the server.

### 6. Running the Web Server
- The server was started using `node server.js`.
- The output confirmed that the server was running successfully and could be accessed via `http://localhost:3000`.

### 7. Verifying the Web Page
- The application was tested by forwarding **port 3000** in GitHub Codespaces.
- The web page was loaded in a browser to confirm that the HTML file was served correctly.

### 8. Committing and Pushing Code to GitHub
- All project files were added to Git tracking using `git add .`.
- Changes were committed with an appropriate message using `git commit -m "Initial commit: Node.js web server"`.
- The committed code was pushed to GitHub using `git push origin main`.

### 9. Submission
- The GitHub repository URL was copied and submitted via OnTrack.

## Technologies Used
- **Node.js** - JavaScript runtime environment for executing JavaScript code outside the browser.
- **Express.js** - Framework used to build the web server.
- **GitHub Codespaces** - Online development environment for coding and testing.
- **Git** - Version control system used to manage project files.



