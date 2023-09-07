# Imagesearch web App
  The Image Search App is a web application that allows users to search for images using keywords. It fetches images from the Unsplash API and displays them in a visually appealing format.

Table of Contents
Demo
Features
Prerequisites
Getting Started
Usage
Contributing
Demo
Test the button in action here: Live Demo

Features
Search for images using keywords.
Display search results with image thumbnails and links to the original images on Unsplash.
Load more images as you scroll or by clicking the "Show More" button.
Responsive design for various screen sizes.
Prerequisites
Before you begin, ensure you have the following installed or configured:

A code editor (e.g., Visual Studio Code, Sublime Text).
A modern web browser (e.g., Chrome, Firefox).
An internet connection to fetch images from the Unsplash API.
An Unsplash API access key. You can obtain one by signing up for a developer account on Unsplash.
Getting Started
Clone this repository to your local machine:

git clone https://github.com/SrJGit86/imageSearchWithApi.git
Navigate to the project directory:

cd imageSearchWithApi
Create a config.js file in the project root and add your Unsplash API access key:

// index.js
const accessKey = 'RZEIOVfPhS7vMLkFdd2TSKGFBS4o9_FmcV1Nje3FSjw';
Open the index.html file in your web browser or set up a local development server.

Usage
Open the web application in your web browser.

Enter a keyword in the search input field and click the "Search" button.

The search results will be displayed as a grid of image thumbnails.

To view the original image on Unsplash, click on the image or the provided link.

To load more images, either scroll down to trigger automatic loading or click the "Show More" button.

Contributing
Contributions to this project are welcome. To contribute:

Fork the repository.

Create a new branch for your feature or bug fix:

git checkout -b feature/my-feature
Make your changes and commit them:

git commit -m "Add my feature"
Push your changes to your fork:

git push origin feature/my-feature
Create a pull request on the original repository.

Wait for review and approval.

