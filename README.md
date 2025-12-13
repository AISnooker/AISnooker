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

**Technique**
- Two high-accuracy table & ball detection models trained with YOLOv8
- Full inference runs directly in the browser using TensorFlow.js (100 % client-side, no server)
- Ultra efficient shot-detection algorithm enables true real-time processing of video streams

**Performance ( test video of 3:30 duration )**

- Intel 1.6 GHz Intel Core i5, integrated graphics: 1:09, processes in 33% of video duration
- Intel 1.8 GHz Intel Core i7, integrated graphics: 59 seconds, processes in 28% of video duration
- iMac M4 8 Core CPU/GPU: 13 seconds, processes in 6% of video duration

**Pool Ball Support**
- [Live Pool Ball demo](https://aisnooker.github.io/AISnooker/poolball/) – currently optimized for classic green and blue tables
- 8 build-in demo videos covering popular styles: American 9-Ball and Chinese 8-Ball (Hey Ball)
- Note: Some striped balls are visually very close to the cue ball → cue ball tracking accuracy is currently limited. Improved models are in active development!

# Real-time Snooker Replay System (Desktop Demo)

Want to experience the full club-grade real-time replay system? 

We provide a ready-to-run desktop demo for macOS / Windows / Linux that turns any IP camera into an instant shot analysis station.

- Connect directly to IP camera via RTSP stream
- Runs locally using Node.js + Chrome
- Instant replay the moment a shot is played
- Cue ball path visualization
- Browse, select, and download highlight clips on the spot

Interested in trying the desktop demo?
[**Contact us**](https://forms.gle/Ce2q3s13YcxZZXv88)

# Product & Commercial Cooperation

We’re actively seeking partners to bring AISnooker to snooker/pool clubs, academies, training platforms.

- Real-time shot analysis & instant replay systems for clubs
- Automated highlight clips with one-click download and social sharing
- Supports snooker and pool ball
- White-label web/app integration — run under your own brand and domain
- Custom deployment (on-premise or cloud)

**Technique**

- Built with Java – runs on Linux for maximum stability and performance
- A compact mini PC (Intel Core i7 + 8 GB RAM) can smoothly handle **4 concurrent 720p 30fps streams**
- Supports live RTSP streams or automatic segmented recording/download from IP cameras
- All processing done locally – ultra-low latency, no cloud dependency

Interested in collaboration or commercial licensing?
👉 [**Contact us now**](https://forms.gle/Ce2q3s13YcxZZXv88)

<!--
# Technical Challenges

Developing a real-time snooker analyzer with no calibration required was no easy feat. Here are some of the toughest hurdles we overcame:

- Image detection accuracy is not high enough
- Image detection is time-consuming, on Intel 1.6 GHz Intel Core i5, it take 200ms
- Ball movement is hard to define

If you're a computer vision geek, or just love deep technical dives, you'll enjoy this: [Technical Challenges of Snooker Video Analyzer](https://aisnooker.github.io/AISnooker/challenges.html)
!>
