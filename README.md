#  Real-Time Multiplayer Chess Game

A full-stack **real-time chess application** that allows two players to play live over the internet using WebSockets. Built with **Node.js**, **Express**, and **Socket.IO**, this project demonstrates real-time communication, multiplayer synchronization, and server-side game validation.

---

## 🛠️ Tech Stack

**Frontend:** HTML, CSS, JavaScript
**Backend:** Node.js, Express.js
**Real-Time Communication:** Socket.IO
**Game Logic:** chess.js

---

## Features

*  Real-time two-player gameplay
*  Instant move synchronization
*  Server-side move validation
*  Automatic White / Black role assignment
*  Responsive chessboard UI
*  Works on local network or deployed server

---


##  Installation & Setup

### 1. Clone Repository

```
git clone https://github.com/your-username/real-time-chess.git
cd real-time-chess
```

### 2. Install Dependencies

```
npm install
```

### 3. Start Server

```
node server.js
```

Server runs at:

```
http://localhost:3000
```

---

##  How It Works

1. Player 1 opens the game.
2. Player 2 joins from another browser/device.
3. Server assigns roles (White/Black).
4. Moves are sent to the server via Socket.IO.
5. Server validates and broadcasts moves to keep boards synchronized.

---

##  Future Improvements

* Private game rooms
* Spectator mode
* Chess timer
* In-game chat
* Leaderboard system

---

## Author

Himanshee
---

