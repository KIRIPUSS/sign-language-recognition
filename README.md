# Real-Time Sign Language Recognition

A real-time system that recognizes sign language gestures from a webcam stream using MediaPipe for hand landmark extraction and a lightweight MLP classifier for gesture prediction.


## Features
- Real-time hand landmark detection with MediaPipe Hands
- MLP-based classifier for static gesture recognition
- Pretrained models available in `saved_models/`
- Dataset and artifacts organized under `data/` and `notebooks/`


## Tech Stack
- Python 3.10+
- TensorFlow 2.x
- MediaPipe
- OpenCV
- NumPy, Pandas, scikit-learn, Matplotlib

See `requirements.txt` for exact versions.


## Repository Structure
- `data/` — Dataset, recordings, or preprocessed landmark CSVs (if applicable)
- `notebooks/` — Experiments and training artifacts
  - `Script.ipynb` — End-to-end exploration and training workflow
  - `asl_model.h5`, `label_encoder.pkl`, `scaler.pkl` — Sample trained model and preprocessing artifacts
- `saved_models/` — Exported trained models ready for inference (e.g., `asl_model.h5`, `sign_language_mlp_model*.h5`)
- `requirements.txt` — Python dependencies
- `Readme.txt` — Previous short project note
