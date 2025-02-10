# JavaScript Image Classifier

A client-side image classification system powered by TensorFlow.js and MobileNet.

[![Live Demo](https://img.shields.io/badge/demo-live-green?style=for-the-badge)](https://glacode.github.io/js-image-classifier/)

## Features

- 🖼️ Real-time image classification in the browser
- 🚀 No server required - 100% client-side processing
- 🧠 Powered by TensorFlow.js and MobileNet
- 🎯 Accurate classification with confidence percentages
- 🔄 Random image fetching from external source
- 🛡️ Protected against premature classification attempts

## How It Works

1. Loads MobileNet model in the browser
2. Fetches random images from [Lorem Picsum](https://picsum.photos/)
3. Processes images using TensorFlow.js
4. Displays classification results with confidence levels

## Usage

1. Visit the [live demo](https://glacode.github.io/js-image-classifier/)
2. Wait for model initialization (typically 2-3 seconds)
3. Click "Analyze New Image" to classify a random image
4. View results including:
   - Predicted class
   - Confidence percentage

## Technical Details

- **Model**: MobileNet (v2, alpha 1.0)
- **Framework**: TensorFlow.js
- **Image Source**: Lorem Picsum API
- **Browser Support**: Modern browsers with WebGL acceleration

## Development

To run locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/glacode/js-image-classifier.git
   cd js-image-classifier