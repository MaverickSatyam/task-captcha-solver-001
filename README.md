# Captcha Solver

This project provides a simple web-based application designed to display captcha images from a given URL and simulate their solving process. It serves as a demonstration of handling URL parameters, displaying images, and simulating asynchronous operations in a web environment.

## Features

*   **Dynamic Captcha Loading**: Displays a captcha image fetched from a URL provided as a query parameter (`?url=`).
*   **Default Image**: If no URL parameter is provided, a default placeholder image is displayed.
*   **Simulated Solving**: Simulates the captcha solving process, displaying a placeholder solution within 15 seconds.
*   **Responsive Design**: Utilizes Bootstrap 5 for a clean and responsive user interface.
*   **Clear Status Updates**: Provides real-time feedback on the captcha loading and solving status.

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

You only need a modern web browser to open the `index.html` file.

### Installation

1.  **Save the files:**
    Save the `index.html` and `README.md` files into a directory on your local machine.

2.  **Open `index.html`:**
    Navigate to the directory where you saved the files and open `index.html` in your preferred web browser.

## Usage

### Viewing the Default Captcha

Simply open `index.html` in your browser:

`file:///path/to/your/project/index.html`

This will display the default placeholder image and then simulate its solving.

### Specifying a Captcha Image URL

You can pass a URL to a captcha image using the `url` query parameter:

`file:///path/to/your/project/index.html?url=https://example.com/image.png`

Replace `https://example.com/image.png` with the actual URL of the captcha image you wish to display. The page will fetch and display this image, then proceed to simulate solving it.

## Limitations

*   **Simulated Captcha Solving**: This application does not perform actual OCR (Optical Character Recognition) or connect to an external captcha-solving API. The "solved captcha" text is a hardcoded placeholder and the solving time is simulated using a `setTimeout`.
*   **Default Image Content**: The `sample.png` content provided in the project brief was a highly truncated PNG header, not a complete, renderable image. Therefore, the application uses a generic 1x1 white PNG as a placeholder for the default image to ensure proper display functionality.

## License

This project is licensed under the MIT License. See the [LICENSE](#license) section for more details.

---

### MIT License

Copyright (c) 2024 Captcha Solver Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
