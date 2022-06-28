"This was created during my time as a student at Code Chrysalis."

# Multiplayer Chess

- This is an app that lets users simply play chess against other people.

- You can go to a room and invite your friend to play.
moet u aint shit bruh 
- You can find a game against a random opponent.

### Inspiration

- I made this app to learn about SocketIO and wanted to use it in a turn based game. I decided on chess since I'm currently learning to play!

### Technologies:
- React
  - ChessBoardJSX & ChessJS for Board & Game Logic
- Node/Express
- SocketIO

### Getting Started
- After cloning or downloading to your local machine, install dependencies
```
npm install
```
- The only environment variable needed is the url for socketIOClient (REACT_APP_URL)
- To create a production ready build folder for client
```
npm run build
```

- To start the server
```
npm start
```

### Development
- To run client seperately
```
npm run client
```

- To run server in development mode
```
npm run dev
```