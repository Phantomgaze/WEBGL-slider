# WEBGL-slider


This project is a WebGL distortion slider using Three.js and GSAP libraries. It creates a unique transition effect between images in a slideshow format.

## Project Structure

The project consists of three main files:

1. `index.html`: This is the main HTML file that contains the structure of the web page.

2. `style.css`: This file contains all the CSS styles used in the project.

3. `script.js`: This is the main JavaScript file that contains the logic for the WebGL distortion slider.

## How It Works

The WebGL distortion slider works by using the Three.js library to create a 3D context, and GSAP to animate the transitions. The images are loaded as textures in Three.js, and a shader material is created using a vertex and fragment shader. The shader material is applied to a mesh, which is added to the scene.

When a pagination button is clicked, the next image is loaded and a transition effect is applied. The transition effect is created by manipulating the vertices and pixels of the images using the shaders.

## Setup

To set up the project, simply clone the repository and open `index.html` in your web browser.

## Dependencies

This project uses the following libraries:

- [Three.js](https://threejs.org/): A library used to create and display animated 3D computer graphics in a web browser.
- [GSAP](https://greensock.com/gsap/): A JavaScript library for building high-performance animations that work in every major browser.
- [imagesLoaded](https://imagesloaded.desandro.com/): A JavaScript library that detects when images have been loaded.

