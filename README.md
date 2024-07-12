# Sign Language to Text Conversion

## Description

This project aims to translate sign language into text using MediaPipe for hand tracking and an LSTM (Long Short-Term Memory) neural network for sequence prediction. The goal is to create an efficient and accurate system that can interpret sign language gestures and convert them into readable text, facilitating communication for the hearing-impaired community.

## Features

- *Hand Tracking*: Utilizes MediaPipe for real-time hand tracking and gesture recognition.
- *Sequence Prediction*: Employs an LSTM neural network to interpret the sequence of gestures and predict the corresponding text.
- *User-Friendly Interface*: Easy-to-use interface for real-time sign language translation.
- *Scalable and Extensible*: Modular design allowing for easy updates and addition of new gestures.

## Installation

1. Clone the repository:
    bash
    git clone https://github.com/Hmnshuuu/Sign-O-Text.git
    
2. Navigate to the project directory:
    bash
    cd sign-language-to-text
    

## Usage

1. Run the real-time testing script to start the application:
    bash
    python real_time_testing.py
    
2. The application will open your webcam and start tracking your hand gestures.
3. Perform sign language gestures in front of the camera, and the system will translate them into text.

## Project Structure

- real_time_testing.py: The main script to run the application for real-time testing.
- mediapipe_hand_tracking.py: Module for hand tracking using MediaPipe.
- lstm_model.py: Module defining and training the LSTM neural network.
- utils.py: Utility functions for data processing and visualization.
- Mp_Data/: Directory containing 30 video samples for each hand sign gesture, with each video being 10 seconds long.
- data/: Directory for storing and preparing datasets for training.


## Dataset

The Mp_Data directory contains 30 video samples for each hand sign gesture, with each video being 10 seconds long. These videos are used to train and test the LSTM model for accurate gesture recognition and translation.

## Training the Model

To train the LSTM model on your dataset, follow these steps:

1. Prepare your dataset and place it in the data/ directory.
2. Run the training script:
    python
    python Action_Detection.py
    
3. The trained model will be saved as action.h5.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [MediaPipe](https://mediapipe.dev/) for providing the hand tracking solution.
- [TensorFlow](https://www.tensorflow.org/) for the machine learning framework.
- The open-source community for their invaluable resources and contributions.

---

Feel free to reach out if you have any questions or need further assistance. Happy coding!

[Himanshu]  
[himanshujangid364@gmail.com]  
[LinkedIn](https://www.linkedin.com/in/himanshuuu/)
