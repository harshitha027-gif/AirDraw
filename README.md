# 🎨 AirDraw - Virtual Air Canvas

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe" />
</div>

<div align="center">
  <h3>✨ Draw in the air using just your fingers - no touchscreen required! ✨</h3>
  <p>A browser-based computer vision application that transforms hand gestures into digital art</p>
</div>

---

## 🌟 Live Demo

🚀 **[Try AirDraw Live](https://airdraw-demo.vercel.app)** *(Demo deployment)*

> This application is deployed on **Vercel** for easy access and demonstration.

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

### 🎮 Gesture Controls

| Gesture | Action |
|---------|--------|
| ✌️ Index finger up | Draw on canvas |
| ☝️ Index + thumb up | Selection mode (choose colors/tools) |
| 🖐️ All fingers up | Clear canvas |

---

## 🛠️ Technology Stack

This is a **client-side web application** built entirely with:

- **HTML5**: Structure and layout
- **CSS3**: Styling and visual design
- **JavaScript**: Application logic and interactivity
- **MediaPipe Hands**: Google's ML solution for real-time hand tracking
- **Canvas API**: Drawing surface for gesture-based artwork

> **Note**: This application runs entirely in the browser - no Python, no backend, no installation required!

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Webcam access
- Internet connection (for MediaPipe CDN)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/harshitha027-gif/AirDraw.git
   cd AirDraw
   ```

2. **Open the application**
   
   Simply open `index.html` in your web browser:
   
   ```bash
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```
   
   Or double-click the `index.html` file to open it in your default browser.

3. **Allow webcam access** when prompted by your browser

4. **Start drawing!** Use the gesture controls to create your artwork

---

## 📦 Deployment

### Deploy on Vercel

This application is perfect for deployment on Vercel:

1. Push your code to GitHub
2. Import the project on [Vercel](https://vercel.com)
3. Deploy - no build configuration needed!

### Deploy Anywhere

Since this is a static HTML/JavaScript application, you can deploy it on:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

---

## 🎯 How It Works

1. **Camera Input**: The application accesses your webcam feed
2. **Hand Detection**: MediaPipe Hands identifies hand landmarks in real-time
3. **Gesture Recognition**: JavaScript analyzes finger positions to determine gestures
4. **Canvas Rendering**: Detected gestures control drawing on an HTML5 canvas
5. **Visual Feedback**: Real-time display of your webcam feed and drawing canvas

---

## 🎨 Usage Guide

### Drawing
1. Raise your **index finger** (other fingers down)
2. Move your hand to draw lines on the canvas
3. The drawing follows your finger tip position

### Selecting Colors/Tools
1. Raise your **index finger and thumb** (pinch gesture)
2. Move to the color/tool section at the top
3. Hover over your desired color or tool to select

### Clearing Canvas
1. Raise **all five fingers** (open palm)
2. The canvas will be cleared

### Erasing
1. Select the eraser tool using the selection gesture
2. Draw with index finger to erase

---

## 🌐 Browser Compatibility

| Browser | Supported | Notes |
|---------|-----------|-------|
| Chrome | ✅ | Recommended |
| Firefox | ✅ | Fully supported |
| Safari | ✅ | iOS 14+ |
| Edge | ✅ | Chromium-based |
| Opera | ✅ | Chromium-based |

---

## 🔧 Troubleshooting

### Webcam Not Working
- Ensure webcam permissions are granted in browser settings
- Check if another application is using the webcam
- Try refreshing the page

### Poor Hand Detection
- Ensure good lighting conditions
- Keep hand within camera frame
- Avoid busy backgrounds
- Maintain reasonable distance from camera

### Performance Issues
- Close other browser tabs
- Try a different browser (Chrome recommended)
- Ensure good internet connection for MediaPipe CDN

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👏 Acknowledgments

- **Google MediaPipe** for the hand tracking solution
- **Web APIs** (Canvas, getUserMedia) for enabling browser-based computer vision
- The open source community for inspiration and support

---

## 📧 Contact

**Developer**: harshitha027-gif

**Project Link**: [https://github.com/harshitha027-gif/AirDraw](https://github.com/harshitha027-gif/AirDraw)

---

<div align="center">
  <p>Made with ❤️ and JavaScript</p>
  <p>⭐ Star this repository if you found it helpful!</p>
</div>
