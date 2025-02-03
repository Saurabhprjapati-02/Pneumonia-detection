# Pneumonia Detection Using Deep Learning

## Description
This project uses deep learning techniques to detect pneumonia from chest X-ray images. The model is trained on a publicly available dataset and is deployed using a Flask web application for real-time predictions.

## Features
- Downloads and processes the pneumonia dataset.
- Trains a deep learning model for classification.
- Deploys the model using a Flask API.
- Provides a frontend interface for users to upload X-ray images and get predictions.

## Dataset
The dataset used for training is **Chest X-Ray Images (Pneumonia)** from Kaggle.

## Tech Stack
- **Python** (NumPy, Pandas, OpenCV, Matplotlib, Seaborn)
- **Deep Learning** (TensorFlow/Keras)
- **Flask** (for API deployment)
- **Frontend** (HTML/CSS/JavaScript)

## Installation
### Prerequisites
- Install Python 3.7+
- Install dependencies:
  ```sh
  pip install -r requirements.txt
  ```

## Usage
1. **Download the dataset**
   ```sh
   kaggle datasets download -d paultimothymooney/chest-xray-pneumonia
   ```
2. **Train the model**
   ```sh
   python train.py
   ```
3. **Run the Flask app**
   ```sh
   python app.py
   ```
4. Open `http://127.0.0.1:5000/` in your browser to upload X-ray images and get predictions.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.
