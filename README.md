# AI-Looks-Coach

An AI-powered system that analyzes facial and body features to provide personalized appearance insights and improvement suggestions.

## Overview

AI-Looks-Coach combines computer vision, machine learning, and user interaction layers to analyze facial and body data from images or video, then delivers tailored recommendations for appearance, styling, posture, and more.

## Key Capabilities

- Facial feature detection and analysis
- Body landmark extraction and posture evaluation
- Personalized appearance and styling suggestions
- Multi-component architecture for model serving, preprocessing, and frontend interaction

## Project Structure

- `FASTAPI/` - Backend API services, model endpoints, and request handling.
- `MAIN PROJECT/` - Core application logic, orchestration, or main deployment entrypoints.
- `MEDIAPIPE/` - MediaPipe models, landmark detection, and computer vision utilities.
- `OPENCV/` - OpenCV processing scripts and image/video analysis helpers.
- `PYTHON/` - Python utilities, preprocessing, and machine learning code.
- `REACT/` - Frontend interface for user interaction, visualization, and results display.

## Getting Started

1. Open the project root in VS Code.
2. Review the relevant subproject folder for installation and usage instructions.
3. Use the backend service in `FASTAPI/` together with the frontend in `REACT/` to build the complete experience.

## Notes

- This repository appears to be split into multiple specialized modules. Keep backend, computer vision, and frontend responsibilities separated for easier development.
- Add more detailed setup and run instructions to each module once the specific dependencies and project conventions are confirmed.
