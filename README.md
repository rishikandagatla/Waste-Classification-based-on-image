# ♻️ Waste Classification Using YOLOv8

This project is a **waste classification system** built with **Python** and **YOLOv8**.  
It identifies different types of waste (such as **plastic**, **metal**, **paper**, **organic**, etc.) from images, helping automate the sorting process and promoting better recycling habits.

---

## 🚀 Features

- Real-time waste classification using **YOLOv8** object detection.
- User-friendly **Streamlit** interface for image uploads and live predictions.
- Supports multiple waste categories.
- Custom-trained **YOLOv8** model with optimized weights.
- Visualizes detections with bounding boxes and labels.

---


## 📂 Project Structure

```bash
├── app.py          
├── helper.py        
├── settings.py      
├── weights/         
├── images/
├── __pycache__/         
├── requirements.txt 
└── README.md
```
---

## 🚀 How to Run the Project

## 1️⃣ Clone the Repository
```bash
git clone https://github.com/rishikandagatla/Waste-Classification-based-on-image.git
cd Waste-Classification-based-on-image
```
2️⃣Create and Activate Virtual Environment , 
Ensure Python 3.9 is installed, then run:
```bash
python -m venv venv
venv\Scripts\activate
```
3️⃣Install Requirements
```bash
pip install -r requirements.txt
```

4️⃣ Run the Streamlit App
```bash
streamlit run app.py
```

5️⃣ Access the App
```bash
Visit the provided local URL (usually http://localhost:8501/) in your browser.
