# Color Detection using OpenCV 🎨

A beginner-friendly Computer Vision project built using Python and OpenCV.
This project detects a specific color from a live webcam feed and draws a bounding box around the detected object.

## 🚀 Technologies Used

- Python
- OpenCV
- NumPy
- Pillow

## 🔍 How It Works

The project follows these steps:

```text
Webcam
   ↓
Capture Frame
   ↓
Convert BGR → HSV
   ↓
Detect Target Color
   ↓
Create Color Mask
   ↓
Find Bounding Box
   ↓
Draw Rectangle
```

The image is converted from **BGR to HSV** because HSV makes color detection easier.

## 📂 Project Structure

```text
Computer_Vision/
│
├── main.py
├── util.py
├── requirements.txt
└── README.md
```

## 🛠️ Installation

Clone the repository:

```bash
git clone <your-repository-link>
```

Navigate to the project folder:

```bash
cd color-detection-opencv
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Project

Run the following command:

```bash
python main.py
```

Make sure your webcam is connected and available.

Press **Q** to exit the webcam window.

## 📦 Requirements

```text
opencv-python
numpy
Pillow
```

## 📚 What I Learned

Through this project, I learned the basics of:

- Computer Vision
- OpenCV
- Webcam input
- BGR and HSV color spaces
- Color detection
- Binary masks
- Bounding boxes
- Image processing using NumPy
- Using Pillow with OpenCV

## 🔮 Future Improvements

- Detect multiple colors
- Improve detection under different lighting conditions
- Add real-time object tracking
- Detect different objects
- Explore more Computer Vision techniques

## 👩‍💻 Author

**Dishitha V**

B.Tech Computer Science and Engineering
