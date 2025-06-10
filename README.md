# 🧠 YOLOv8 Object Detection with Real-World Descriptions

This project uses the YOLOv8 model to detect objects in an image and provide **easy-to-understand, real-life descriptions** of what’s in the picture.

## 🖼 Example

Input Image: `dog.jpg`

The model detects objects like:
- 🐶 Dog: “This is a dog. A domesticated animal known for loyalty and companionship.”
- 🚗 Car: “This is a car. A four-wheeled motor vehicle used for transportation on roads.”

It then:
- Draws boxes and labels on the image
- Saves the new image (`output_detected.jpg`)
- Saves the detected info in a JSON file (`detections.json`)

---

## 📁 Files in This Project

| File | Purpose |
|------|---------|
| `yolov8_object_detection.py` | Main Python script |
| `dog.jpg` | Sample image (you can replace it with your own) |
| `output_detected.jpg` | Result image after detection |
| `detections.json` | JSON file with detection info |
| `requirements.txt` | Python libraries needed |
| `README.md` | This guide |

---

## 📦 Requirements

You can install the required libraries using:

```bash
pip install -r requirements.txt
