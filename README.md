# VisionAuth

VisionAuth is a simple web app that uses your webcam to find faces and show live guesses for emotion, age, and gender. All processing happens in your browser; nothing is saved or sent.

## Quick use
1. Serve the folder over HTTPS (or open via localhost).  
2. Open index.html in a modern browser.  
3. Allow camera access when prompted.  
4. Watch the live face analysis on screen.

## What it does (plain words)
- Finds faces in the camera view.  
- Shows one of seven emotions: Happy, Sad, Neutral, Surprised, Angry, Confused, Disgusted.  
- Gives an approximate age and a gender estimate.  
- Updates instantly as the face moves or expressions change.

## Privacy
- No images or videos are stored.  
- No face data is sent to servers.  
- Camera is used only while the page is open and you allow it.  
- Use over HTTPS for camera access.

## Tech
HTML, CSS, JavaScript, MediaPipe, TensorFlow.js

## Files
- index.html  
- styles.css  
- script.js  
- README.md  
- LICENSE
