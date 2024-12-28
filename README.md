# Kids-Digit-Learning-Tool

This project implements a handwritten digit recognition system using the K-Nearest Neighbors (K-NN) algorithm. It allows users to create their own dataset by drawing digits on an interactive interface. The system preprocesses user-drawn images, saves them with labels, and uses the dataset for classification. Key features include:

. Custom Dataset Creation: Draw and label digits for training/testing.
. Image Preprocessing: Resizing and grayscale conversion.
. K-NN Implementation: From-scratch algorithm for digit classification.
. Interactive Learning: User-friendly interface for dataset creation.

# Repository structrue:
KNNProject/
├── build/                      # Build output directory
├── data/                       # Data-related files
│   ├── mnist/                  # Original MNIST dataset
│   ├── custom_dataset/         # Custom digit dataset
│   │   ├── images/             # Saved digit images
│   │   ├── labels/
├── include/                    # Header files
│   ├── knn.h                   # K-NN implementation header
├── src/                        # Source files
│   ├── main.cpp                # Main entry point
│   ├── knn.cpp                 # K-NN algorithm implementation
├── External/                    
│   ├── SFML                    # For GUI
│   ├── espeak-ng-master        # For voice
└── CMakeLists.txt              # CMake configuration (if applicable)


