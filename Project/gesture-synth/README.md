# Gesture Synth

[![Live Demo](https://img.shields.io/badge/Live-View_Demo-blue)](https://gesture-synth-delta.vercel.app/)
> **🌐 Website:** [https://gesture-synth-delta.vercel.app/](https://gesture-synth-delta.vercel.app/)
> **👉 Demo Videos:** [Watch here!](https://gesture-synth-delta.vercel.app/demo.html)

A camera-based musical instrument that lets you control chords, tone, and expression using hand gestures.

## Features
- Left hand controls chord selection
- Right hand controls voicing and expression
- Real-time hand tracking with MediaPipe
- Web Audio API synthesis

## Built With
- JavaScript
- MediaPipe Hand Landmarker
- Web Audio API
- Vite

## Credit
Created by Raghuvaran.

## How to Use

Use your hands in front of the webcam to create chords, melodies, and sounds in real-time!

### Left Hand (Chord Selection & Scale Degree)
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

### Right Hand (Voicing & Expression)
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
