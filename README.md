# VivoVR
VivoVR is a multiplayer VR framework built on Unity Multiplayer Services, designed to provide a smooth, scalable, and feature-rich networking solution tailored for Gorilla Tag fan games. It aims to be a modern alternative to PhotonVR, offering advanced integration, full player synchronization, and built-in voice chat support with Vivox.

Features
Player Synchronization: Real-time syncing of player movements, rotations, and actions.

Custom Player Properties: Supports usernames, player colors, cosmetics, and other customizable properties.

Voice Chat Integration: Uses Vivox for clear, low-latency voice communication between players.

Room Management: Seamless room creation, joining, and management via Unity Lobby and Relay services.

Netcode for GameObjects: Leverages Unity’s official netcode for stable multiplayer synchronization.


Optimized for Gorilla Tag Fan Games: Designed with Gorilla Tag-style VR multiplayer games in mind, but adaptable to other VR projects.

Getting Started
Prerequisites
Unity 2023.x or later

Unity Multiplayer Services (Lobby, Relay, Netcode for GameObjects)

Vivox SDK for Unity

Installation
Clone or download this repository.

Import the project into Unity.

Setup Unity Multiplayer Services and link your project in the Unity Dashboard.

Import the Vivox SDK and configure your Vivox credentials.

Follow the sample scene to see VivoVR in action.

Usage
Join a Room: Use VivoVRManager.JoinRoom(string roomName, Action<bool> callback) to join or create a multiplayer room.

Player Setup: The VivoVRPlayer prefab syncs transform, username, color, and cosmetics automatically.

Voice Chat: Integrated voice is active by default when connected to a room.

Refer to the example scenes for detailed setup and customization.
