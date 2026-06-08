# Tech-Explora
Tech-Explora is an immersive, virtual reality (VR)-based educational laboratory designed to revolutionize how students learn computer hardware. By leveraging cutting-edge hand tracking and voice command technologies, it provides an interactive environment where users can explore, understand, and assemble hardware components safely and cost-effectively—without the need for expensive physical equipment.

Key Features
Hand Tracking Assembly: Move beyond traditional controllers. Students can use natural hand gestures to pick up, inspect, and precisely assemble internal computer components like the motherboard, RAM, and CPU.
Voice-Command Exploration: Integrated with smart voice recognition, allowing users to issue voice commands (e.g., to disassemble parts or query technical details) for a hands-free learning experience.
Proximity-Based Audio Guides: As you approach or interact with specific hardware parts, contextual audio explanations trigger automatically to explain their functionality.
Safe & Cost-Effective Learning: Eliminates the risk of damaging expensive delicate components or dealing with electrical hazards, making hardware education accessible to any student with a VR headset.

Tech Stack & Architecture
The project is built using the Unity Game Engine and optimized for VR environments:
C# (53.1%): Powers the core game logic, user interactions, hand-tracking simulation, and voice command triggers.
ShaderLab (28.2%) & HLSL (18.7%): Used for advanced graphics rendering, realistic lighting, and material shaders to give the 3D hardware components a lifelike appearance.
Hugging Face API Integration: Utilized for processing advanced voice processing/AI capabilities within the simulation.

Core Repository Breakdown
VR & Interactive Scripts
VRHandSimulator.cs: Manages and simulates natural hand movements and gesture tracking inside the VR lab.
VoiceDisassemble.cs: Handles voice recognition logic to trigger the automated disassembly or breakdown of components.
VRLeverMovement.cs / VRLeverMovements.cs: Controls physical-like interactions with switches and mechanical levers in the lab.

Audio & Environmental Scripts
ProximityAudio.cs: Dynamically plays instructional audio descriptions when a user gets close to a specific hardware component.
DisplayTextOnTrigger.cs: Renders floating UI text instructions or component names when a part is highlighted or touched.
DoorTrigger.cs / elavator.cs / WALK.cs: Manages lab navigation, player movement, and environment physics (like doors and elevators).

3D Assets
mother_board__3d_model (1).glb: The central 3D asset representing a highly detailed computer motherboard used for the assembly simulation.

Target Audience
Educational Institutions: Schools and universities looking to scale their IT/Computer Science labs digitally without high hardware maintenance costs.
Students & Self-Learners: Individuals wanting a hands-on approach to understanding how a computer is built from scratch.
VR Enthusiasts: Developers interested in implementing advanced hand-tracking and voice-recognition mechanics in Unity.

Contributors
Abinaya Shree M S - Main Creator & Developer
