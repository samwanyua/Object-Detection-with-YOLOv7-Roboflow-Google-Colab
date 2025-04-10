# Construction Helmet Detection using YOLOv7 

This project involves training an object detection model to identify **construction helmets** using **YOLOv7**, with data preprocessing and annotation powered by **Roboflow**, and training executed on **Google Colab** with **PyTorch**.

---

##  Project Overview

Ensuring safety at construction sites is crucial, and detecting whether workers are wearing helmets can be automated using computer vision. This project leverages **YOLOv7**, one of the most accurate real-time object detectors, to train a helmet detection model.

###  Objectives
- Detect presence of construction helmets in real-time.
- Improve safety compliance using automated systems.

---

##  Model Performance (Validation)

| Metric      | Score   |
|-------------|---------|
| **mAP@50**  | 88.3%   |
| **Precision** | 90.5%   |
| **Recall**    | 79.3%   |

---

## 🛠️ Tech Stack

- **YOLOv7**
- **PyTorch**
- **Roboflow** (for annotation and dataset versioning)
- **Google Colab** (for training)
- **OpenCV** (for inference)
- **Python**

---

##  Dataset

The dataset consists of images sourced from **Kaggle** and the open web. Data was:
- Cleaned and labeled using Roboflow
- Exported in YOLOv7 format for training

### Classes
- Helmet


---

## 🚀 Training Workflow

1. **Clone YOLOv7 Repo**
```bash
!git clone [https://github.com/WongKinYiu/yolov7](https://github.com/samwanyua/Object-Detection-with-YOLOv7-Roboflow-Google-Colab)
