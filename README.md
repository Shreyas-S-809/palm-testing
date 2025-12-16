## 🚀 palm-testing

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/Shreyas-S-809/palm-testing?style=for-the-badge)](https://github.com/Shreyas-S-809/palm-testing/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Shreyas-S-809/palm-testing?style=for-the-badge)](https://github.com/Shreyas-S-809/palm-testing/network)
[![GitHub issues](https://img.shields.io/github/issues/Shreyas-S-809/palm-testing?style=for-the-badge)](https://github.com/Shreyas-S-809/palm-testing/issues)
[![GitHub license](https://img.shields.io/github/license/Shreyas-S-809/palm-testing?style=for-the-badge)](LICENSE) <!-- TODO: Add project license -->

**Real-time Hand Tracking with Three.js for Interactive Image Display**

</div>

## 📖 Overview

This project is a simple, client-side web application that demonstrates real-time hand tracking and integrates it with a 3D scene rendered using Three.js. It captures live video from the user's webcam, detects hand movements and gestures using a computer vision library, and then uses this input to interactively display and manipulate images within a dynamic 3D environment. This creates an engaging and hands-free interactive experience directly in the browser.

## ✨ Features

- 🎯 **Real-time Hand Tracking**: Detects and tracks human hand landmarks and gestures from a live webcam feed.
- 🖼️ **3D Image Display**: Renders images within a Three.js 3D scene, allowing for dynamic visual feedback.
- 🖐️ **Gesture-Controlled Interaction**: Images and 3D elements can respond to specific hand movements or positions.
- 📹 **Webcam Integration**: Seamlessly accesses and processes video input from the user's default webcam.
- 🌐 **Pure Client-Side**: Runs entirely in the browser without requiring any server-side components.

## 🖥️ Screenshots

<!-- TODO: Add actual screenshots of the application in action.
     Include a screenshot of the main interactive display.
-->
![Screenshot 1](path-to-screenshot-1.png)
![Screenshot 2](path-to-screenshot-2.png)

## 🛠️ Tech Stack

**Frontend:**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-FF3366?style=for-the-badge&logo=google&logoColor=white)

## 🚀 Quick Start

This project is designed to run directly in your web browser.

### Prerequisites
- A modern web browser (e.g., Google Chrome, Mozilla Firefox, Microsoft Edge)
- A working webcam connected to your device.

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/Shreyas-S-809/palm-testing.git
    cd palm-testing
    ```

2.  **Open in your browser**
    Simply open the `index.html` file in your preferred web browser.

    ```bash
    # On macOS
    open index.html

    # On Windows
    start index.html

    # On Linux
    xdg-open index.html
    ```

    Alternatively, for development and to avoid potential browser security restrictions with local file access (especially for webcam), you can use a simple local HTTP server (e.g., `live-server` from npm):
    ```bash
    # If you have Node.js and npm/yarn/pnpm installed
    npm install -g live-server
    live-server
    ```
    This will typically open the application at `http://127.0.0.1:8080` or `http://localhost:8080`.

## 📁 Project Structure

```
palm-testing/
├── index.html       # Main application file containing all HTML, CSS, and JavaScript logic.
└── README.md        # Project overview and documentation.
```

## Check it out Live 
- Click Here : [Check out](https://palm-testing.netlify.app/)

## 🙏 Acknowledgments

-   **Three.js**: For the powerful 3D rendering capabilities.
-   **MediaPipe Hands**: For enabling robust real-time hand tracking.

## 📞 Support & Contact

-   🐛 Issues: [GitHub Issues](https://github.com/Shreyas-S-809/palm-testing/issues)

---

<div align="center">

**⭐ Star this repo if you find it helpful!**

Made with ❤️ by [Shreyas-S-809](https://github.com/Shreyas-S-809)

</div>