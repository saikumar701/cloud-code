Here is your cleaned-up `README.md` with all Docker-related sections **removed**, while keeping only the **local installation method** under the new project name **Cloud Code** and authored by **Sai Kumar**:

---

# **Cloud Code: Realtime Collaborative Code Editor**

## Introduction

Are you tired of sending code snippets back and forth, struggling to debug and collaborate with your team? Look no further! **Cloud Code** is here to revolutionize the way you code together. This powerful and intuitive collaborative code editor is designed to empower developers and teams to work seamlessly in real-time, regardless of their location. With **Cloud Code**, you can code together, debug together, and ship faster — together.

## Features

* Multiple users can join a room and edit code collaboratively
* Real-time code syncing across all participants
* Copy button to copy the room ID to clipboard
* Leave button to exit a room
* Syntax highlighting for multiple programming languages
* Theme customization based on user preferences
* Rejoin rooms later and continue editing
* User join/leave notifications in real time

## Prerequisites

* Node.js (v20.11.1)
* npm (10.2.4)
* pm2 (5.3.1): install globally with `npm i -g pm2`

> **Note:** Using `nvm` (v0.39.7) to manage Node versions is recommended. See [nvm documentation](https://github.com/nvm-sh/nvm).

## Tech Stack

* React.js
* Node.js
* Express.js
* Socket.io
* CodeMirror
* React-Toastify

## Installation (Run Locally)

1. Clone this repository:

   ```bash
   git clone https://github.com/your-github-username/cloud-code.git
   cd cloud-code
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the root folder and copy the contents of `example.env`, then fill in the required values.

4. Start the React client:

   ```bash
   npm start
   ```

5. In another terminal, start the backend server:

   ```bash
   npm run server:dev
   ```

   or using PM2:

   ```bash
   pm2 start server.js
   ```

6. Open your browser and navigate to `http://localhost:3000`

7. Click `Create New Room`, enter your username, and share the room ID with others to join.

> To stop the server:
>
> * Press `Ctrl + C` if running manually
> * Use `pm2 stop server.js` if using PM2

## Project Demo

🎥 Watch it in action:
[Project Video](https://github.com/Mohitur669/Realtime-Collaborative-Code-Editor/assets/79283402/14c17cc7-d23a-4d39-8af3-ef9e9fa8ef45)

## Future Scope

* [x] Syntax highlighting for multiple languages
* [x] Support for multiple themes
* [x] Persist theme/language in local storage
* [x] Approve or reject new users before they join
* [ ] Add video and voice chat
* [ ] Support local file upload

## Open Source Contribution

We welcome contributions! Follow these steps:

1. Fork this repo

2. Clone your fork:

   ```bash
   git clone https://github.com/your-github_username/cloud-code.git
   cd cloud-code
   ```

3. Create a new branch:

   ```bash
   git checkout -b your_branch_name
   ```

4. Make changes, then commit and push:

   ```bash
   git add .
   git commit -m "Your message"
   git push origin your_branch_name
   ```

5. Create a pull request on GitHub.

> Please use your own branch when contributing.

## About Me

Hi, I'm **Sai Kumar**, a passionate developer building real-world cloud-based tools like **Cloud Code**. I enjoy creating impactful applications, especially in cloud computing, AI, and real-time systems.

## Connect with Me

* [LinkedIn](https://www.linkedin.com/)
* [GitHub](https://github.com/) *(Add your actual links here)*

---

Let me know if you also want:

* Deployment instructions for Railway, Render, or Vercel
* Updated `.env` setup help
* Custom logo or branding for **Cloud Code**
