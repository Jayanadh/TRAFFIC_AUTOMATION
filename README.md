# 🚦 AI Traffic Signal Automation

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)](https://jupyter.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An AI-driven project that leverages computer vision and deep learning to automate traffic signal control. The system analyzes real-time video feeds, detects vehicle density, and dynamically optimizes signal timings to reduce congestion and improve road safety.

---

## 📌 Features

- **Traffic Density Estimation** – Uses computer vision to detect and count vehicles.  
- **Dynamic Signal Optimization** – Allocates green light time based on lane density.  
- **Computer Vision Pipeline** – Built with OpenCV, PyTorch, and NumPy.  
- **Visualization** – Annotated frames and plots for analysis.  
- **Scalable Design** – Extendable to multiple intersections and IoT integration.  

---

## 📂 Project Structure

```
AI_TRAFFIC_SIGNAL_AUTOMATION.ipynb   # Main Jupyter Notebook
data/                                # (Optional) Input videos/images
models/                              # (Optional) Pre-trained ML/DL models
outputs/                             # Processed results and visualizations
requirements.txt                     # Dependencies
README.md                            # Project documentation
```

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/AI_TRAFFIC_SIGNAL_AUTOMATION.git
   cd AI_TRAFFIC_SIGNAL_AUTOMATION
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

📌 `requirements.txt` includes:
```
numpy
pandas
matplotlib
opencv-python
torch
Pillow
ipython
google-colab
```

---

## ▶️ Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook AI_TRAFFIC_SIGNAL_AUTOMATION.ipynb
   ```

2. Run the cells in sequence:
   - Load traffic video/image
   - Preprocess frames
   - Detect and count vehicles
   - Optimize signal timings
   - Visualize outputs

3. Output includes:
   - Vehicle counts per lane  
   - Adjusted signal durations  
   - Annotated video frames  

---

## 📊 Methodology

1. **Input** – Traffic video or CCTV feed  
2. **Detection** – Vehicle detection with computer vision & ML/DL models  
3. **Counting** – Frame-wise vehicle density calculation  
4. **Decision** – Dynamic green-light allocation  
5. **Output** – Optimized traffic signal timings  

---

## 🚀 Future Work

- Real-time IoT integration with smart traffic lights  
- Multi-camera fusion for complex intersections  
- Pedestrian and emergency vehicle detection  
- Predictive modeling with historical traffic data  

---

## 🤝 Contributing

Contributions are welcome!  
Please open an issue or submit a pull request for suggestions and improvements.

