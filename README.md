## Chessboard Object Detection and Analysis

This project is a Python-based application that uses computer vision and machine learning to detect chess pieces on a physical chessboard, map their positions, and analyze the game state. By integrating OpenCV for image processing, the Roboflow inference API for object detection, and chess APIs for move analysis, the project provides a comprehensive solution for chessboard detection and game analysis.

Features
- Real-Time Object Detection: Leverages Roboflow's inference API to detect and classify chess pieces on a physical board.
- Chessboard Perspective Transformation: Automatically adjusts for camera angle distortions to ensure accurate piece mapping.
- FEN Notation Generation: Converts detected piece positions into Forsyth-Edwards Notation (FEN) for use with chess engines.
- Move Suggestion: Integrates with chess APIs to provide optimal move suggestions based on the current board state.
- Visualization: Uses Python-Chess and SVG rendering to display the chessboard state and highlight suggested moves.
- Real-Time Video Processing: Captures and processes live video from a webcam for continuous chessboard analysis.

Technologies Used
- Programming Languages: Python
- Libraries: OpenCV, NumPy, Matplotlib, Python-Chess
- APIs: Roboflow inference API, Chess API for move analysis
- Tools: Perspective transformation, corner detection, and image annotation

Use Cases
- Analyze ongoing chess games with a physical board in real time.
- Train or practice chess by getting AI-recommended moves.
- Enhance computer vision skills with practical applications in game analysis.
