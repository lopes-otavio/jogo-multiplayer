# Multiplayer Game

This is a simple multiplayer game where players can collect fruits an mark points.

## How to Run

1. Clone this repository to your local machine.

2. Navigate to the project directory in your terminal.

3. Install the dependencies using npm:

npm install

4. Start the Node.js server:

node server.js

5. Open your browser and go to `http://localhost:3000` to see the game in action.

## Gameplay

- When you open the game in your browser, you'll see a box with colored pixels, the green ones are the fruits the yellow its u and the black ones its the other players.
- You can move your square using the keyboard arrows.
- Your youe moves will be synchronized with other players in real-time.

## Technologies Used

- **Node.js**: Used for the server-side logic.
- **HTML5 Canvas**: Provides the drawing interface in the browser.
- **JavaScript**: Used for client-side scripting to handle user interactions.
- **WebSockets (Socket.io)**: Enables real-time communication between the server and clients.

## File Structure

- **server.js**: Node.js server file that handles WebSocket connections and broadcasts drawing updates.
- **public/index.html**: HTML file containing the canvas element and client-side JavaScript.

## Dependencies

- **express**: Web framework for Node.js.
- **socket.io**: WebSocket library for real-time communication.
- **nodemon** (optional, for development): Automatically restarts the server when files change.

## Contributing

Contributions are welcome! Feel frree to fork this repository, make changes, and submit a pull equest.

