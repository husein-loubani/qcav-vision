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
├── LICENSE                      # License file
├── README.md                    # Project documentation
├── outpy.avi                    # Visual output video
├── tactile.avi                  # Tactile sensor-aligned video
├── visibility_counts.pickle    # Object visibility tracking data
├── results/                    # Output images and logs
├── README.md                   # Project documentation
└── LICENSE                     # Licensing information
```

## 🧩 Requirements

- MATLAB R2021b or newer
- Image Processing Toolbox

No additional packages are required beyond MATLAB standard toolboxes.

## 🚀 Usage

Run the pipeline by executing the main script in MATLAB:

```matlab
% Navigate to the source directory
cd src

% Run the complete processing chain
preprocess;
feature_extract;
segmentation;
evaluation;
```

Results will be saved in the `results/` directory.

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## 👨‍💻 Author

Developed by Hussein Loubani as part of the QCaV 2023 research submission.
