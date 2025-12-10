# Intelligent Snooker Video Analyzer

An AI-powered Tools that turns ordinary snooker footage into professional-grade insights. It automatically detects every shot, tracks cue ball path, and generates cinematic highlights in seconds.

Built for clubs, academies, and passionate players, it delivers instant real-time playback and detailed shot review - helping you quickly spot execution errors, receive improvement suggestions, and track progress. With one click, create and share thrilling highlights with friends, bringing the joy of snooker to everyone who loves the game.

# [Snooker Video Analyzer Demo](https://aisnooker.github.io/AISnooker/)
🚀 [Live online demo](https://aisnooker.github.io/AISnooker/) showcasing robust snooker shot detection, automated highlight generation, and precise cue ball tracking—tested across diverse cameras, angles, and lighting conditions.

**Highlights**  
- 8 built-in demo videos covering real-world extremes: Championship broadcasts with professional gear, club IP cameras, and poor lighting at home — all processed perfectly, zero calibration required
- Upload and test your own local snooker videos instantly — see for yourself how the analyzer handles any footage flawlessly, right in your browser  
- Automatic extraction of every shot as short, share-ready clips
- Cue ball tracking with smooth running path visualization
- Fully client-side with TensorFlow.js — no video uploads, no server, no calibration, just instant real-time analysis in your browser

**Tech Highlights**
- Two high-accuracy table & ball detection models trained with YOLOv8
- Full inference runs directly in the Chrome browser using TensorFlow.js (no server needed)
- Ultra efficient shot-detection algorithm enables true real-time processing of video streams

**Performance ( test video of 3:30 duration )**

- Intel 1.6 GHz Intel Core i5, integrated graphics: 1:09, processes in < 33% of video duration
- Intel 1.8 GHz Intel Core i7, integrated graphics: 59 seconds, processes in 28% of video duration
- iMac M4 8 Core CPU/GPU: 13 seconds, processes in 6% of video duration

Real-time capable on most modern PCs — entirely in the browser

