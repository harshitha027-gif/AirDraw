# 🎨 AirDraw - Virtual Air Canvas

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
</div>

<div align="center">
  <h3>✨ Draw in the air using just your fingers - no touchscreen required! ✨</h3>
  <p>A computer vision application that transforms hand gestures into digital art</p>
</div>

---

## 🌟 Live Demo

🚀 **[Try AirDraw Live](https://airdraw-demo.vercel.app)** *(Demo deployment)*

---

## 📺 Demo

<div align="center">
  <img src="https://user-images.githubusercontent.com/demo/airdraw-demo.gif" alt="AirDraw Demo" width="600"/>
  <p><i>Draw, erase, and create with simple hand gestures</i></p>
</div>

---

## ✨ Features

### 🎯 Core Functionality
- **👆 Gesture-Based Drawing**: Draw using your index finger in real-time
- **🎨 Multi-Color Support**: Switch between Blue, Green, Red, and Yellow
- **🧹 Eraser Tool**: Remove mistakes with ease
- **🗑️ Clear Canvas**: Reset your canvas with a single gesture
- **📹 Real-Time Processing**: Smooth and responsive hand tracking
- **🖼️ Intuitive Interface**: Visual toolbar for color and tool selection

### 🔥 Technical Highlights
- Hand landmark detection using MediaPipe
- Real-time finger tracking with OpenCV
- Optimized for low-latency drawing experience
- Support for multiple hand positions and gestures

---

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.7+
Webcam or camera device
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/harshitha027-gif/AirDraw.git
cd AirDraw
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the application**
```bash
python airdraw.py
```

---

## 💡 Usage

### How to Draw

1. **Launch the application** - Your webcam will activate
2. **Select a color** - Hover your index finger over a color in the top toolbar
3. **Start drawing** - Raise your index finger and move it to draw
4. **Erase** - Select the eraser tool from the toolbar
5. **Clear canvas** - Select "CLEAR" to reset
6. **Exit** - Press 'q' to quit the application

### Gesture Controls

| Gesture | Action |
|---------|--------|
| ✌️ Index finger up | Draw mode |
| 🖐️ Multiple fingers up | Selection mode (no drawing) |
| 👉 Hover over toolbar | Select color/tool |
| 🧹 Select eraser | Erase mode |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| **Python** | Core programming language |
| **OpenCV** | Computer vision and image processing |
| **MediaPipe** | Hand tracking and landmark detection |
| **NumPy** | Numerical operations and array handling |

### Key Libraries

```python
import cv2              # OpenCV for video capture and processing
import mediapipe as mp  # Hand tracking
import numpy as np      # Array operations
```

---

## 📁 Project Structure

```
AirDraw/
│
├── airdraw.py          # Main application file
├── requirements.txt    # Project dependencies
├── README.md          # Project documentation
└── demos/             # Demo images and videos
```

---

## 🎨 Features Breakdown

### Color Palette
- 🔵 **Blue** - Default drawing color
- 🟢 **Green** - Nature and highlights
- 🔴 **Red** - Bold statements
- 🟡 **Yellow** - Bright accents

### Tools
- ✏️ **Draw Mode** - Create your artwork
- 🧹 **Eraser** - Fix mistakes
- 🗑️ **Clear All** - Fresh start

---

## 🔮 Future Enhancements

- [ ] Add shape recognition (circles, squares, lines)
- [ ] Implement save/export functionality
- [ ] Support for brush size adjustment
- [ ] Add undo/redo functionality
- [ ] Multi-user collaboration mode
- [ ] Mobile app version
- [ ] Custom color picker
- [ ] Drawing templates and backgrounds

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👩‍💻 Author

**Harshitha**
- GitHub: [@harshitha027-gif](https://github.com/harshitha027-gif)
- Project: [AirDraw](https://github.com/harshitha027-gif/AirDraw)

---

## 🙏 Acknowledgments

- Google MediaPipe team for the amazing hand tracking library
- OpenCV community for comprehensive documentation
- All contributors and users of this project

---

<div align="center">
  <p>Made with ❤️ and Python</p>
  <p>⭐ Star this repo if you find it helpful!</p>
</div>

---

## 📞 Support

If you encounter any issues or have questions:
- 🐛 [Report a bug](https://github.com/harshitha027-gif/AirDraw/issues)
- 💡 [Request a feature](https://github.com/harshitha027-gif/AirDraw/issues)
- 📧 Contact via GitHub

---

**Happy Drawing! 🎨✨**
