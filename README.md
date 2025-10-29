# Face Recognition with OpenCV

This project uses OpenCV, a popular computer vision library, for **real-time face recognition** using a webcam.

## Installation

Make sure you have the required dependencies installed: 
- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)

## Utilisation

1. Clone this repository to your machine:
```bash
   git clone https://github.com/Lukas-bt/reconnaissance-faciale.git
  ```
2. Navigate to the project directory:
  ```bash
  cd reconnaissance-faciale
  ```
3. Run the Python script:
  ```bash
python reconnaissance_faciale.py
```
4. A webcam window will open, displaying the live video feed with detected faces highlighted in green.
5. Press the 'q' key to exit the application.

## How It Works

The script uses OpenCV to access the webcam, capture frames, and detect faces using a pre-trained Haar cascade classifier.
