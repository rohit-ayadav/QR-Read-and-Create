# QR Code Scanner and Generator

This project provides a simple web application that allows users to scan QR codes and generate their own QR codes. It utilizes JavaScript libraries for QR code scanning (`jsQR`) and QR code generation (`QRCode.js`).

## Features

- **QR Code Scanning**: Uses the device camera to scan QR codes and display the result.
- **QR Code Generation**: Allows users to enter text or a URL to generate a QR code.
- **Copy to Clipboard**: Users can copy the scanned QR code data to their clipboard.
- **Google Search**: Users can search the scanned QR code data on Google.
- **Save QR Code**: Save generated QR codes as images to your device.
- **Share QR Code**: Share generated QR codes using the Web Share API (if supported by the browser).

## Technologies Used

- HTML5
- CSS3
- JavaScript
- QRCode.js (for generating QR codes)
- jsQR (for scanning QR codes)

## How to Use

1. **Scan QR Code**:
   - Click the **Start Scanning** button to start the camera.
   - Align a QR code in front of your camera.
   - The scanned QR code's data will be displayed on the screen.

2. **Generate QR Code**:
   - Enter text or a URL in the input box and click **Generate QR Code**.
   - The corresponding QR code will be generated and displayed.

3. **Additional Features**:
   - After scanning or generating a QR code, you can:
     - **Copy to Clipboard**: Copy the QR code's data to your clipboard.
     - **Search on Google**: Search the QR code's data on Google.
     - **Save QR Code**: Save the generated QR code as a PNG image to your device.
     - **Share QR Code**: Share the generated QR code via supported platforms.

## Installation

1. Clone or download the repository.
2. Open the `index.html` file in a web browser.
