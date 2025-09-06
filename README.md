# IVP-Notebooks
 Exploring IVP techniques with Python notebooks...

🖼️ Image & Video Processing (IVP) – Google Colab Projects

This repository contains a collection of Image & Video Processing experiments implemented in Python (OpenCV, NumPy, Matplotlib, Scikit-Image, Scikit-Learn) on Google Colab.

Each notebook corresponds to a lab task (IVP 1–6), with step-by-step code, visualization, and explanations.

📌 IVP Experiments
1️⃣ Image Sampling & Quantization

Reduces spatial resolution (sampling) and pixel intensity levels (quantization).

Demonstrates trade-offs between image quality and storage/computation cost.

Includes before-and-after visualizations.

2️⃣ Spatial Filtering & Sharpening

Applies Laplacian, High-Pass filters for sharpening.

Extended with advanced filters like Sobel, Prewitt, and Unsharp Masking.

Explains why grayscale images are used (intensity-based operations).

3️⃣ DFD (Displaced Frame Difference) & DCD (Dominant Color Detection)

DFD: Highlights changes between neighboring pixels (horizontal, vertical, combined).

DCD: Extracts top 5 dominant colors using KMeans clustering.

Useful for motion detection, texture analysis, and color summarization.

4️⃣ 2D Fourier Transform (FFT)

Computes 2D FFT on grayscale images.

Displays:

Magnitude Spectrum (log-scaled)

Phase Spectrum

Reconstructed Image (via IFFT)

Prints cropped 10×10 matrices for detailed observation.

5️⃣ Combined Visualizations

Side-by-side before/after panels for sampling, quantization, filtering, and transforms.

Helps in comparing multiple operations in one view.

6️⃣ Advanced Image Analysis

Frequency-domain low-pass, high-pass, band-pass filtering.

Channel-wise Fourier analysis (R, G, B).

Quantitative evaluation: PSNR, MSE.

Edge detection using FFT-based filters.

Framework for future IVP experiments.

├── IVP_1_Sampling_Quantization.ipynb
├── IVP_2_Spatial_Filtering.ipynb
├── IVP_3_DFD_DCD.ipynb
├── IVP_4_Fourier_Transform.ipynb
├── IVP_5_Combined_Visualization.ipynb
├── IVP_6_Advanced_Analysis.ipynb
├── README.md
└── sample_output/   # Optional - store generated figures

🛠️ Requirements

Python 3.x

OpenCV

NumPy

Matplotlib

Scikit-Learn

scikit-image

| Experiment              | Example Output                      |
| ----------------------- | ----------------------------------- |
| Sampling & Quantization | ![img](sample_output/sampling.png)  |
| Spatial Filtering       | ![img](sample_output/filtering.png) |
| DFD & DCD               | ![img](sample_output/dfd_dcd.png)   |
| Fourier Transform       | ![img](sample_output/fft.png)       |

📝 Author

Aishwarya Priydarshni
📌 Founder & Director – Technorphic Systems Pvt. Ltd.
🎓 B.Tech CSE (Data Science), Government Engineering College Arwal
