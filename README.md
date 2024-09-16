# Real-Time Collaborative Whiteboard

A simple real-time collaborative whiteboard application where multiple users can draw and share their drawings instantly using Socket.IO and React. This app allows users to draw on a shared canvas and see updates in real-time from other connected users.

## Features

- Real-time drawing collaboration.
- Multiple users can connect and draw simultaneously.
- Automatic broadcasting of drawing events to all connected clients.
- User connection and disconnection notifications.
- Server implemented with Node.js, Express, and Socket.IO.
- Client-side built with React.

## Tech Stack

- **Frontend**: React, Socket.IO Client
- **Backend**: Node.js, Express, Socket.IO
- **Others**: CORS, WebSockets

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/collaborative-whiteboard.git
    cd collaborative-whiteboard
    ```

2. Install dependencies for the server:

    ```bash
    cd server
    npm install
    ```

3. Install dependencies for the client:

    ```bash
    cd ../client
    npm install
    ```

## Running the Application

1. Start the backend server:

    ```bash
    cd server
    npm start
    ```

2. Start the frontend development server:

    ```bash
    cd ../client
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000` to use the collaborative whiteboard.

## Usage

- Once the app is running, open it in multiple browser tabs or share the URL with others to collaborate on a shared canvas.
- Users can draw on the whiteboard, and their drawings will appear in real-time for all connected clients.
- The list of connected users is broadcasted and updated when users connect or disconnect.

## Project Structure

```bash
collaborative-whiteboard/
├── client/         # React client-side code
├── server/         # Node.js server-side code
└── README.md       # This file


