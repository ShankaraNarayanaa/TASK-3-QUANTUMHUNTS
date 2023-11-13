# Image Resizer Web Application

This web application is a simple Image Resizer built using HTML, Bootstrap, and JavaScript/jQuery. It allows users to display a set of images with a predefined height and adds a small icon at the center of each image.

## Features

- **Responsive Design**: The web application is designed to be responsive and works well on different devices and screen sizes.

- **Bootstrap Integration**: The application utilizes Bootstrap 4.5.2 for styling, providing a clean and modern appearance.

- **Image Display**: Images are displayed in a grid layout with a fixed height of 300 pixels. The background size, position, and repeat are adjusted for optimal display.

- **Center Icon**: A small icon (HTML5.png) is added to the center of each image using absolute positioning. The size of the icon can be adjusted in the CSS.

- **Easy Image Management**: Images are managed dynamically through JavaScript, making it easy to add or remove images from the display.

## Usage

1. Clone or download the repository to your local machine.

2. Open the `index.html` file in a web browser.

3. The web page will display a grid of images with the specified height and a centered icon.

## Customization

- **Image List**: You can customize the list of images displayed by modifying the `images` array in the JavaScript section of the HTML file.

- **Icon Size**: Adjust the size of the centered icon by changing the width property in the `.center-icon` CSS class.

- **Background Height**: Modify the `height` property in the `.image-container` CSS class to change the height of the image containers.

## Dependencies

- [Bootstrap](https://getbootstrap.com/) (v4.5.2)
- [jQuery](https://jquery.com/) (v3.5.1)
- [Popper.js](https://popper.js.org/) (v2.11.6)

## Credits

- The application uses Bootstrap for styling.
- The centered icon is provided by the HTML5.png image.

Feel free to explore, modify, and use this web application for your projects! If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.