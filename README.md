# QCaV 2023 Vision Pipeline

This repository contains the complete implementation of the project submitted to the QCaV 2023 conference. The focus is on developing a modular, efficient, and scalable computer vision pipeline capable of handling various image processing tasks relevant to industrial quality control applications.

## 🧠 Overview

The project addresses automated analysis of visual data using classical and AI-based image processing techniques. It includes modules for:

- Image acquisition and input standardization
- Preprocessing: normalization, denoising, resizing
- Feature extraction and segmentation
- Evaluation and visualization of results

All components are implemented in a structured and modular format for ease of experimentation and scalability.

## 📁 Project Structure

```
├── ope/                         # Main processing package
│   └── __init__.py              # Initialization script
│   └── setup.py   
├── __init__.py                  
├── outpy.avi                    # Visual output video
├── tactile.avi                  # Tactile sensor-aligned video
├── visibility_counts.pickle    # Object visibility tracking data
├── results/                    # Output images and logs
├── README.md                   # Project documentation
└── LICENSE                     # Licensing information
```

## 🧩 Requirements

- Python 3.x
- NumPy
- OpenCV (`cv2`)
- Pickle (standard)
- MATLAB R2021b or newer
- Image Processing Toolbox

```bash
pip install numpy opencv-python matplotlib
```

## 🚀 Usage

Run the processing pipeline:

```bash
python -m ope
```
Results will be saved in the `results/` directory.

Make sure the following input files exist in the root directory:
- `tactile.avi`
- `outpy.avi`
- `visibility_counts.pickle`

The script will process these and generate visual overlays or console outputs for inspection.

## 📜 License

This repository is licensed under the [MIT License](./LICENSE).

## 👤 Author

Developed by **Hussein Loubani** as part of the QCaV 2023 submission on quality-focused visual inspection pipelines.
