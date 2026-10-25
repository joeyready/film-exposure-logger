# Film Logger Virtual Prototype — v0.1

Software-only prototype for the ESP32 film exposure logger.

## v0.1 goals

- Test the physical button layout
- Test basic navigation
- Test shutter/aperture selection
- Test frame counter
- Test SHOT behavior
- Work on desktop and phone browsers
- No backend or database required

## Controls

- Left / Right: change the currently selected exposure setting
- Up / Down: switch between shutter and aperture
- Select: placeholder for the future menu system
- Shot: log a frame and advance the counter
- Keyboard: arrow keys, Enter, and Space also work

## Deploying to Vercel

This is a static site and needs no build step.

1. Put `index.html` in a GitHub repository.
2. Import the repository into Vercel.
3. Use the default settings / no build command.
4. Deploy.

You can then share the Vercel URL with friends for feedback.
