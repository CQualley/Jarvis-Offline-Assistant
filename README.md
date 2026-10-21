# Jarvis-Offline-Assistant
Offline Raspberry Pi voice assistant built with Python, Vosk, Piper TTS, and OpenWakeWord.

# JARVIS — Offline Raspberry Pi Voice Assistant

## Overview

Jarvis is a personal project I built using Python and a Raspberry Pi. My goal was to create a voice assistant that runs locally without relying on cloud services or an internet connection.

The project started as an assistant for my car, with plans to expand it into a home automation system.

## Features

- Offline voice recognition using Vosk
- Wake-word detection using OpenWakeWord
- Text-to-speech responses using Piper TTS
- Voice commands for music playback and volume control
- Modular Python plugin system
- Custom startup sequence and audio responses

## Technologies Used

- Python
- Raspberry Pi
- Linux
- Vosk Speech Recognition
- Piper Text-to-Speech
- OpenWakeWord
- USB microphone and speaker

## How It Works

1. Jarvis listens for its wake word.
2. After detecting "Jarvis," the system listens for a voice command.
3. Vosk converts speech into text locally.
4. The command system matches the recognized words to a supported function.
5. Jarvis executes the command and responds using Piper TTS.

All core speech processing happens locally.

## Current Development

The project is being developed in stages. Current work focuses on improving reliability, error handling, startup behavior, and voice interactions.

## Future Plans

- Improved command recognition
- Interruptible voice responses
- Offline memory and knowledge capabilities
- Smart home integration
- Vehicle OBD-II integration
- Additional sensors and camera support

## What I Learned

This project has helped me gain experience with Python development, Linux, audio devices, speech recognition, modular software design, and troubleshooting hardware and software integration.

It has also taught me how to build a system that works without depending on an external cloud service.

## Project Status

Work in progress — initial voice assistant functionality implemented.
