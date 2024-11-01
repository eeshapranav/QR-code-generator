URL to QR Code Generator:
This Node.js application takes a user-entered URL and generates a QR code image for it. The URL is also saved in a .txt file for reference.

Project Overview:
The application performs the following:

User Input: Uses the inquirer package to prompt the user to input a URL.
QR Code Generation: Converts the URL into a QR code image using the qr-image package.
File Storage: Saves the entered URL in a text file using Node’s native fs module.

Prerequisites:
Node.js: Ensure you have Node.js installed on your machine.
npm: The required packages (inquirer and qr-image) can be installed via npm.

Installation:
Clone the repository:
git clone <repository-url>
Install the dependencies:
npm install inquirer qr-image

Usage:
Run the program:
node app.js
Follow the prompt to enter a URL.
The application will generate:
A qr_image.png file containing the QR code for the URL.
A URL.txt file containing the original URL.

Dependencies:
inquirer - For command-line user input.
qr-image - For generating QR code images.
fs - Node.js native module for file system operations.
