# pj-2
image sliding using radio button by HTML, CSS
# Image Slider with Radio Button

![1](https://github.com/abdul-1432/pj-2/assets/124916666/285a5eaa-5404-44aa-b092-a8c69387adf0)
![2](https://github.com/abdul-1432/pj-2/assets/124916666/879e8b8c-0ba2-4d0a-9efd-4b12dd80f7a3)
![3](https://github.com/abdul-1432/pj-2/assets/124916666/09303cbf-43ea-49c8-b055-2b5b1a022b0d)
![4](https://github.com/abdul-1432/pj-2/assets/124916666/2c5eaf45-fd0a-439e-a25f-6709dfb404c3)

## Demo
You can see the web page here [Demo](https://codepen.io/abdul-1432/pen/XWyZpjv?editors=1100)

This repository contains an image slider with radio buttons, a simple and intuitive way to navigate through a collection of images. The slider provides a visual representation of the available images and allows users to select specific images using radio buttons.

## Features

- Display multiple images in a slider format
- Radio buttons for easy image selection
- Smooth transitions between images
- Fully responsive design
- Customizable styles and settings
- Keyboard navigation support
- Support for touch gestures on mobile devices
- Extensive documentation and examples

## Getting Started

To get started with the image slider, follow these steps:

1. **Clone the repository**: Use the following command to clone this repository to your local machine:

   ```shell
   git clone https://github.com/your-username/image-slider-radio-button.git
   ```

2. **Include the necessary files**: Include the CSS and JavaScript files required for the image slider in your HTML file.

   ```html
   <link rel="stylesheet" href="path/to/slider.css">
   <script src="path/to/slider.js"></script>
   ```

3. **Create HTML markup**: Create the HTML markup for your image slider and radio buttons. Each radio button should correspond to an image in the slider.

   ```html
   <div class="slider">
     <div class="slider-container">
       <img src="path/to/image1.jpg" alt="Image 1">
       <img src="path/to/image2.jpg" alt="Image 2">
       <!-- Add more images -->
     </div>
     <div class="radio-buttons">
       <input type="radio" name="slider" id="radio1" checked>
       <input type="radio" name="slider" id="radio2">
       <!-- Add more radio buttons -->
     </div>
   </div>
   ```

4. **Initialize the image slider**: Initialize the image slider using the following JavaScript code:

   ```javascript
   const sliderContainer = document.querySelector('.slider-container');
   const radioButtons = document.querySelectorAll('.radio-buttons input');

   radioButtons.forEach((radio, index) => {
     radio.addEventListener('change', () => {
       sliderContainer.style.transform = `translateX(-${index * 100}%)`;
     });
   });
   ```

   This code sets up event listeners on the radio buttons and updates the slider container's transform property to slide to the selected image.

5. **Customize and enhance**: Customize the styles and add any additional functionality to suit your needs. You can modify the CSS classes, transitions, and other properties to achieve the desired look and behavior.

6. **Enjoy the image slider**: Launch your HTML file in a browser and enjoy the image slider with radio buttons on your website.

## Documentation

Detailed documentation and examples on how to use and customize the image slider can be found in the [docs](./docs) directory. It provides explanations of the available options, customization techniques, and additional features you can add.

## Examples

The [examples](./examples) directory contains ready-to-use examples showcasing different configurations and styles of the image slider with radio buttons. You can open these examples in your browser and explore their source code to learn how to implement the image slider effectively.

## Contributing

Contributions to the image slider with radio button project are welcome! If you find a bug, have a suggestion, or want to contribute new features or improvements, please open an issue or submit a pull request. Make sure to follow the project's code style and guidelines.

## License

The image slider with radio button is released under the [MIT License](./LICENSE). Feel free to use it in personal or commercial projects.

## Credits

The image slider with radio button is developed based on various open-source libraries and contributions from the community. We are grateful for their efforts and contributions.

## Support

If you have any questions, encounter any issues, or need support with the image slider with radio button, you can reach out to the project's maintainers or community. Check the [Contributing](#contributing) section for more information.
