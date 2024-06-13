This project demonstrates a simple web application for image classification using a trained  Keras model with kaggle datasets served with Flask.

## Overview

This Flask application allows users to upload an image and receive a prediction on whether the image contains a ship or not. The model used for prediction is a pre-trained convolutional neural network (CNN) trained on a dataset of ship images.

## Prerequisites

Before running the application, ensure you have the following installed:
- Python 3.x
- Flask
- Keras
- matplotlib

You can install the required Python packages using pip:

```bash
pip install Flask keras matplotlib
```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. **Run the Flask application:**

   ```bash
   python app.py
   ```

   The application will start running locally at `http://localhost:5000/`.

3. **Upload an image:**

   Navigate to `http://localhost:5000/` in your web browser. You will see an upload form. Choose an image file and click "Predict".

4. **View the prediction:**

   After uploading, the application will display whether the image contains a ship or not.

## File Structure

- **`app.py`**: Flask application file containing route definitions and prediction logic.
- **`index.html`**: HTML template for the main page with upload form.
- **`static/`**: Directory to store uploaded images.
- **`my_models.h5`**: Pre-trained Keras model for image classification.
- **`README.md`**: This file, providing an overview of the project and instructions for usage.

## Additional Notes

- The model (`my_models.h5`) used in this project is a simple CNN trained on a dataset of ship images. Replace it with your own trained model for different applications.
- Feel free to customize the HTML templates (`index.html`) and CSS styles to fit your design preferences.
- datasets which are used are gathered from kaggle .

## About

This project was developed by Santhana Krishnan V. For inquiries, please contact [santhanakrishnan9704@gmail.com](mailto:santhanakrishnan9704@gmail.com).

---
