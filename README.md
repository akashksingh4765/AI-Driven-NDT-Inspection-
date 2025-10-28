# 🧠 AI-Driven Defect Detection and Smart Inspection System using YOLOv11s


### 🏢 Developed during internship at [Tata Advanced Systems Ltd (TASL), Bengaluru](https://www.tataadvancedsystems.com/)

## 📘 Project Overview
This project implements a YOLO deep learning model to detect and classify defects in composite materials using C-scan and thermographic NDT data. 
It forms a critical component of the AI-Driven NDT Inspection System, developed by **Akash Kumar Singh** during his internship at **Tata Advanced Systems Ltd (TASL), Bengaluru**.

## 🎯 Objectives
- Automate defect detection using YOLO deep learning architecture  
- Enhance accuracy and consistency of NDT inspections  
- Provide visual outputs for real-time or post-inspection analysis  

## ⚙️ Tech Stack
Python, PyTorch, OpenCV, Ultralytics YOLOv8, NumPy, Pandas, Matplotlib, Google Colab

## 📁 Repository Structure
```
YOLO_MODEL(Akash)/
│
├── dataset/                 # Training and validation data
├── runs/                    # YOLO training outputs
├── weights/                 # Trained model weights
├── YOLO_MODEL(Akash).ipynb  # Training and inference notebook
└── README.md                # Project documentation
```

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/akashksingh4765/AI-Driven-Defect-Detection-YOLO.git
   ```
2. Open the notebook `YOLO_MODEL(Akash).ipynb` in Jupyter or Google Colab.  
3. Run all cells to train or perform inference using YOLOv8.  
4. Results will be saved in the `runs/` directory.

## 📊 Results Summary
The model achieved strong performance in detecting delaminations and surface anomalies, with precision and mAP values indicating reliable inspection accuracy suitable for real-world aerospace composite evaluations.

| Metric | Value |
|--------|--------|
| Precision | 0.94 |
| Recall | 0.91 |
| mAP@50 | 0.92 |

## 🧠 Future Work
- Integrate this YOLO module with XGBoost-based signal classification  
- Combine results into a hybrid AI decision system for predictive maintenance  
- Extend to thermographic data fusion for composite analysis  

## 👨‍💻 Author
**Akash Kumar Singh**  
🎓 M.Tech in Non-Destructive Testing, NIT Trichy  
🔗 [LinkedIn](https://www.linkedin.com/in/akashksingh4765/) • [GitHub](https://github.com/akashksingh4765)

## ⚖️ License
This project is licensed under the [MIT License](LICENSE).
