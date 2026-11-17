# Neon Spiral Galaxy (Python Turtle)

A procedural generative art script built with Python's `turtle` graphics module that renders a tilted, multi-layered neon spiral galaxy complete with deep-space background stars, cosmic dust clouds, four logarithmic spiral arms, a glowing galactic core, and bright starlight sparkles.

---

## Features

* **Procedural Generation:** Uses Gaussian distributions and trigonometric rotation to organically scatter stars, dust, and spiral arms.
* **Dynamic Neon Color Gradient:** Transitions smoothly across the HSV color spectrum from warm gold/amber in the core to electric cyan, blue, and violet along the outer arms.
* **3D Perspective Tilt:** Compresses the vertical axis and applies a rotational matrix (`TILT`) to give the 2D canvas a tilted 3D viewing angle.
* **Configurable Animation Speed:** Uses `screen.tracer()` to control rendering speed—allowing anything from a step-by-step live drawing animation to an instantaneous render.

---

## Requirements

* **Python 3.x**
* Standard library modules only (no external `pip` installations required):
  * `turtle` (Note: On Linux, ensure `python3-tk` is installed)
  * `colorsys`
  * `math`
  * `random`

---

## Usage

1. Save the script as `neon_galaxy.py`.
2. Run the script from your terminal or IDE:

```bash
python neon_galaxy.py
