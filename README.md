# Smart-Plant-Health-Assistant-Using-CNN-and-NLP-for-Disease-Detection


---

# Smart Plant Health Assistant Using CNN and NLP for Disease Detection

## Overview

The **Smart Plant Health Assistant** is a machine learning-based application designed to assist in the early detection and diagnosis of plant diseases. Leveraging Convolutional Neural Networks (CNN) for image classification and Natural Language Processing (NLP) for processing textual data, this tool provides accurate predictions of plant health issues. The application aims to help farmers and gardeners in identifying diseases and taking timely corrective measures.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Image Classification**: Detects plant diseases from images using a CNN model.
- **Text Analysis**: Analyzes plant health reports using NLP techniques.
- **User-Friendly Interface**: Simple and intuitive frontend built with Streamlit.
- **Real-Time Predictions**: Provides instant feedback on plant health.
- **Scalable Solution**: Designed to be extended with additional plant species and diseases.

## Technologies Used

- **Frontend**: Streamlit
- **Backend**: FastAPI
- **Machine Learning**: TensorFlow, CNN, NLP
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Database**: MongoDB (optional for persistent storage)
- **Version Control**: Git

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Thilakkumar48/smart-plant-health-assistant.git
    cd smart-plant-health-assistant
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the application:**
    ```bash
    streamlit run app.py
    ```

## Usage

1. **Upload an Image**: Use the application interface to upload an image of a plant leaf.
2. **View Results**: The application will classify the disease and provide the result on the screen.
3. **Analyze Text**: Input a textual description of the plant's symptoms for further analysis.

## Dataset

- **Image Dataset**: A collection of labeled images of plant leaves with different diseases.
- **Text Dataset**: A dataset containing descriptions of plant diseases.

## Model Architecture

- **CNN Model**: The Convolutional Neural Network is used for image classification, detecting diseases based on visual features.
- **NLP Model**: Natural Language Processing techniques are used to analyze textual descriptions and provide insights into potential diseases.

## Results

- **Accuracy**: The CNN model achieved an accuracy of XX% on the test dataset.
- **Precision & Recall**: Detailed metrics for each class of disease.
- **Confusion Matrix**: A visual representation of the model's performance.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the open-source community for the datasets and libraries used in this project.
- Inspired by the need to support sustainable agriculture.

---
