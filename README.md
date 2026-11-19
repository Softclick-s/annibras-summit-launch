# An-Nibrās Institute: "The Journey has Started" (summit launch animation)

A 16-second animated version of the An-Nibrās Institute 2-day Qur'an Summit launch flyer.
Live page: https://annibraas-summit-launch.netlify.app

## Who made what
- **Artwork and direction: Abdulgafar Quareeb.** Designed the original flyer and its layers (background, rocket, logo). Directed the layout, the rocket's angle, size and placement, and the text positions.
- **Animation code: written by Claude (AI)** from Abdulgafar's brief and revisions. Abdulgafar directed and reviewed the result.
- This is not hand-written code by the designer, and it is shared openly as AI-assisted work.

## What it renders
- Kinetic headline type ("The Journey has Started!"), paragraph reveals and a handle pill.
- A rocket that launches in along its own axis, with light streaks and smoke puffs drawn on an HTML5 `<canvas>`.
- A closing card that shows the original flyer with a design credit.

## What drives the output
- `CFG` in the script: handle, total length, launch time, text lines and designer name.
- In `play()`: the rocket's angle (`ANG`), travel distance and speed, and the particle settings (how many streaks, their speed, length and lifetime).
- CSS keyframes and per-word `animation-delay` values control the text timing.

## Export
Not exported to a video file. It runs live in the browser (HTML + CSS + JavaScript, no libraries). It can be screen-recorded if a video copy is needed. Remotion and FFmpeg were not used.

## Files
- `index.html`: the whole piece (images are embedded, so it works on its own).
