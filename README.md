# Row Swap Lab — Determinants, Exercise 03

A standalone, interactive educational website for the matrix

```text
A = [ 1  2  0 ]
    [ 0  3  1 ]
    [ 2  1  1 ]
```

The lesson starts with general determinant theory, walks step by step through `det(A) = 6`, performs the first/second row swap and verifies `det(B) = -6`, and ends with a fully interactive matrix lab.

## Included

- Theory: oriented volume, alternating property, cofactor signs, row operations
- Animated seven-step solution and full written calculation
- Nine matrix sliders with optional direct integer entry
- Three interactive row-swap controls and matrix presets
- Cofactor expansion and Sarrus visual explorers
- Rotatable 3D parallelepiped (HTML Canvas, no external libraries)
- Adjustable rotation, tilt, animation speed, and theme color
- Three-question self-test

## Running locally

Open `index.html` in any modern browser. It works offline; no installation, build system, or external assets are required.

## Publishing on GitHub Pages

1. Add `index.html` to the root of a repository (and commit it).
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

All calculations and interactions run locally in the browser, without a server.
