# Car Parts Segmentation with YOLOv11 🚗🛠️

This repository contains a YOLOv11 segmentation project for detecting and segmenting different car parts using the **CarParts-Seg** dataset.

![Example](https://github.com/ultralytics/assets/raw/main/yolo-examples/example.jpg)

---

## 📂 Project Structure


---

## 🗂 Dataset

- **Name:** CarParts-Seg (by Ultralytics)  
- **Description:** 23 car parts segmented from front and rear views  
- **Size:** 133 MB  
- **Classes:**  
  - back_bumper, back_door, back_glass, back_left_door, back_left_light, back_light, back_right_door, back_right_light, front_bumper, front_door, front_glass, front_left_door, front_left_light, front_light, front_right_door, front_right_light, hood, left_mirror, object, right_mirror, tailgate, trunk, wheel  

Dataset YAML: [`carparts-seg.yaml`](carparts-seg.yaml)

Download link:  
[CarParts-Seg Dataset](https://github.com/ultralytics/assets/releases/download/v0.0.0/carparts-seg.zip)

---

## 🚀 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/carparts-segmentation.git
cd carparts-segmentation
pip install ultralytics roboflow  # or your specific requirements
