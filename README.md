# Handwritten Digit Recognition

A simple web app that recognizes handwritten digits using a neural network. Draw a number, and it'll tell you what it thinks you drew.

## How It Works

The app uses a neural network (basically a simplified version of how our brains work) to recognize digits from 0 to 9. The model was originally trained in PyTorch and then converted to JavaScript so it can run right in your browser. It uses the learned patterns (weights and biases) to make predictions about what digit you've drawn.

## Try It Out

**[✏️ Live Demo](https://hoffhannisyan.github.io/handwritten-digit-recognition/)**

Just draw any digit on the canvas and watch it predict in real-time! The bar chart shows how confident the model is about each possible digit.

## Running Locally

Want to run it on your machine?

1. Clone the repo
2. Make sure you have Node.js installed
3. Open your terminal and navigate to the project folder
4. Run `npm run start` or `node app.js`
5. Open your browser and go to `localhost:8080`

Draw a digit on the canvas with your mouse (or finger on touch screens), and the chart next to it will show what the model thinks it is. The taller the bar, the more confident it is about that number.
