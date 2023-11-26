# Haarcascade Frontalface Emotion Detection Model

Welcome to the Haarcascade Frontalface Emotion Detection Model subdirectory! This directory contains the resources for a pre-trained emotion detection model using Haarcascade Frontalface.

## Contents

1. **main.py**: The main Python script for running the emotion detection model on live video streams.

2. **model.h5**: Pre-trained deep learning model for emotion detection.

3. **tempCodeRunnerFile.py**: Temporary code runner file.

4. **test.py**: Script for testing the emotion detection model.

5. **testdata**: Folder containing sample images for testing the emotion detection model.

6. **faces-small**: Folder for storing cropped face images generated during the emotion detection process.

7. **emotion.npy**: File storing the detected emotion during runtime.

8. **haarcascade_frontalface_default.xml**: Haarcascade XML file for detecting frontal faces.

## Instructions

1. **Run the Model**: Execute the `main.py` script to run the emotion detection model on live video streams. Adjust parameters as needed.

2. **Test the Model**: Use the `test.py` script to evaluate the emotion detection model on sample images in the `testdata` folder.

3. **Explore Outputs**: Check the `faces-small` folder for cropped face images generated during the emotion detection process.

4. **Analyze Detected Emotion**: The detected emotion during runtime is stored in the `emotion.npy` file.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/NebulaTris/detection_models.git
   cd detection_models/user_database_model
   ```

2. Run the `main.py` script for live emotion detection.

3. Execute the `test.py` script for testing the model on sample images.

Feel free to explore, modify, and integrate this emotion detection model into your projects. Happy coding! 🚀