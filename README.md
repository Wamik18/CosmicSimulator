Cosmic Canvas: Interactive Orbital Mechanics Sandbox

An interactive 2D physics sandbox simulating real-time orbital mechanics, gravity vectors, and momentum conservation. Built entirely with vanilla HTML, CSS, and JavaScript within a single file for the NASA x AMD Stardance Challenge.

Live Demo
https://cosmicsimulator.netlify.app/

Core Physics and Features
This sandbox avoids predefined animations, running entirely on a custom frame-by-frame vector physics engine modeled after astronomical principles:

Universal Gravitation: Every object exerts a pull on every other object based on mass and distance, calculated dynamically across every frame.

Inelastic Merging Collisions: Colliding bodies merge into a single entity, using conservation of momentum to calculate the combined mass and new trajectory vector.

Vector Launch System: Click and drag to draw a dynamic directional vector, adjusting initial launch speed and trajectory instantly.

Orbital Path Visualization: Moving bodies leave fading trails of past coordinates to map out clean ellipses, hyperbolas, and slingshot trajectories.

Real-Time Data Dashboard
The interface includes a live readout panel tracking real-time simulation metrics:

Object Speed and Velocity: Displays continuous speed updates and individual directional vector velocities for active celestial bodies.

Gravity Controls: Shows the live gravitational constant value alongside adjustable sliders to increase or decrease the strength of the gravity field.

Collision Data: Tracks the total number of remaining active bodies and registers data changes immediately when objects merge.

Controls and Presets

Massive Star Mode: Click to place heavy, static solar hubs.

Planet Launch Mode: Click and drag anywhere in space to launch planets or asteroids with custom velocity.

Built-in Scenarios: Buttons to instantly load classic orbital setups, including a stable Earth-Moon system, a binary star system, and a chaotic asteroid belt.

Tech Stack and Performance

Architecture: Built as a single HTML file with no external frameworks or dependencies.

Graphics: High-performance HTML5 Canvas 2D rendering loop.

AMD Stress Testing: Engineered with a scalable time-step variable to handle high body counts, allowing users to stress-test concurrent vector calculations on modern hardware.

Project Backstory
This project began in Notepad++ and was later migrated to Visual Studio Code with Hackatime integration to properly log developer hours. The underlying physics algorithms and UI layout were designed in collaboration with Claude, focusing on optimizing force-vector softening loops to prevent layout and boundary glitches.

Created for the Hack Club Stardance Event (2026).
