# TaskGlitch

Live demo: https://task-glitch-inky.vercel.app

## About
TaskGlitch is a small task manager for sales teams. It tracks revenue, time taken, ROI, priority, and status.

## Bugs Fixed (Assignment)
I fixed the 5 required bugs:
1) Double fetch on page load (data loaded twice).
2) Undo snackbar kept old deleted task (stale undo).
3) Unstable sorting when ROI and priority were the same.
4) Edit/Delete opened the view dialog due to event bubbling.
5) ROI errors (NaN/Infinity and inconsistent formatting).

## Tech Stack
- React + TypeScript
- Vite
- MUI

## Run Locally
1) Install deps: `npm install`
2) Start dev server: `npm run dev`
3) Build: `npm run build`
