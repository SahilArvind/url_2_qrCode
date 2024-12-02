# URL QR Code Generator
This project provides a straightforward way for users to generate QR codes for URLs. By simply entering the desired URL and clicking a button, users can quickly obtain a QR code representation of the URL. The application validates the input URL format and dynamically generates the QR code using JavaScript and the QRCode.js library.

## Usage

1. Enter the URL you want to generate a QR code for in the input field.
2. Click the "Generate QR Code" button.
3. The QR code will be displayed below the input field.

## Features

- Validates input URL format.
- Generates QR code dynamically based on user input.

## Technologies Used

- HTML
- CSS
- JavaScript
- QRCode.js (a library for generating QR codes)

## How to Run

### Option 1: Download ZIP

1. Download the ZIP file from the [GitHub repository](https://github.com/SahilArvind/url_2_qrCode).
2. Extract the ZIP file to your desired location.
3. Open the extracted folder.
4. Double-click the `index.html` file to open it in a web browser.

### Option 2: Clone the Repository

1. Clone the repository using the following command in your terminal or command prompt:
``` 
git clone https://github.com/SahilArvind/url_2_qrCode.git 
```
2. Navigate to the cloned directory:
``` 
cd url_2_qrCode
```
3. Open the `index.html` file in a web browser.

## Allowed Input

- Valid URLs starting with 'ftp://', 'http://', or 'https://'
- URLs must not contain spaces or special characters.

### Examples

- Valid: https://www.example.com
- Valid: http://subdomain.example.com/page
- Valid: ftp://ftp.example.com
- Invalid: www.example.com (missing protocol)
- Invalid: http://www example com (contains spaces)
- Invalid: https://www.example.com/page with space (contains space)

## Preview

![URL QR Code Generator](preview.png)

## Support and Contributions