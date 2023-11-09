# Game

# Running

Open client/index.html in a browser (on two tabs if you want to play)

Run npm start in ./src

Connect the clients, create a game on one client, join it on the other and press start

# Notes

Refactored TSBR to have reasonable typing and not broadcast the entire game state.

Server manages a collection of GameRoom objects which have Players in them.

Client is shitty, just exists as for validation for now.

https://github.com/Craigievar/typespeed_br has OG client code etc.

Notes:
Players send words, client side validation, server verifies.

Get server key from https://console.statsig.com/2kKHVKKsowaOw4evoTzZGL/metrics/events, add to .env file in src.
