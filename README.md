# Captcha Solver Web Application

## Overview

This web application provides a simple, responsive interface for recognizing text from CAPTCHA images via a simulated OCR process. The app is built with plain HTML, Tailwind CSS for styling, and embedded JavaScript for functionality.

## Features

- Enter a URL of a CAPTCHA image or use the default sample image.
- Click the 'Solve' button to simulate OCR recognition.
- View the recognized text in a read-only textarea.
- Reset the form to recognize another image.

## Usage

1. Open the `index.html` file in a modern web browser.
2. Enter the URL of the CAPTCHA image you want to recognize, or leave it blank to use the default sample.
3. Click the 'Solve' button. The recognized text will appear after a short delay.
4. Click 'Reset' to clear the input and output fields.

## Notes

- This implementation uses a mock OCR function for demonstration purposes. To perform real OCR, consider integrating with an API like Tesseract.js.
- The default sample image is a randomly selected photo from Unsplash, serving as a placeholder.

## License

This project is licensed under the MIT License.

---

## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.