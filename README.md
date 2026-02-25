# 🎵 Audio Player Collection

A Progressive Web App (PWA) featuring a collection of high-end audiophile audio players with interfaces inspired by Technics and McIntosh brands.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Supported Audio Formats](#supported-audio-formats)
- [Compatibility](#compatibility)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)

## 🎯 Overview

Audio Player Collection is an elegant web application that offers audio player interfaces inspired by legendary Hi-Fi equipment. The application combines minimalist design with a refined user experience, offering a touch-optimized interface for all devices.

### Key Features

- **Premium user interface** with dark design and elegant lighting effects
- **Progressive Web App (PWA)** installable on mobile and desktop
- **Responsive design** adapted to all screens (smartphone, tablet, desktop)
- **Touch-optimized** with intuitive gestures
- **Audiophile theme** inspired by Technics and McIntosh brands

## ✨ Features

### User Interface

- 🎨 Elegant dark design with radial lighting effects
- 📱 Touch-optimized and responsive interface
- 🔄 Smooth navigation between brands
- 🌐 Multi-language support (English interface)
- 🎭 Premium typography (Zalando Sans Expanded)

### Audio Players

- **Technics Player**
  - Characteristic amber interface
  - Design inspired by Technics Hi-Res Audio players
  
- **McIntosh Player**
  - Iconic McIntosh aesthetic
  - Elegant and refined interface

### Progressive Web App

- 📥 Installation on home screen
- 🚀 Standalone mode launch
- 🎨 Custom icons (192x192 and 512x512)
- 📲 Apple mobile web app support
- 🎯 Optimized portrait orientation

## 🛠️ Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Advanced styles and animations
  - Custom CSS variables
  - Responsive design with media queries
  - Flexbox and Grid Layout
- **JavaScript** (vanilla) - Interactions
- **Bootstrap 5.3.2** - CSS framework
- **Google Fonts** - Premium typography
- **Manifest.json** - PWA configuration

## 📦 Installation

### Prerequisites

- A web server (local or remote)
- A modern browser supporting PWAs

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/player-collection.git
   cd player-collection
   ```

2. **Deploy on a web server**
   ```bash
   # With Python 3
   python -m http.server 8000
   
   # With Node.js and http-server
   npx http-server -p 8000
   
   # With PHP
   php -S localhost:8000
   ```

3. **Access the application**
   ```
   http://localhost:8000
   ```

### Installing as PWA

1. Open the application in a compatible browser
2. On mobile: tap "Add to Home Screen"
3. On desktop: click the installation icon in the address bar

## 🚀 Usage

### Navigation

1. **Home page** (`index.html`)
   - Select your preferred brand: Technics or McIntosh
   - Click on the logo to access the corresponding player

2. **Audio players**
   - `brand/technics.html` - Technics interface
   - `brand/mcintosh.html` - McIntosh interface

### Customization

CSS variables can be adjusted in each HTML file:

```css
:root {
    --font-size-base: 32px;      /* Base font size */
    --logo-width: 400px;         /* Logo width */
    --gold: #d4af37;            /* Gold color */
    --font-size-line: 25px;     /* Secondary font size */
}
```

## 📁 Project Structure

```
Player-Collection-main/
│
├── index.html              # Home page - brand selection
├── manifest.json           # PWA configuration
├── LICENSE                 # MIT License
├── README.md              # Documentation
│
├── brand/                 # Audio player pages
│   ├── technics.html     # Technics interface
│   └── mcintosh.html     # McIntosh interface
│
└── img/                   # Graphic resources
    ├── favicon.png        # Application icon (192x192)
    ├── Technics-Logo-org.png    # Technics logo
    ├── McIntosh_Logo.png        # McIntosh logo
    └── McIntosh_Logo_b.png      # McIntosh logo (variant)
```

## 🎵 Supported Audio Formats

The application is designed to support high-quality audio formats:

- **Hi-Res Audio** (FLAC, ALAC)
- **MP3** (standard)
- **AAC** (Advanced Audio Coding)
- **WAV** (Lossless)
- **OGG Vorbis**

*Note: Actual support depends on the web browser's capabilities.*

## 💻 Compatibility

### Supported Browsers

- ✅ Chrome / Edge (Chromium) 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+

### Devices

- 📱 **Smartphones** (iOS, Android)
- 📲 **Tablets** (iPad, Android tablets)
- 💻 **Desktop** (Windows, macOS, Linux)

### Responsive Breakpoints

- 📱 Mobile: < 576px
- 📱 Large mobile: 576px - 767px
- 📱 Tablet: 768px - 991px
- 💻 Desktop: > 992px

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Guidelines

- Follow the existing code style
- Test on multiple browsers and devices
- Document new features
- Maintain PWA compatibility

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🌟 Acknowledgments

- **Technics** - For design inspiration and audio heritage
- **McIntosh Laboratory** - For iconic aesthetics and audio excellence
- **Bootstrap** - For the CSS framework
- **Google Fonts** - For premium typography

---

<div align="center">

**Made with ❤️ for audiophiles**

[⭐ Star this project](https://github.com/yourusername/player-collection) if you like it!

</div>








