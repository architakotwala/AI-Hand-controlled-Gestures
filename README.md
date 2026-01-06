# 🌌 AI-Powered Interactive 3D Particle System
A real-time, gesture-controlled generative art experience built with Three.js and MediaPipe. This project transforms your webcam into a spatial controller, allowing you to manipulate thousands of particles through hand tracking and computer vision.
✨ Key Features:
1. Hand-Gesture Shape Morphing: Transition smoothly between complex 3D templates (Flower, Heart, Saturn, Butterfly) based on the number of fingers detected.
2. Dynamic Physics Engine:
   Explosion (Fireworks): Trigger a radial velocity blast by quickly opening a clenched fist.
   Vortex Swirl: Control the system's rotation and turbulence by tilting your palm or rotating your hand.
   Pinch-to-Scale: Dynamically expand or contract the particle field using the distance between your thumb and index finger.
3. High-Performance Rendering: Utilizes BufferGeometry and Additive Blending to render 10,000+ particles at a buttery-smooth 60 FPS.
4. Fluid Motion: Implements Linear Interpolation (lerping) and TWEEN.js for graceful, organic movement.

🚀 Tech Stack
Engine: Three.js (WebGL)
AI/ML: MediaPipe Hands
Animation: TWEEN.js
Language: JavaScript (ES6+), HTML5, CSS3
