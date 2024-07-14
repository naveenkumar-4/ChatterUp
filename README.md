# ChatterUp
ChatterUp is an interactive real-time chat application designed to facilitate seamless communication and interaction between users. Built with Node.js, Express.js, Socket.io, and MongoDB, this project aims to provide a robust and engaging chat experience.

## Features
1. Real-time Communication:
   - Utilizes WebSockets through the Socket.io library for real-time, bidirectional communication between users.
2. Code Modularity:
   - Follows modern development practices by employing ES6 Modules for code organization, ensuring maintainability and ease of collaboration.
3. User-Friendly Chat UI:
   - Designed with HTML, CSS, and JavaScript to enhance the user experience, including components for seamless chatting and a notification panel displaying online users.
4. User Onboarding:
   - Prompts new users to provide their name and displays a welcome message in the header with their name.
5. Chat History and User Count:
   - Allows newly joined users to access chat history and provides real-time updates on the number of users currently in the chat.
6. Message Broadcasting and Database Storage:
   - Broadcasts messages to all connected users in real-time and securely stores them in the MongoDB database for future reference and retrieval.
7. User Typing Indicators:
   - Displays a 'typing...' indicator to all connected users when a user is typing, which disappears once the user finishes typing.
8. Notification of New User Joins and Disconnections:
   - Updates the notification panel in real-time when a new user joins or leaves the chat, notifying all connected users.
9. Profile Pictures for User Consistency:
   - Displays an associated profile picture for each user throughout their conversation, providing a consistent visual identity.
10. Displaying Chat Messages:
   - Displays the user's name, profile picture, message content, and the time of posting for each chat message.
11. Project Setup
    - Backend Setup:
      - Navigate to the backend directory.
      - Run npm install to install dependencies.
      - Create a .env file with your MongoDB URI.
      - Run npm run dev to start the backend server.
    - Frontend Setup:
      - Navigate to the frontend directory.
      - Run npm install to install dependencies.
      - Run npm start to start the frontend server.
