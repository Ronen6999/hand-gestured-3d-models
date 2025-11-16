# Hand gestured controlled 3D Model

Control 3D models using hand gestures and voice commands in real-time.

An interactive web app built with Three.js, MediaPipe computer vision, Web Speech API, and Rosebud AI.

## Features

- Say "drag", "rotate", "scale", or "animate" to change the interaction mode
- Pinch fingers to control the 3D model
- Use hand gestures to select interaction mode buttons
- Drag and drop new 3D models onto the page to import them (GLB/GLTF format)

## Requirements

- Modern web browser with WebGL support
- Camera access for hand tracking
- Microphone access for voice commands

## Technologies

- **Three.js** - 3D rendering
- **MediaPipe** - Hand tracking and gesture recognition
- **Web Speech API** - Speech recognition
- **HTML5 Canvas** - Visual feedback
- **JavaScript** - Real-time interaction

## Setup for Development

```bash
# Serve with your preferred method (example using Python)
python -m http.server
```

Then navigate to `http://localhost:8000` in your browser.

## License

MIT License - Open Source

## Credits

- Three.js - https://threejs.org/
- MediaPipe - https://mediapipe.dev/
- Rosebud AI - https://rosebud.ai/
- Quaternius 3D models - https://quaternius.com/

## Author

This is an open source project created and maintained by the repository owner.
