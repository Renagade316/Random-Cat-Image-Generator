Random Cat Image Generator

Overview

This project is a simple web application that fetches and displays random cat images using The Cat API. Users can click a button to generate a new cat image dynamically.

Features

Fetches random cat images from The Cat API.

Displays the image inside a designated container.

Uses async/await for handling API requests.

Minimalistic and responsive design.

Technologies Used

HTML: Structure of the web page.

CSS: Basic styling for layout.

JavaScript: Handles API calls and DOM manipulation.

How It Works

When the page loads, an empty image container is created.

Clicking the "Click me" button triggers an API request to fetch a random cat image.

The returned image URL is set as the src of an <img> element, displaying the image.

If the API request fails, an alert notifies the user.

Code Breakdown

HTML: Contains a button and an empty div container to hold the image.

CSS: Styles the div and img elements to maintain consistent dimensions.

JavaScript:

Uses fetch() to retrieve random cat images.

Handles errors gracefully.

Updates the img element dynamically upon button clicks.

Installation & Usage

Clone the repository:

git clone https://github.com/yourusername/random-cat-image-generator.git

Open index.html in a web browser.

Click the "Click me" button to generate a new cat image.

Demo



Future Enhancements

Add a loading animation while fetching images.

Implement a "Like" feature to save favorite cat images.

Improve styling for a more engaging user experience.

License

This project is licensed under the MIT License.

Enjoy generating random cat images! 🐱
