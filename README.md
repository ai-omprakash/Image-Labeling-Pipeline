# 🏷️ OCR Image Labeling Tool

A modern Python-based OCR image labeling application built with Tkinter and Pillow for creating annotated datasets for Optical Character Recognition (OCR), computer vision, and machine learning projects.

This tool allows users to draw bounding boxes on images, assign text labels, and export structured datasets for OCR model training and experimentation.

---

# 🚀 Features

* 📁 Load multiple images
* 🖼️ Interactive image viewer with zoom support
* ✏️ Draw bounding boxes for text regions
* 🏷️ Add, edit, and delete OCR labels
* 💾 Save and load annotation sessions
* 📤 Export cropped text regions and annotations
* 📊 Generate dataset-ready annotation files
* 🎨 Modern dark-themed UI
* ⌨️ Keyboard shortcuts for faster workflow
* 🔍 Visualized annotation preview generation

---

# 🛠️ Technologies Used

* Python 3
* Tkinter
* Pillow (PIL)
* JSON
* File System Operations

---

# 📂 Project Structure

```bash
Image-Labeling-Pipeline/
│
├── import.py
├── README.md
├── session.json
│
├── output/
│   ├── image_001/
│   │   ├── image_001_label_001.png
│   │   ├── image_001_label_001.txt
│   │   ├── image_001_annotations.txt
│   │   └── image_001_visualized.png
```

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/ai-omprakash/Image-Labeling-Pipeline.git
cd Image-Labeling-Pipeline
```

---

## 2. Install Dependencies

```bash
pip install pillow
```

Tkinter is included with most Python installations.

---

# ▶️ Run the Application

```bash
python import.py
```

---

# 🧠 How It Works

1. Add images to the application
2. Draw bounding boxes around text regions
3. Enter corresponding OCR labels
4. Save annotations
5. Export dataset files for model training

The tool automatically:

* Crops labeled text regions
* Saves text annotations
* Generates annotation metadata
* Creates visualization previews

---

# 📤 Export Format

Each labeled image exports:

## Cropped Text Image

```bash
image_label_001.png
```

## OCR Text Label

```bash
image_label_001.txt
```

## Annotation File

```bash
filename	label	bbox(x1,y1,x2,y2)
```

## Visualization Output

Annotated image with all bounding boxes displayed.

---

# ⌨️ Keyboard Shortcuts

| Shortcut    | Action                |
| ----------- | --------------------- |
| Ctrl + O    | Add Images            |
| Ctrl + S    | Save All Labels       |
| Left Arrow  | Previous Image        |
| Right Arrow | Next Image            |
| Delete      | Delete Selected Label |
| Escape      | Cancel Current Label  |

---

# 🎯 Use Cases

* OCR dataset creation
* Text recognition projects
* Machine learning dataset annotation
* Synthetic OCR training pipelines
* Computer vision research
* Handwritten text labeling
* Document AI systems

---

# 📸 Supported Image Formats

* PNG
* JPG / JPEG
* BMP
* GIF
* TIFF
* WEBP

---

# 🔮 Future Improvements

* YOLO format export
* COCO dataset export
* XML annotation support
* Polygon annotations
* Auto-save functionality
* AI-assisted labeling
* Multi-language OCR support

---

# 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the repository and submit pull requests.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Developed by Omprakash Gharti Magar

GitHub: https://github.com/ai-omprakash
