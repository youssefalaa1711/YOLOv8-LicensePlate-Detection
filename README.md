# 🚘 Car Plate Detection Using YOLOv8

This project demonstrates the use of [YOLOv8](https://github.com/ultralytics/ultralytics) for real-time vehicle license plate detection.  
The detection pipeline is implemented in a Jupyter Notebook using Python and OpenCV, with inference and visualization included.

---

## 📌 Project Overview

- Uses YOLOv8 pretrained model for car plate detection
- Performs inference on images using a Roboflow-hosted dataset
- Shows detection results with bounding boxes using OpenCV
- Notebook includes preprocessing, model loading, and detection steps

---

## 🧠 Tools and Libraries

- Python 3.x
- Jupyter Notebook
- YOLOv8 (via Ultralytics)
- OpenCV
- Roboflow API

---

## 📁 Files in this Repository

- `Milestone_4.ipynb` – main notebook containing the detection pipeline and visual results

---

## 📦 Dataset

This project uses the **`alyalsayed/egyptian-car-plates`** dataset hosted on [Roboflow](https://roboflow.com):

- Dataset is **not included** in this repository due to size and licensing.
- You can access the dataset via Roboflow's API using the existing code in the notebook.

To run the notebook:
1. Create a free account at [Roboflow](https://roboflow.com).
2. Go to your project workspace and generate a **Roboflow API Key**.
3. Replace `"YOUR_API_KEY"` in the notebook with your actual API key.
4. Run the cell to download the dataset.

---

## 📷 Example Output

*Sample output image showing car plate detection (add screenshot if available)*

---

## ⚠️ Notes

- This is a partial academic/inference-level implementation; full training and dataset access require additional setup.
- Model weights and raw datasets are not uploaded due to file size and permissions.
- You are encouraged to retrain or test with your own dataset using the YOLOv8 pipeline.

---

## 🧠 Author

Youssef Alaa Nassar  
[LinkedIn](https://linkedin.com/in/youssef-alaa932004) • [GitHub](https://github.com/youssefalaa1711)

---

## 📄 License

This repository is provided for educational and demonstration purposes only.