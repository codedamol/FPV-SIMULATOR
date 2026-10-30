# FPV Flight Simulator

Browser-based fixed-wing FPV simulator for the SBS Rangsit drone program.

- **Tablet (iPad / Android):** tilt to fly. Left/right = roll, forward/back = pitch. Drag the left slider for throttle.
- **Laptop:** arrows = roll and pitch (up arrow = nose down), A/D = yaw, W/S = throttle, C = camera, R = reset.

Tilt sensors need HTTPS, so run it from GitHub Pages (or any https host), not from a local file.

## Run it
Enable GitHub Pages (Settings > Pages > Deploy from branch > `main` / root), then open the Pages URL on the tablet.

Built with [three.js](https://threejs.org/) (loaded from cdnjs). No build step.
