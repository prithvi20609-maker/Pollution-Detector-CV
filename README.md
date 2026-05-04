# Pollution Detector using Computer Vision

A Computer Vision project that uses a Keras model to classify whether air conditions in an image indicate pollution (such as haze or reduced visibility).

---

## Features

* Image-based pollution detection
* Trained Keras model for classification
* Simple and easy-to-run Python pipeline

---

## Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy

---

## Project Structure

* `model.keras` → Trained model file
* `detector.py` → Script to run predictions
* `test_images/` → Folder containing input images

---

## Setup & Installation

1. Install required libraries:

```
pip install tensorflow opencv-python numpy
```

2. Download or place the trained model (`model.keras`) in the project folder

   * If not included, provide a download link (e.g., Google Drive)

---

## How to Run

1. Add your test images inside the `test_images/` folder

2. Run the detection script:

```
python detector.py
```

3. The model will process the image and output whether the air appears polluted or not

---

## Model Details

* Built using Keras (TensorFlow backend)
* Trained on image data representing different air visibility conditions
* Uses visual features such as haze and clarity to estimate pollution

---

## Example Output

* Clear Image → Low Pollution
* Hazy Image → High Pollution

---

## Notes

* Ensure images are resized to the correct input shape before prediction
* Best results are obtained with outdoor environmental images

---

## Future Improvements

* Increase dataset size for better accuracy
* Add real-time camera-based detection
* Integrate AQI (Air Quality Index) data for more precise results

---

## Author

Prithvi Biswas
