# Geometric Optics Virtual Laboratory

An interactive browser-based simulation for exploring **geometric optics**. This virtual lab lets you experiment with convex and concave lenses, visualize ray tracing in real time, and observe how image properties change as you adjust physical parameters.

Built for students, educators, and curious minds who want to *see physics think*.

---

## Overview

This project simulates thin-lens imaging using the **Gaussian lens formula**:

[
1/f = 1/u + 1/v
]

Adjust object distance, focal length, and object height to observe how the image changes. The simulation dynamically renders:

* Principal rays
* Image position and size
* Real vs virtual behavior
* Magnification and orientation

The goal: turn abstract equations into visual intuition.

---

## Features

**Lens Modes**

* Convex lens
* Concave lens

**Interactive Controls**

* Adjustable focal length
* Adjustable object distance
* Adjustable object height
* Drag-and-drop object positioning
* Drag focal points directly on canvas

**Real-Time Physics**

* Instant image distance calculation
* Magnification display
* Image height calculation
* Property indicators:

  * Real / Virtual
  * Upright / Inverted
  * Magnified / Reduced

**Visualization**

* Principal axis and coordinate grid
* Accurate ray tracing:

  * Parallel ray → through focal point
  * Central ray → straight through
  * Focal ray → exits parallel (convex)
* Dashed extensions for virtual images

**Extras**

* One-click demo mode
* Reset controls
* Live coordinate display
* Responsive layout
* Touch support for mobile/tablet

---

## How It Works

The simulation uses the **thin lens equation**:

```
v = (f × u) / (u − f)
Magnification (M) = −v / u
Image height = |M| × object height
```

Convex lens behavior:

* Object beyond 2f → real, reduced, inverted
* Between f and 2f → real, magnified, inverted
* Inside f → virtual, upright

Concave lens behavior:

* Always virtual
* Always upright
* Always reduced

Canvas rendering updates continuously as parameters change.

---

## Controls

* **Drag the orange object** to change object distance
* **Drag focal markers** to change focal length
* Use sliders for precise adjustments
* Switch between **convex** and **concave**
* Click **Reset** to return to default values
* Click **Help** for quick physics guidance

---

## Tech Stack

* HTML5 Canvas
* Vanilla JavaScript
* Tailwind CSS (CDN)
* Google Fonts:

  * Space Grotesk
  * JetBrains Mono

No frameworks. No build step. Just open and run.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/geometric-optics-lab.git
```

Open the project:

```bash
cd geometric-optics-lab
```

Then open:

```
index.html
```

in your browser.

That’s it. Zero dependencies. Physics at the speed of curiosity.

---

## Use Cases

* Physics classroom demonstrations
* Self-study for optics
* Concept visualization for students
* Interactive teaching tool
* Science outreach or exhibitions

---

## Accessibility

* Reduced motion support for users with motion sensitivity
* Touch interaction for mobile devices
* Responsive layout for different screen sizes

---

## License

MIT License

© 2026

---

## Future Ideas

* Mirror simulations
* Multiple lens systems
* Wave optics mode
* Measurement tools
* Export snapshots
* Classroom preset scenarios

---

## Why This Exists

Equations tell you *what* happens.
Visualization tells you *why*.

When the rays move and the image flips in front of your eyes, geometric optics stops being math and starts being intuition.

Physics is a visual language. This lab is a translator.
