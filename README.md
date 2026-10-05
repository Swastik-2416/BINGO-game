# Bingoo! 🎲

Bingoo! is an open-source, web-based multiplayer Bingo game. Host custom private rooms, join public matchmaking lobbies, or play local party games directly in your browser.

## Features ✨

- **Local Party Mode:** Sit in a circle and play locally. Announce numbers physically; mark them manually on your screen.
- **Online Public Matchmaking:** Quick matchmaking. Connect and play turn-by-turn with online public players.
- **Custom Private Rooms:** Host a custom match (public or private), or join a friend's room with a 6-letter room code.
- **Avatar & Nickname System:** Choose from a wide selection of animal avatars and pick your own nickname.
- **Customizable Bingo Range:** Play classic 1-75 bingo, 1-90 UK style, or smaller 1-25 and 1-50 grids.
- **Firebase Powered:** Realtime database integration ensures snappy sync between all players.

## Getting Started 🚀

To run this project locally, simply clone the repository and open `index.html` in your browser. Alternatively, run a local web server (e.g. using python, node, or Live Server) for the best experience.

### Prerequisites

You need a web browser and a connection to the internet (for Firebase functionality). 

### Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/bingoo.git

# Navigate to the project directory
cd bingoo

# Serve using Python 3
python3 -m http.server 8000
```
Then, open `http://localhost:8000` in your web browser.

## Contributing 🤝

We welcome contributions of all sizes! Whether it's fixing a bug, adding a feature, or improving the design, please check out our [CONTRIBUTING.md](CONTRIBUTING.md) guide to get started. Don't forget to review our [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

If you are a beginner looking for a place to start, check the Issues tab for issues labeled `good first issue`. 

## Tech Stack 🛠️

- HTML5, CSS3, JavaScript (Vanilla)
- Firebase Realtime Database (for multiplayer state synchronization)
- Firebase Anonymous Auth

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
