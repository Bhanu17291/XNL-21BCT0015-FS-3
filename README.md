# Real-time Drone Surveillance Integration

This project integrates autonomous drones with real-time video streaming and processing capabilities. The system captures live video feeds of traffic, pollution, and infrastructure using drones, processes the feed to detect relevant objects, and streams the data to a web interface for real-time monitoring.

## Features

- **Autonomous Drone Control**: Using DJI SDK (or another SDK like PX4), the drone can autonomously move, capture video feeds, and monitor infrastructure.
- **Real-time Video Streaming**: The drone streams live video via RTSP, which is captured and processed in real-time.
- **Object Detection**: Traffic and pollution are detected using pre-trained models like YOLO for object detection on video frames.
- **Web Interface**: A real-time web interface to display the live video feed and object detection results.
- **WebSocket Communication**: Video frames are transmitted from the backend to the frontend using WebSockets for low-latency, real-time streaming.

---

## Prerequisites

Before starting, ensure you have the following installed:

- **Python 3.x** (for drone control and video processing)
- **Node.js** (for the WebSocket server and web frontend)
- **DJI SDK or PX4/ArduPilot** (depending on the drone platform you are using)
- **OpenCV** (for video capture and processing)
- **TensorFlow or PyTorch** (optional, for advanced AI model integration like traffic or pollution detection)

### Python Libraries:

Install required Python libraries:

```bash
pip install opencv-python dji-sdk
