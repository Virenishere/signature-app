# Signature App

A simple signature application created using HTML, CSS, and JavaScript. This app allows users to create digital signatures, save them using LocalStorage, and customize signature colors. It also uses the Canvas context (`ctx`) for drawing signatures and Bootstrap for responsive design.

## Features

- **Signature Drawing**: Users can draw their signatures on a canvas using simple mouse interactions.
- **Color Selection**: A color input selector allows users to pick custom colors for drawing.
- **Responsive Design**: Bootstrap is used to ensure the app adapts to different screen sizes.
- **Local Storage**: The app saves the user's signature locally in the browser, so it remains after refreshing.
- **Canvas Context Methods**: The app uses methods like `ctx.beginPath()`, `ctx.moveTo()`, `ctx.lineTo()`, `ctx.stroke()`, and `ctx.fillRect()` to draw lines and shapes dynamically.

## Technologies Used

- **HTML**
- **CSS**
- **JavaScript**
- **Bootstrap** (for responsive design)
- **LocalStorage** (for saving signatures)
- **Canvas Context (`ctx`)** (for drawing functionality)

## Canvas Methods Used

- `ctx.beginPath()` - Starts a new path for the signature.
- `ctx.moveTo(x, y)` - Moves the drawing cursor to a specific point (last known mouse coordinates).
- `ctx.lineTo(x, y)` - Draws a line from the last point to the current mouse position.
- `ctx.stroke()` - Renders the line on the canvas.
- `ctx.fillStyle = color` - Sets the color for shapes or lines.
- `ctx.fillRect(x, y, width, height)` - Draws a filled rectangle on the canvas, used to clear the canvas or create backgrounds.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Virenishere/signature-app.git
   ```

2. Open the `index.html` file in your browser.

3. Draw your signature, select a color, and save it!

## Usage

- Click and drag on the canvas to draw your signature.
- Choose your preferred color using the color input selector.
- The signature is automatically saved in LocalStorage and can be cleared or updated.


## License

This project is licensed under the MIT License.

---

This updated README now accurately reflects the usage of the canvas context methods like `ctx.beginPath()`, `ctx.lineTo()`, and `ctx.fillRect()` for drawing.