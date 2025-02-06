# PDF Generator from Images

This project allows you to generate a PDF document containing images found on a webpage using the [jsPDF](https://github.com/parallax/jsPDF) library.

## Features
- Converts images on the webpage into a PDF.
- Supports images with `blob:` URLs (commonly used for uploaded images).
- Creates a new page for each image in the PDF document.

## How to Use
1. Add the script to your webpage.
2. Ensure that there are `<img>` elements on the page with valid `src` attributes (starting with `blob:`).
3. When the page loads, the script will automatically detect and convert the images to a PDF.
4. The PDF will be saved as `Exported_File.pdf`.

## Installation
This script relies on the `jsPDF` library, which is included via a CDN:
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/1.5.3/jspdf.debug.js"></script>
