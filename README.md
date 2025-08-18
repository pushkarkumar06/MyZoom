# Apna Video Call

## Overview

**Apna Video Call** is a full-stack web application that enables users to make high-quality video calls, chat in real-time, and manage their meeting history. Inspired by platforms like Zoom, this project is designed for seamless video communication, whether you want to connect with friends, family, or colleagues. It features guest access, user authentication, meeting history tracking, and a modern UI built with React and Material-UI.

---

## Features

- **Video Conferencing:** Real-time video calls using WebRTC and Socket.io.
- **Chat:** In-call chat functionality for instant messaging.
- **User Authentication:** Register, login, and guest access.
- **Meeting History:** Track and view previous meetings.
- **Responsive UI:** Built with React and Material-UI for a smooth user experience.

---

## Installation Instructions

### Prerequisites

- Node.js (v16+ recommended)
- npm (comes with Node.js)
- MongoDB (cloud or local instance)

### 1. Clone the Repository

'''sh
git clone https://github.com/pushkar/Zoom-main.git
cd MyZoom


2. Backend Setup
   -> cd backend
   -> npm install
   .  Configure MongoDB connection in src/app.js if needed.

3. Frontend Setup
   -> cd ../frontend
   -> npm install

Usage Guide
1. Start the Backend server :)
   cd backend
   npm run dev
  . The backend runs on http://localhost:8000 by default.

2. Start the Frontend Development Server
   cd frontend
   npm start
   . The frontend runs on http://localhost:3000.

3. Access the Application
   -> Open http://localhost:3000 in your browser.
   -> Register or login to access full features , or join as a guest.
   -> Start or join a video call using a meeting code.
   -> Use the chat feature during calls.
   -> View your meeting history from the "History" page.


###

backend/
  src/
    [app.js](http://_vscodecontentref_/0)                # Express server entry point
    controllers/
      [socketManager.js](http://_vscodecontentref_/1)    # Socket.io logic for video and chat
      [user.controller.js](http://_vscodecontentref_/2)  # User authentication and history
    models/
      [user.model.js](http://_vscodecontentref_/3)       # User schema
      [meeting.model.js](http://_vscodecontentref_/4)    # Meeting schema
    routes/
      [users.routes.js](http://_vscodecontentref_/5)     # API routes for user actions

frontend/
  src/
    [App.js](http://_vscodecontentref_/6)                # Main React app
    pages/                # Landing, Home, Auth, VideoMeet, History
    contexts/             # AuthContext for global state
    styles/               # CSS modules
    utils/                # withAuth HOC
    [environment.js](http://_vscodecontentref_/7)        # Backend server URL

###
  

Contributing Guidelines
1. Fork the repository and create your branch from main.
2. Install dependencies as described above.
3. Follow coding standards (ESLint, Prettier, React best practices).
4. Commit descriptive messages.
5. Open a pull request with details about your changes.
6. Report issues or feature requests via GitHub Issues.


###

Project Information 
~ Version: 1.0.0
~ License: ISC
~ Authors: Pushkar Kumar,
~Acknowledgments:
  [![React](https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg)](https://react.dev/)
  [![Material-UI](https://v4.mui.com/static/logo.png)](https://mui.com/)  
  [![Socket.io](https://socket.io/images/logo.svg)](https://socket.io/)  
  [![MongoDB](https://webassets.mongodb.com/_com_assets/cms/mongodb_logo1-76twgcu2dm.png)](https://www.mongodb.com/)  





 


