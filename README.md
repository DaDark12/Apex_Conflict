Apex Conflict: Multiplayer FPS Simulator

This project is a real-time, browser-based, first-person shooter (FPS) simulator designed to explore the concepts of 3D rendering (using Three.js) and real-time multiplayer synchronization (using Firebase Firestore).

It is entirely contained within a single index.html file for easy deployment and testing.

🚀 Getting Started

Since this is a multiplayer application, it requires a backend service to work.

Deployment: To run this game, you need to host the index.html file on a web server (like GitHub Pages).

Backend Requirement: The application uses Firebase for user authentication, lobby management, and player position sync. It relies on environment variables (__app_id, __firebase_config, __initial_auth_token) to connect to a secure environment. While the code is complete, it must be run in a Firebase/Canvas-enabled environment to function as a live multiplayer game.

✨ Key Features

3D Environment: Uses Three.js for rendering a basic game arena.

Real-Time Multiplayer: Players' positions and rotations are synced via Firestore's real-time listeners.

Lobby System: Includes screens for profile setup, browsing public lobbies, joining private lobbies (using codes), and host-driven game start.

FPS Controls: Standard WASD movement and mouse look (requires pointer lock).

Loadouts: Simple selection of weapon and grenade types during profile setup.

📝 License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0).

See the full license text in the LICENSE file.
