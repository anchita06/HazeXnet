# Image Dehazing Algorithm using Python

## Project Overview
This project implements an image dehazing algorithm to remove haze or fog from images affected by atmospheric scattering. The goal is to enhance visibility, contrast, and color fidelity while preserving natural scene details.

The complete implementation is provided in a Jupyter Notebook (HazeXnet.ipynb), allowing step-by-step execution and visualization of results.

---

## Problem Statement
Images captured in hazy or foggy environments suffer from low contrast, reduced visibility, and color distortion. These issues negatively impact applications such as surveillance systems, autonomous driving, outdoor photography, and remote sensing.

This project addresses these challenges using classical image processing and computer vision techniques.

---

## Methodology
The dehazing pipeline consists of the following steps:
1. Atmospheric light estimation  
2. Transmission map estimation  
3. Scene radiance recovery  
4. Post-processing and contrast enhancement  

---

## Project Structure
HazeXnet.ipynb      - Main Jupyter Notebook  
input_images/       - Folder containing hazy input images  
output_images/      - Folder containing dehazed output images  
README.md           - Project documentation  

---

## Technologies Used
- Python  
- OpenCV  
- NumPy  
- Matplotlib  
- PIL / SciPy (optional)  

---

## Key Features
- Atmospheric scattering model-based dehazing  
- Improved image clarity and contrast  
- Preservation of edge details  
- Side-by-side visualization of hazy and dehazed images  

---

## How to Run
1. Clone the repository  
2. Navigate to the project directory  
3. Open the Jupyter Notebook using:
   jupyter notebook HazeXnet.ipynb  
4. Run all cells to generate dehazed images  

---

## Results
The algorithm significantly improves visibility and contrast in hazy images. The notebook displays visual comparisons between the original hazy image and the dehazed output.

---

## Applications
- Computer vision preprocessing  
- Autonomous vehicles  
- Surveillance systems  
- Satellite and aerial image analysis  
- Photography enhancement  

---

## Future Enhancements
- Real-time video dehazing  
- Deep learning-based dehazing models  
- Quantitative evaluation using PSNR and SSIM  
- Web or API-based deployment  

---

## Author
Anchita Singh  

---

## License
This project is intended for educational and research purposes.
