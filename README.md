# OpenCV Interactive Image Cropping Tool 🖼️🖱️

A lightweight, interactive Python tool built with OpenCV (`cv2`) and NumPy that lets you crop images dynamically using mouse drag-and-drop actions inside a Jupyter Notebook.

---

## 🚀 Features

* **Mouse Callback Integration:** Leverages OpenCV's `setMouseCallback` to capture mouse events (click and release).
* **Real-time Rectangle Drawing:** Draws a bounding box directly on the source image as you finish your selection.
* **Automatic Output Saving:** Instantly displays the cropped region in a new window and saves it automatically to disk as `cropped-image.png`.
* **Jupyter Compatible:** Structured to run interactively block-by-block.

---

## 🛠️ Prerequisites & Installation

Make sure you have Python installed along with OpenCV and NumPy:

```bash
pip install opencv-python numpy
