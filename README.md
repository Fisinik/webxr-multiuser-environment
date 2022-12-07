# WebXR Multiuser Environment

The project showcases the University of Prishtina in the immersive world of Virtual Reality. It supports multiuser environment to make the interaction more fun. You can watch the other users as spherical avatars with big eyes, but don't stare at them for too long! 

## Technologies
This application uses [**A-Frame**](https://aframe.io/), a web framework for building 3D/AR/VR experiences built on top of Three.js specifically for WebXR. The server that handles the directional data is built with [**Express.js**](https://expressjs.com/), [**Open-EasyRTC**](https://github.com/open-easyrtc/open-easyrtc) and [**Networked-AFrame**](https://github.com/networked-aframe/networked-aframe/).

## Getting Started
To run the examples on your own PC:
```bash
git clone https://github.com/Fisinik/webxr-multiuser-environment  # Clone the repository.
cd webxr-multiuser-environment
npm install  # Install dependencies.
npm start  # Start the local development server.
```
With the server running, browse the examples at http://localhost:8080. Open another browser tab and point it to the same URL to see the other client.

## Demo
Click [**HERE**](https://glitch.com/~webxr-multiuser-environment) for the demo of the website. Alternatively, a snapshot of the scenery is provided below.



![Screenshot_7](https://user-images.githubusercontent.com/24959316/206233842-fdbf5f8b-0a67-47bc-bb86-75331a4def32.png)
