# Geometric Optics Virtual Laboratory

Interactive simulation for exploring **thin lens physics** using real-time ray tracing.

**Live Demo:**
https://apiwishboon-spec.github.io/Geometric-Optics-Virtual-Laboratory/

---

## Overview

The Geometric Optics Virtual Laboratory is a browser-based simulation that allows students and educators to experiment with **convex and concave lenses** and observe image formation dynamically.

The simulation uses the **Gaussian thin lens equation**:

1/f = 1/u + 1/v

and calculates magnification:

M = −v/u

All results update instantly as parameters change.

---

## Features

* Convex and concave lens modes
* Real-time ray tracing visualization
* Adjustable parameters:

  * Focal length (f)
  * Object distance (u)
  * Object height (h)
* Displays calculated values:

  * Image distance (v)
  * Magnification (M)
  * Image height
  * Image type (Real / Virtual)
  * Orientation (Upright / Inverted)
  * Size (Reduced / Magnified)
* Drag-and-drop interaction:

  * Move object (candle)
  * Adjust focal points directly
* One-click demonstration mode
* Responsive canvas rendering
* No backend required

---

## How to Use

1. Select **Convex** or **Concave** lens.
2. Adjust parameters using sliders, or:

   * Drag the candle to change object distance
   * Drag focal markers to change focal length
3. Observe:

   * Ray paths
   * Image position and size
   * Image properties updating in real time

### Physics Behavior

**Convex Lens**

* Object beyond 2f → real, reduced image
* Object between f and 2f → real, magnified image
* Object inside f → virtual, upright image

**Concave Lens**

* Always produces a **virtual, upright, reduced** image.

---

## Technology

* HTML5 Canvas
* Vanilla JavaScript
* Tailwind CSS (CDN)
* Google Fonts
* Pure client-side rendering (no server)

---

## Project Structure

```
index.html
README.md
LICENSE
```

---

## Educational Purpose

This project is designed as a **visual learning tool** for:

* High school physics
* Introductory optics courses
* STEM demonstrations
* Self-study and experimentation

---

## License

This project is licensed under the **MIT License**.
See the `LICENSE` file for details.

---

## Author

Created by Boon
Open for learning, modification, and experimentation.
