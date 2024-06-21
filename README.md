# MCG QR Code Generator

This is a custom QR code generator built with React, Vite, and Bun. It allows users to create and download QR codes with customizable URL, colors, logo, margin size, and additional text. The project is deployed to GitHub Pages using GitHub Actions.

[View the live project](https://drikusroor.github.io/mcg-qr-codes/)

![MCG QR Code Generator Screenshot](screenshot.png)

## Features

- Generate QR codes with customizable URL, foreground color, and background color.
- Add a logo to the center of the QR code by URL or by uploading an image.
- Customize the margin size of the QR code.
- Add a subtext below the QR code.
- Download the generated QR code in PNG, JPG, or SVG format.

## Technologies Used

- React
- Vite
- Bun
- Tailwind CSS
- qrcode.react
- html-to-image
- downloadjs
- GitHub Actions for CI/CD

## Getting Started

### Prerequisites

- Node.js (v14 or above)
- Bun (v0.1.0 or above)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/drikusroor/mcg-qr-codes.git
   cd mcg-qr-codes
   ```

2. Install the dependencies:

   ```sh
   bun install
    ```

### Development

1. Start the development server:

   ```sh
   bun run dev
   ```

2. Open [http://localhost:5173/mcg-qr-codes/](http://localhost:5173/mcg-qr-codes/) in your browser.

### Production

1. Build the project:

   ```sh
   bun run build
   ```
