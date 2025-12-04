# Newton vs Einstein: Orbital Simulation

A visual and interactive simulation comparing classic Newtonian gravity with a Post-Newtonian correction that demonstrates orbital precession.

## Overview

This project simulates two planets orbiting a central sun starting from **identical initial conditions** (position and velocity).

- **Planet 1 (Blue)** follows standard Newtonian mechanics, resulting in a closed elliptical orbit.
- **Planet 2 (Pink)** includes a Post-Newtonian correction term ($C/r^3$), which causes the orbit to precess over time, creating a beautiful "rosette" pattern similar to the famous precession of Mercury's perihelion.

## Features

- **Real-time Physics Rendering**: Smooth HTML5 Canvas animation.
- **Visual Comparison**: Direct side-by-side visualization of stable vs. precessing orbits.
- **Interactive Controls**:
  - **Speed Control**: Toggle between 1x, 2x, 5x, and 10x simulation speeds.
  - **Trails**: Toggle orbital trails on/off to visualize the path history.
  - **Restart**: Instantly reset the simulation to initial conditions.
- **Responsive Design**: Layout adapts for desktop and mobile viewing.

## The Physics

### Newtonian Orbit (Blue)

The blue planet follows the classic inverse-square law of gravity:
$$F = \frac{G M m}{r^2}$$
In a perfect two-body Newtonian system, bound orbits are closed ellipses. The planet returns to the exact same point in space after every revolution.

### Post-Newtonian "Rosette" Orbit (Pink)

The pink planet is subject to a perturbed force law that mimics Einstein's General Relativistic effects:
$$F = \frac{G M m}{r^2} + \frac{C}{r^3}$$
The additional $1/r^3$ term makes gravity slightly stronger when the planet is closest to the sun (perihelion). This prevents the orbit from closing perfectly, causing the ellipse to rotate (precess) slightly with each pass, tracing out a rosette shape.

## Controls

| Control                | Description                                                 |
| :--------------------- | :---------------------------------------------------------- |
| **Restart Simulation** | Resets planets to their starting positions.                 |
| **Toggle Trails**      | Turns the orbital path lines on or off.                     |
| **Speed**              | Cycles simulation speed: 1x &rarr; 2x &rarr; 5x &rarr; 10x. |

## Usage

1.  Clone or download the repository.
2.  Open `index.html` in any modern web browser.
3.  No installation or server required!

## Link

https://lugawplain.github.io/Newton-vs-Einstein-Orbital-Simulation/
