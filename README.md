
# Emotion-Based-Music-Recommender

This repository contains the code for an emotion recognition system that uses images to predict emotions and recommends music based on these emotions. It integrates TensorFlow for the emotion detection model, Gradio for the web interface, and the YouTube API for fetching music recommendations.

## Repository Structure

```
Emotion-Based-Music-Recommender/
│
├── notebooks/                # Jupyter notebooks with the main logic
│   ├── display.ipynb         # Gradio interface and music recommendation logic
│   └── model.ipynb           # Model training and evaluation
│
├── models/                   # Stored trained model files
│   └── emotion_model.h5      # The trained emotion detection TensorFlow model
│
├── data/                     # Dataset for model training and testing
│   └── facial_emotions/      # Directory containing images of facial emotions
│
├── src/                      # Additional source code for the project
│   └── ...                   # Helper scripts and modules can be placed here
│
├── requirements.txt          # Required Python libraries
└── README.md                 # Project documentation and setup instructions
```

## Setup

To replicate the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies using the command: `pip install -r requirements.txt`.
3. Place your dataset in the `data/facial_emotions/` directory following the expected structure.
4. Load and run the `notebooks/model.ipynb` to train the model or use the pre-trained model provided in the `models/` directory.
5. Run the `notebooks/display.ipynb` notebook to start the Gradio web interface.

## Usage

Once the Gradio interface is running, you can:

1. Upload an image to the web interface.
2. The system will display the predicted emotion and provide music video recommendations based on the emotion.

For detailed usage, refer to the instructions within the `display.ipynb` notebook.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.
