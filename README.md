Fair Big/Small Prediction Game
Overview
This is a simple web app where users predict if a random blockchain-based number is “Big” or “Small.” The randomness is provably fair because it uses the last digit of the latest Ethereum block hash. The app updates every 20 seconds, showing results with sound effects and tracking wins, losses, and points.

How to Use
Open index.html in any modern browser (Chrome, Firefox, Edge).

Click Big or Small to select your prediction.

Wait for the countdown to reach zero (20 seconds).

The app fetches the latest Ethereum block hash, determines the result, and shows if you won or lost.

Scoreboard updates automatically.

Features
Provably fair randomness from blockchain data
Countdown timer for rounds
Sound effects for win, lose, and draw
Scoreboard tracking games played, wins, losses, and points
Simple, clean UI
Technical Details
Uses Ethereum block hash from BlockCypher API
JavaScript for logic and UI updates
Audio from free sound effect URLs
No server needed, runs fully in browser

