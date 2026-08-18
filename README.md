# Computer Vision Projects

Welcome to the Computer Vision repository! This repository contains various implementations and projects related to CNNs, Object Detection, Transfer Learning, and more.

## Featured Project: Gesture Synth 🎹

[![Live Demo](https://img.shields.io/badge/Live-View_Demo-blue)](https://gesture-synth-delta.vercel.app/)
> **🌐 Website:** [https://gesture-synth-delta.vercel.app/](https://gesture-synth-delta.vercel.app/)
> **👉 Demo Videos:** [Watch here!](https://gesture-synth-delta.vercel.app/demo.html)

Inside the `Project/gesture-synth` folder, you will find a camera-based musical instrument that lets you control chords, tone, and expression using real-time hand gestures.

* **Tech Stack:** JavaScript, MediaPipe Hand Landmarker, Web Audio API, Vite
* **How it works:** It uses CNN-based hand tracking to map 3D hand landmarks to musical scales and audio distortion.

### How to Use the Gesture Synth
Use your hands in front of the webcam to create chords, melodies, and sounds in real-time!

#### Left Hand (Chord Selection & Scale Degree)
*   **Tilt**
    *   Inward → Major
    *   Outward → Minor
*   **Fingers (Scale Degree)**
    *   1 finger → I
    *   2 fingers → II
    *   3 fingers → III
    *   4 fingers → IV
    *   5 fingers → V
    *   Index + Pinky → VI
    *   Index + Pinky + Thumb → VII

#### Right Hand (Voicing & Expression)
*   **Fingers (Chord Quality)**
    *   1 finger → Root Position
    *   2 fingers → 1st Inversion
    *   3 fingers → Major/Minor 7th
    *   4 fingers → Dominant/Diminished 7th
*   **Octave**
    *   Thumb In → Higher octave
    *   Thumb Out → Lower octave
*   **Tilt**
    *   Inward → More Filter (Distortion)
    *   Outward → Less Filter
*   **Height**
    *   Higher → Louder
    *   Lower → Softer

---
*Created and contributed by Raghuvaran.*
