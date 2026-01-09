# VisualGuide™ Accessibility Tool

> **VisualGuide Version:** 1.1.04

* ![Python 3.11](https://img.shields.io/badge/Python-3.11-blue.svg)
* ![Accessibility](https://img.shields.io/badge/Accessibility-Inclusive-brightgreen)
* ![Windows 11](https://img.shields.io/badge/OS-Windows%2011-lightgrey)
* ![CPU Support](https://img.shields.io/badge/CPU-Intel%2FAMD-orange)
* ![GPU Support](https://img.shields.io/badge/GPU-NVIDIA%2FAMD%2FIntel-red)

---

![FNBubbles420 Logo](https://fnbubbles420.org/orgcircle.png)

🎗️ **Registered 501(c)(3) Nonprofit • EST. 2025**

Empowering gamers, streamers, developers, and veterans — especially those with disabilities, autism, PTSD, mental health and physical challenges, and service-related injuries.

---

## What is VisualGuide™?

VisualGuide™ is a **desktop accessibility tool** designed for gamers and users who need visual assistance and enhanced focus during gameplay.

Developed by **FNBubbles420 Org**, VisualGuide provides:

* **Real-time visual overlays** that help with aiming, object detection, and focus
* **AI-powered object detection** using YOLO and ONNX models
* **Customizable accessibility features** (high contrast, colorblind modes, adaptive themes)
* **A professional Windows desktop application** with automatic setup and a user-friendly interface

```python
print("VisualGuide")
print("Accessibility-focused visual enhancement tool")
print()
print("To use VisualGuide, please download the official installer:")
print("https://www.fnbubbles420.org/Visual-Guide/visual-guide-info")
```

---

## 💻 System Requirements

> **⚠️ Important:** **Windows 11 (64-bit)** is required. Windows 10 is not supported.

### Minimum Requirements

* **OS:** Windows 11 (64-bit)
* **CPU:** Intel Core i5-8th Gen or AMD Ryzen 5 3600 (or equivalent)
* **RAM:** 4GB minimum (8GB recommended)
* **GPU:**

  * **NVIDIA:** GTX 1060 6GB or GTX 1650 4GB
  * **AMD:** RX 580 8GB or RX 5500 XT 4GB
  * **Intel:** Arc A380 4GB or Intel Xe integrated graphics
* **Storage:**

  * **1.82GB** for VisualGuide MSI installer + base app
  * **771MB additional** for NVIDIA CUDA installer download
  * **~3GB total storage** after CUDA/cuDNN installation
* **Admin Rights:** Required during installation
* **Internet Connection:** Required for initial setup and dependency downloads

### Recommended Specs

* **CPU:** Intel Core i7-10th Gen or AMD Ryzen 7 3700X+
* **RAM:** 8GB+ for smooth AI processing
* **GPU:**

  * **NVIDIA:** RTX 2060+ (RTX 20/30/40 series)
  * **AMD:** RX 6600 XT / RX 6700 XT (RX 6000/7000 series)
  * **Intel:** Arc A750 / Arc A770
* **Storage:** SSD for faster model loading
* **Display:** 1920×1080 or higher for the best overlay experience

# Trouble Shooting Tips
- [Trouble Shoot](https://github.com/FNBUBBLES420-ORG/VisualGuide/blob/main/Visual-Guide-Troubleshooting-Notes.MD)
---

## 🛡️ Accessibility, Compliance & Ethics

**Accessibility & Compliance**

* Designed as **assistive technology** for users with disabilities
* Follows **ADA (Americans with Disabilities Act) guidelines**
* **Section 508** aligned for federal accessibility standards
* **WCAG 2.1 AA** principles for visual and UI design
* Accessibility-first options:

  * High contrast themes
  * Colorblind-friendly palettes (deuteranopia, protanopia, tritanopia, monochrome)
  * Scalable text and UI
  * Full keyboard navigation and screen reader support

**Non-Invasive & Ethical**

VisualGuide is **not a cheat** and **not a bot**:

* **Does NOT** modify or change any game files or settings
* **Does NOT** inject code into games or alter game behavior
* **Does NOT** provide mouse automation or any input injection
* **External overlay only**: reads the screen and draws visual bounding boxes
* **Read-only visual assistance** – the tool never sends inputs to the game
* **Privacy-focused**: all processing is done locally on your PC

---

## 🎮 How VisualGuide Helps in Games

**For Aiming & Focus**

* Draws **bounding boxes** around detected objects in your game window
* Provides **visual guides** to support accuracy and reaction time
* Offers **customizable overlays** that avoid clutter and performance impact
* Designed for players who benefit from extra visual structure and guidance

**For Accessibility**

* **High contrast modes** for low-vision users
* **Colorblind-friendly themes**
* **Screen reader integration** (Narrator, NVDA, JAWS compatible UI)
* **Keyboard shortcuts** to control the app without needing a mouse

**For Enhanced Experience**

* **Real-time detection** with GPU acceleration (NVIDIA, AMD, Intel)
* **Multi-window support** – works with any selected game window
* **Background processing** to minimize performance impact
* **Non-intrusive overlay** – transparent and configurable

---

# 📥 Download VisualGuide

### 👉 [Download MSI Installer 1.0.25](https://www.fnbubbles420.org/Visual-Guide/visual-guide-info)

---

## 💿 MSI Installer – Fully Automated Setup

The **MSI installer** is built so non-technical users can install everything with a standard wizard.

### What the Installer Handles

✅ **Python Environment**

* Downloads and installs **Python 3.11.9**
* You just follow the official Python installer prompts — it’s straightforward
* Manages required packages automatically so you don’t have to use the command line

✅ **GPU Optimization (NVIDIA)**

* Detects NVIDIA GPUs and:

  * Installs **CUDA toolkit**
  * Configures **cuDNN** for AI acceleration
* Uses UAC prompts so you always know when system-level changes are happening

✅ **Dependencies & Models**

* Installs required Python packages:

  * `PyQt5`, `OpenCV`, `Ultralytics`, `onnxruntime`, and others
* Sets up GPU-specific versions where needed
* Copies **AI detection models** to your **Documents** folder

✅ **Desktop Integration**

* Creates a **desktop shortcut**
* Adds a **Start Menu entry**
* Sets up required app data and configuration files

---

### Quick Install Steps

1. **Download** the MSI from the VisualGuide page
2. **Right-click** → **Run as administrator**
3. **Follow the wizard** (Next → Next → Install)
4. **Approve UAC prompts** for Python / CUDA when asked
5. Wait for the installer to complete
6. Look for the **VisualGuide desktop icon** — you’re ready to go

No command line. No manual dependency setup. No model downloads.

---

## 🚀 Using VisualGuide

### Getting Started

1. Double-click the **VisualGuide desktop icon**
2. The main interface opens; the Python backend runs in the background
3. Choose your **AI model** and configure your **preferences**

### Setting Up for Gaming

1. Launch your **game** (windowed or fullscreen)
2. **Alt+Tab** to VisualGuide
3. Select your **game window** from the window list
4. Pick your **detection model** (optimized by game type)
5. Adjust **overlay settings** (colors, thickness, contrast)
6. Click **“Run Overlay”** to start assistance

### Overlay Behavior

* Bounding boxes appear in real time over detected objects
* Overlay window stays on top but uses a transparent background
* You can toggle overlays on/off using keyboard shortcuts

---

## ♿ Accessibility Controls

* **High Contrast Mode** for low-vision users
* **Theme Selection**: Normal, high contrast, and colorblind-friendly
* **Screen Reader Support**: Compatible with Narrator, NVDA, JAWS
* **Keyboard-Only Control**: All core actions can be driven from the keyboard
* **Adjustable Text Size**: Larger fonts for easier reading

### How to Enable Screen Reader on Windows 11

1. Press **Windows + Ctrl + Enter** to start Narrator
2. Or go to **Settings → Accessibility → Narrator**
3. Adjust voice, speed, and verbosity
4. Optional: install [NVDA](https://www.nvaccess.org/) or use JAWS for advanced features
5. Press **Windows + Ctrl + Enter** again to turn Narrator off

---

## ⚙️ Advanced Features

* **Multiple Game Profiles** – save different configs per game
* **Model Selection** – use lighter models for higher FPS
* **Image Size & Confidence Tuning** – balance speed vs. accuracy
* **Streaming-Friendly** – works alongside OBS and other recording tools
* **Multi-monitor Support** – use VisualGuide on one screen and game on another

---

## 👥 Who Benefits?

**Gamers with Disabilities**

* Visual impairments, colorblindness, low vision
* Motor disabilities needing clearer visual guidance
* Cognitive or attention-related challenges (ADHD, autism, PTSD)

**Veterans & Service Members**

* PTSD-related focus and attention issues
* Service-related injuries affecting motor skills
* Visual processing challenges from TBI

**General Gaming Community**

* Players who benefit from extra visual clarity
* Streamers wanting consistent visual guides
* Anyone who wants more accessible, structured visual support in games

---

## 🎗️ Our Mission & Programs

**FNBubbles420 Org** focuses on:

* **Accessibility Tools**: Software and adaptive solutions for gaming, streaming, and development
* **Education & Mentorship**: Classes in coding, physics, and digital skills
* **Student Tech Assistance**: Refurbished laptops for students in need
* **Veteran Support**: Tech access and community support for veterans with PTSD and disabilities
* **Mental Health & Community**: Safe, moderated spaces with wellness check-ins
* **STEM Kit Initiative**: Hands-on science and coding kits for young innovators

Learn more: [Our Programs](https://www.fnbubbles420.org/our-programs)

---

## 🤝 Support & Community

* 🌐 Website: [FNBubbles420 Org](https://www.fnbubbles420.org)
* 💬 Discord: [Join Our Community](https://fnbubbles420.org/discordinvite)
* 💙 [Donate](https://www.fnbubbles420.org/donate) • [Volunteer](https://www.fnbubbles420.org/volunteer)

---

© 2025 FNBubbles420 Org. All Rights Reserved. For personal, non-commercial, and educational use only.
[Copyright](https://www.fnbubbles420.org/copyrightnotice) • [Privacy Policy](https://www.fnbubbles420.org/privacypolicy) • [Terms of Service](https://www.fnbubbles420.org/termsofservice)
