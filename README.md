# Chat-app

Chat-app is a real-time chat application built using Node.js, Express.js, Socket.IO, MongoDB, and Mongoose. The application allows users to send and receive messages instantly with real-time bidirectional communication.

## Features

- Real-time messaging using Socket.IO
- Fast bidirectional communication between users
- Chat history persistence using MongoDB
- User and message schema management with Mongoose
- Static frontend served from the `public` folder
- Event-driven architecture for handling WebSocket connections
- Supports multiple concurrent users

## Tech Stack

- Node.js
- Express.js
- Socket.IO
- MongoDB
- Mongoose
- HTML
- CSS
- JavaScript

## Project Structure

```bash
Chat-app/
│
├── public/
│   ├── css/
│   ├── profile/
│   ├── chat.html
│   ├── chat.js
│   ├── index.html
│   └── notification.mp3
│
├── db.config.js
├── index.js
├── message.schema.js
├── user.schema.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
