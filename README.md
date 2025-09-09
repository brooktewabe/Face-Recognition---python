# 🧑‍💻 Face Recognition with Python

This project demonstrates **face detection and recognition** using Python, OpenCV, and the `face_recognition` library.  

The system:
- Detects faces from input images.
- Crops & saves them into a `faces/` folder.
- Uses a webcam feed to recognize known faces in real-time.

---

## ⚙️ Requirements

### System Requirements (Windows)
- ✅ Python **3.8+** (3.10 or 3.11 recommended, 64-bit)
- ✅ [CMake](https://cmake.org/download/) (needed to compile dlib if not using prebuilt wheel)
- ✅ [Microsoft Visual Studio Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/)
  - Install via **Visual Studio Installer**
  - Select **Desktop development with C++**
- ✅ Windows SDK (installed with VS Build Tools)

> 💡 If you don’t want to set up CMake/VS manually, you can use **Anaconda** which handles prebuilt binaries.

Alternative (skip CMake & VS setup)

> Download the correct prebuilt .whl file for your Python version from:
👉 Unofficial Windows binaries (Gohlke) https://www.cgohlke.com/#dlib
---

## 📦 Python Dependencies

Install required Python packages:

```bash
pip install opencv-python
pip install opencv-contrib-python
pip install numpy
pip install dlib
pip install face-recognition
