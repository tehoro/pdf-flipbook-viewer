# PDF Flipbook Viewer

A simple, elegant PDF flipbook viewer that renders a single PDF file with page-turning animations.

## Features

- Renders PDF documents with realistic page-turning effects
- Responsive design that works on both desktop and mobile devices
- Single and double-page viewing modes
- Touch and mouse swipe gestures for page turning
- Keyboard navigation support
- Fullscreen mode
- Page slider for quick navigation

## Viewer for Sample Document
Check out the [sample document](https://tehoro.github.io/pdf-flipbook-viewer) to see the flipbook viewer in action

## Usage

1. Clone or download this repository
2. Replace `document.pdf` in the assets folder with your own PDF file (keep the same filename)
3. Make sure *not* to use CMYK colour (output for a book may use this) for the pdf file as the colours will look "off" 
4. Serve the directory using a web server
5. Open index.html in a browser

## Dependencies

This project uses:
- [Turn.js](https://www.turnjs.com/) for page-turning effects
- [PDF.js](https://mozilla.github.io/pdf.js/) for PDF rendering

## License

This project is licensed under the MIT License - see the LICENSE file for details
