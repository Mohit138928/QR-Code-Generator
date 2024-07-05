# QR Code Generator using JavaScript

The QR Code Generator is a web application designed to assist users in generating QR codes quickly and easily. This project utilizes JavaScript and the [QR Code Generator API](https://goqr.me/api/) to create a user-friendly site for generating QR codes based on user input.

## Demo:
![Screenshot 2023-07-16 141114](https://github.com/Mohit138928/QR-Code-Generator/assets/63627791/72430fb0-c3d2-4f3a-8cd7-34cda87b82f8)
![Screenshot 2023-07-16 141155](https://github.com/Mohit138928/QR-Code-Generator/assets/63627791/af48ee16-e5fb-4c10-9b04-7eaff9d907fb)

## Demo of generating QR code 
https://mohit138928.github.io/QR-Code-Generator/

## Features:

- **QR Code Generation**: Users can input desired text or information, such as URLs, contact details, or any other text-based data, and th
e application generates a corresponding QR code.
- **Customization Options**: Users have the ability to customize the size of the generated QR code. They can input the desired size and see the preview of the QR code accordingly.
- **Qr Code API Integration**: The project utilizes the Qr Code API, specifically the following endpoint: `https://api.qrserver.com/v1/create-qr-code/?size=<size>&data=<text>`, where `<size>` represents the desired size of the QR code and `<text>` represents the input text or data. This integration simplifies the process of generating QR codes by leveraging the API's encoding and rendering capabilities.
- **Dynamic Updating**: Users can dynamically update the QR code as they make changes to the input size and text. The real-time updating feature allows users to preview and fine-tune the QR code before generating the final version.
- **Cross-Platform Compatibility**: The web application is designed to work seamlessly on various platforms and devices, including desktop computers, laptops, tablets, and mobile phones, ensuring a consistent user experience across different devices.

## Installation:

To run the QR Code Generator on your local machine, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
   Replace `<repository-url>` with the actual URL of the project's repository.

2. Navigate to the project directory:
   ```
   cd qr-code-generator
   ```

3. Launch the application:
   - If you have a live server setup, launch the server and specify the project directory as the root.
   - If you don't have a live server, you can use a local development server:
     - For Python users:
       ```
       python -m SimpleHTTPServer
       ```
     - For Node.js users:
       ```
       npm install -g http-server
       http-server
       ```

4. Access the application:
   Open your web browser and enter the following URL:
   ```
   http://localhost:<port>
   ```
   Replace `<port>` with the port number specified by your server (e.g., 8000).

## Usage:

1. Open the QR Code Generator in your web browser by accessing the URL mentioned in the installation steps.

2. Input the desired size and text into the respective fields provided.

3. As you type or make changes, the QR code preview will update in real-time.

4. Customize the size of the QR code using the provided input field.

5. Once satisfied with the size and text, you can use the generated QR code as needed. You can right-click on the QR code and choose to save it as an image or copy the URL for sharing or integration into other materials.

## License:

The QR Code Generator is open source software licensed under the MIT License.

## Contact:

For any questions, suggestions, or support, please feel free to contact the project maintainers at [Mohit Maurya](mauryamohit138@gmail.com).
