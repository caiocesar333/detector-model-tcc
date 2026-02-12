# LIBRAS Sign Detector (TCC)

Prototype for recognizing LIBRAS (Brazilian Sign Language) gestures from **MediaPipe keypoints** extracted from frame sequences (≈80–100 frames per word).  
Vocabulary: **Oi**, **Eu te amo**, **Obrigado**.

## Core code
- Notebook: `Action Detection Refined.ipynb`

## Environment
- Python 3.x
- TensorFlow/Keras, MediaPipe, OpenCV, NumPy, scikit-learn

Install:
```bash
pip install -r requirements.txt

jupyter notebook "Action Detection Refined.ipynb"
