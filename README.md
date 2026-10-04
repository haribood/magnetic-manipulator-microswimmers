# Magnetic Manipulator & Microswimmers

University research on magnetic actuation, vision-based position tracking, and feedback control of untethered microswimmers.

![Magnetic manipulator](https://haribood.github.io/magnetic%20manipulator%201.png)

## Research overview

This project investigates microswimmers driven through fluid by rotating magnetic fields, with blood clot removal as the research motivation. My work focused on real-time control software, three-axis magnetic-field control, and dual-camera position tracking.

## Technical stack

| Technology | Role |
|------------|------|
| LabVIEW | Real-time control software |
| OpenCV | Computer vision and position tracking |
| PID feedback | Trajectory-tracking corrections |
| Three-axis magnetic-field control | Magnetic actuation |
| Dual-camera system | Position feedback |

## My contributions

- Developed real-time control software with PID feedback.
- Worked on three-axis magnetic-field control for microswimmer actuation.
- Integrated dual-camera position tracking into the control workflow.
- Improved trajectory tracking through feedback control.

## Feedback-control workflow

Camera observations provide position feedback. The control system compares the measured position with the desired trajectory and uses PID corrections to adjust magnetic actuation. This links visual tracking with motion control of the untethered swimmer.

## Reported result

Trajectory-tracking error decreased from approximately **10 mm to 5 mm**, an improvement of about **50%**, as reported in my portfolio.

This repository does not yet contain the experimental dataset or a detailed measurement protocol.

## Media and context

See the [portfolio project gallery](https://haribood.github.io/#projects) for additional media and project context.

## Repository status

This repository currently contains a public project overview. LabVIEW files, OpenCV source code, apparatus specifications, and calibration procedures have not yet been uploaded.

## Author

[Haridev Nambood](https://github.com/haribood) — electrical engineering student at the University of Houston.

[Portfolio](https://haribood.github.io/)
