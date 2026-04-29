# VR-Multiplayer-Collaborative-Design-Workshop

A Virtual Reality (VR) platform that enables multiple users to collaborate in real time within a shared 3D design workspace. Participants can create, modify, and review designs together, enhancing teamwork, communication, and immersive design experiences.

INTRODUCTION:
This project implements a multiplayer VR system that provides:
Room-Based System: Users can create or join public/private rooms for controlled collaboration.
Interactive Virtual Environment: A fully navigable VR space designed for user interaction and engagement.
Mini-Games Integration: Three different interactive activities/games are included to enhance collaboration and user involvement.
Real-Time Communication: Integrated Vivox voice and chat system for seamless communication between users.
User Customization: Basic user identity setup such as naming and appearance customization.
The system is built using Unity and focuses on delivering a smooth, interactive, and collaborative VR experience. It can be extended further for educational, training, or professional design collaboration use cases.

TOOLS:
Unity (2022.x) – Game engine used for developing the VR environment and interactions
C# – Programming language used for scripting game logic
XR Interaction Toolkit – For implementing VR interactions and controls
Netcode / Multiplayer Framework – For handling real-time multiplayer functionality
Vivox – Integrated for real-time voice and text communication
Blender / 3D Assets – Used for creating and importing 3D models (if applicable)
Visual Studio / VS Code – Code editor for scripting and debugging
Git (optional) – Version control for project management
Windows PC with VR Support – Development and testing platform

PROJECT SETUP:
The project was initialized using Unity (2022.x) with VR support enabled. Essential packages such as XR Interaction Toolkit were imported and configured. The basic scene was set up with camera rigs, lighting, and initial environment layout to support VR development.

VR ENVIRONMENT DESIGN:
A 3D virtual environment was designed to simulate a collaborative workshop space. Various assets such as floors, walls, interactive objects, and visual elements were added to create an immersive and user-friendly VR experience. The environment was optimized for smooth navigation and interaction.

Player Setup & Movement
The VR player system was implemented using XR tools, allowing users to move, look around, and interact within the virtual environment. Controller-based interactions such as pointing, selecting, and grabbing objects were enabled to enhance usability.

Multiplayer Integration
Multiplayer functionality was integrated to allow multiple users to connect and interact in real time. Networking systems were configured to synchronize player positions, actions, and interactions across all connected users in the same session.

Room/Lobby System
A room-based system was developed where users can create public or private rooms and join existing sessions. This system ensures controlled access and allows multiple groups to collaborate independently within separate virtual spaces.

User Customization
Before entering the virtual environment, users can set their identity by choosing a name and customizing basic appearance elements such as avatar color. This helps in identifying different users in the shared space.

Voice & Chat Integration
Vivox was integrated to provide real-time voice and text communication between users. This feature enhances collaboration by allowing participants to discuss, share ideas, and coordinate effectively within the VR environment.

Mini-Games Development
Three interactive mini-games were implemented within the environment to improve user engagement and teamwork. These activities encourage interaction between players and demonstrate collaborative features of the system.

UI & Interaction System
Interactive UI panels were designed for room creation, settings, and game controls. The UI was optimized for VR usage, ensuring it is easily accessible and user-friendly within the 3D space.
![Description](1.jepg)

Testing & Optimization
The project was thoroughly tested to ensure smooth performance, proper synchronization between players, and a seamless user experience. Optimization techniques were applied to maintain stable frame rates and reduce latency in VR.
