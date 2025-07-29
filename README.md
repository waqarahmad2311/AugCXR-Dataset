# AugCXR: Augmented Chest X-Ray Dataset for Pneumonia Diagnosis

This repository contains the finalized implementation of our research work titled:

**"AugCXR Dataset: Augmented Chest X-Ray Datasets for Robust Pneumonia Diagnosis Using Deep Learning"**

The code provided here was used to achieve the best results reported in the paper. It is made available for the benefit of the research community to ensure reproducibility and to support further advancements in medical imaging and deep learning.

---

## 🧪 Key Features

- Data preprocessing and augmentation pipeline
- Training using custom VGG13 (IVGG13), MobileNetV2, and EfficientNetV2L models
- Performance evaluation using accuracy, precision, recall, F1-score, and confusion matrix
- Visualization of training history and results

---

## 📁 Dataset

The dataset used in this study is available on Mendeley Data:

📥 [Download Dataset Here](https://data.mendeley.com/preview/3byppmysgw?a=bb67e2cb-78d7-4477-b0cf-19a4086f7f57)

After downloading, please extract it and update the dataset paths in the code accordingly.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/waqarahmad2311/AugCXR-Pneumonia-Diagnosis.git
cd AugCXR-Pneumonia-Diagnosis
```

### 2. Create Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Code

- Download the dataset and place it appropriately
- Update the paths in the code (clearly marked in comments)
- Run the script (e.g., `python train.py`)

---

## 🧾 Requirements

See [`requirements.txt`](requirements.txt) for all dependencies.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

> 🔓 The code is open access and provided for academic research and educational purposes.

---

## 👨‍💻 Author

**Waqar Ahmad**  
📧 waqarahmad2311@gmail.com  
🔗 [GitHub Profile](https://github.com/waqarahmad2311)

---

## 📄 Citation

If you use this code or dataset in your work, please cite our paper:

```
@article{ahmad2025augcxr,
  title={AugCXR Dataset: Augmented Chest X-Ray Datasets for Robust Pneumonia Diagnosis Using Deep Learning},
  author={Ahmad, Waqar},
  journal={[Your Journal]},
  year={2025},
  publisher={[Publisher]}
}
```
