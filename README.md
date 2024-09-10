# Chess-Game
npm packages need to be installed before starting project - 
1) npm init -y
2) npm i express chess.js ejs socket.io

This project is a real-time multiplayer chess game developed using a combination of modern web technologies like Node.js, Express.js, Socket.IO, and Chess.js. The game provides a smooth and interactive environment where two players can challenge each other online. Below is an overview of the features and technologies used:

### Features:
- **Real-time Multiplayer Gameplay**: Two users can play chess against each other in real-time, with live updates on moves thanks to Socket.IO.
- **Move Validation and Game Logic**: Chess.js handles all the game logic, including move validation, game status (check, checkmate, stalemate), and piece movement rules.
- **Seamless User Communication**: Socket.IO ensures low-latency, real-time communication between players, providing an interactive gaming experience without lag.
- **Backend with Node.js and Express.js**: The server is built with Node.js and Express.js, managing player connections, game states, and routing.
- **User Interface**: A simple, clean, and intuitive user interface allows players to engage in the game without distractions.
- **Matchmaking**: Players can be paired with an opponent automatically or manually by joining a game room.
- **Cross-browser Support**: The game works across different browsers, providing a seamless experience regardless of the platform.

### Technologies:
- **Node.js**: Handles the server-side logic, managing requests and routing, and serves the game files.
- **Express.js**: Powers the web server, handling client connections, requests, and game sessions.
- **Socket.IO**: Facilitates real-time, bidirectional communication between the server and clients, allowing instant game state updates.
- **Chess.js**: Used for implementing the chess game logic, move validation, and game status monitoring.

This repository provides a fully functional chess game that can be expanded with additional features like player authentication, score tracking, or an AI-based opponent. Whether you’re a developer looking to enhance your real-time web application skills or a chess enthusiast interested in coding a game, this project is a solid foundation.
