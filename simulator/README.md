# Film Logger Simulator — v0.2

Static browser prototype for the Film Exposure Logger interface.

## Controls

- **Left / Right:** select the editable field (Shutter or Aperture).
- **Up / Down:** cycle through the values for the selected field.
- **Select / Enter:** show the current selection/help.
- **Shot / Space:** log the current frame in the prototype and advance the frame counter.
- The selected field is highlighted with an inverse black-and-white display and an `EDIT` label.

## Run locally

Open `index.html` in a browser. No build tools or dependencies are required.

## Deploy to Vercel

Import the GitHub repository and set the project Root Directory to `simulator`. Use the `Other` framework preset with no build command and `.` as the output directory.

This is a UI prototype only. It does not yet save data to a file or communicate with the ESP32.
