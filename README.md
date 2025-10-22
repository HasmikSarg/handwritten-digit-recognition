# Handwritten Digit Recognition

## Overview

The "Handwritten Digit Recognition" is a simple yet effective tool for recognizing handwritten digits. This project is powered by a machine learning model originally trained with PyTorch, and the outputs have been adapted to JavaScript format for use in the browser. The application utilizes arrays and matrices to represent biases and weights, allowing for quick and efficient digit recognition.

## How It Works

The core of the "Handwritten Digit Recognition" is a neural network, which is a computational model inspired by the human brain. It consists of layers of interconnected nodes or "neurons" that process input data, learn from it, and make predictions. In this case, the model predicts handwritten digits from 0 to 9 using learned weights and biases from the training phase.

## Live Demo
[Try the application online](https://hoffhannisyan.github.io/handwritten-digit-recognition/): Draw any digit (0-9) on the canvas and see the neural network predict it in real-time!

## Running the Project

To use the "Handwritten Digit Recognition":

1. Clone the project from the GitHub repository.
2. Ensure you have Node.js installed on your local machine.
3. Navigate to the project directory in your terminal.
4. Run the project using the command `npm run start` or `node app.js`.
5. Open your web browser and go to `localhost:8080`.

You'll be greeted with a canvas where you can draw a digit using your mouse or touchscreen. Upon drawing, the prediction chart next to the canvas will display the recognized digit, with the height of the columns representing the model's confidence in its prediction.

