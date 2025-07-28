# Beat Counter & Marker

Live Demo: [https://beat-counter.netlify.app/](https://beat-counter.netlify.app/)

## Overview
Beat Counter & Marker is a modern, mobile-friendly web tool for musicians, producers, and audio editors to mark, count, and manage beats in any audio file. It is designed for ease of use, fast workflow, and robust beat management, supporting both desktop and mobile devices.

### Features
- **Audio Beat Marking:** Mark beats in real-time while playing any audio file.
- **BPM Support:** Enter and manage BPM (beats per minute) for accurate beat calculation.
- **Visual Beat List:** View, edit, and delete marked beats in an interactive list.
- **Import/Export:** Save and load your beat markers as JSON files (including BPM value) for easy sharing or backup.
- **Warnings & Validation:** Get instant feedback for invalid actions (e.g., missing BPM, no audio loaded).
- **Keyboard & Touch Shortcuts:** Mark beats with keyboard (Space), export/import with Ctrl+E/Ctrl+I, and swipe up on mobile.
- **Modern UI/UX:** Responsive, glassmorphism-inspired design with smooth animations and accessibility in mind.

### How to Use
1. **Enter BPM** (beats per minute) in the input field.
2. **Select an audio file** (any supported format).
3. **Play the audio** and use the "Mark This Beat" button, Space key, or swipe up (mobile) to mark beats.
4. **Edit or delete** beats directly from the beat list.
5. **Export** your beat markers as a JSON file, or **import** a previously saved file (BPM included).

### Data Format
Exported/imported JSON files have the following structure:
```json
{
  "bpm": 120,
  "beats": [1, 5, 9, ...]
}
```

---
Created by DanyZaky.
