# rtsp-recorder

rtsp-recorder is a Python-based application that allows you to record and playback video streams from RTSP cameras. It provides functionality for recording video, detecting motion, and playing back recorded videos.

## Project Structure

The project consists of the following files and directories:

- `files_handler/`: Contains files related to handling files and directories.
  - `dir_size.py`: Calculates the size of a directory.
  - `storage_handler.py`: Manages storage for recorded videos.

- `detection/`: Contains files related to motion detection.
  - `motion.py`: Implements motion detection algorithms.

- `recorder/`: Contains files related to video recording.
  - `recorder.py`: Handles the recording of video streams.

- `playback/`: Contains files related to video playback.
  - `playback.py`: Implements the video player with support for fast forward and time slider.

- `main.py`: Main entry point of the application.

## Requirements

- Python 3.x
- OpenCV
- Pygame
- PyAudio (for audio playback, if needed)
