# Chess-like Turn-based Game
This project is a chess-like turn-based game with a client-server architecture using WebSockets for real-time communication. The client-side is implemented in Kotlin for Android, and the server-side is written in Kotlin (or another language of your choice).

**Table of Contents**
  1) Prerequisites
  2) Project Structure
  3) Setup Instructions
      * Server Setup
      * Client Setup
  4) Running the Application
      * Running the Server
      * Running the Client
  7) Game Rules

**Prerequisites**
  1) JDK 17 or higher
  2) Gradle 8.0 or higher
  3) Android Studio (for the client)
  4) Kotlin (for both client and server)
  5) WebSocket library (like kotlinx.coroutines or ktor)

**Project Structure**
├── client/               # Android app (Kotlin)
│   ├── src/main/          # Source code for the Android app
│   └── build.gradle       # Build script for the Android client
│
├── server/               # Server-side code
│   ├── src/main/          # Source code for the server
│   └── build.gradle       # Build script for the server
│
├── README.md             # This README file
└── settings.gradle       # Gradle project settings

**Game Rules**
Game Setup: The game is played on a 5x5 grid. Each player controls 5 characters (Pawns, Hero1, Hero2).
Turns: Players take turns to move their characters. Moves are validated on both the client and server sides.
Winning Condition: The game ends when one player eliminates all of the opponent's characters.
For detailed game rules and instructions, refer to the game documentation.
