# Google Docs Clone

This project is a collaborative document editing application inspired by Google Docs. Built with React for the frontend, Quill.js for rich text editing, Socket.io for real-time communication, and Node.js for the backend, this application allows multiple users to edit a document simultaneously.

## Features

- Real-time collaborative editing
- Rich text formatting with Quill.js
- User authentication (optional)
- Document versioning and saving
- Responsive design for various devices

## Technologies Used

- **Frontend:** 
  - [React](https://reactjs.org/) - JavaScript library for building user interfaces
  - [Quill.js](https://quilljs.com/) - Rich text editor
  - CSS
  
- **Backend:**
  - [Node.js](https://nodejs.org/) - JavaScript runtime
  - [Express](https://expressjs.com/) - Web framework
  - [Socket.io](https://socket.io/) - Real-time bidirectional event-based communication

## Getting Started

### Prerequisites

- Node.js installed on your machine
- A package manager like npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/google-docs-clone.git
   cd google-docs-clone
   ```
   
2. Install dependencies for both frontend and backend:
    ```bash
    npm install
    cd client
    npm install
    ```

3. Start the server:
    ```bash
    Copy code
    cd ..
    npm start
    ```
4. Open your browser and navigate to http://localhost:3000 to view the application.

## Usage
- Create a new document or open an existing one.
- Collaborate with other users in real-time.
- Use the toolbar to format text, insert images, and more.

## License
- This project is licensed under the MIT License. See the LICENSE file for more details.
