# 🗑️ Illegal Dumping Sites dataset

This repository contains an annotated image dataset representing illegal dumping sites (`dump_site`). The main goal is to support research, training, and evaluation of computer vision models that can detect these types of scenes in real-world images.

---

## 📁 Dataset Structure

The dataset is organized into the following subsets:

```
dataset/
├── train/
│   └── labels/
├── valid/
│   └── labels/
```

Each subset includes `.txt` annotation files in YOLO format.

---

## 📦 Class Frequency per Subset

| Subset   | Class       | ID | Objects |
|----------|-------------|----|---------|
| `train`  | dump_site   | 0  | 2481    |
| `valid`  | dump_site   | 0  | 1067    |

---

## 📊 Dataset Statistics

| Subset   | Images | Percentage |
|----------|--------|------------|
| `train`  | 730    | 69.99%     |
| `valid`  | 313    | 30.01%     |

**🧮 Total number of images in the dataset:** `1043`

---

## 📝 Annotation Format

Annotations follow the YOLO format, where each line represents one object detection with the following format:

```
<class_id> <x_center> <y_center> <width> <height>
```

All values are normalized between 0 and 1, and coordinates are relative to the image dimensions.

---

## 📌 License

This dataset is published under an open license. You may use it for educational, research, and development purposes, citing this repository as the source.

---

## 🤝 Contributions

If you’d like to contribute with more images, annotations, or improvements to the dataset structure, feel free to fork the repository or open a pull request!

---

## 🚀 Contact

If you have any questions or suggestions, feel free to open an [Issue](https://github.com/your_username/your_repository/issues) or contact me directly.

---

Thanks for your interest in helping fight illegal dumping using AI! 🌍
