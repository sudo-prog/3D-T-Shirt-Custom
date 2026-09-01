# 3D T-Shirt Custom 👕

A web-based 3D t-shirt customization tool that allows users to design and
personalize t-shirts in real-time directly in the browser using WebGL.

The application renders 3D t-shirt models using **Verge3D (v3d.js)** and
provides an interactive canvas where users can change colors, upload images,
and apply textures to the 3D garment model.

------------------------------------------------------------------------

# Demo

Live Demo:
https://3d-t-shirt-custom.vercel.app

------------------------------------------------------------------------

# Features

### 3D T-Shirt Customization
-   Change shirt colors in real-time on the 3D model
-   Upload images to print on the t-shirt
-   Real-time preview of design changes

### Interactive 3D Viewer
-   Rotate and inspect the t-shirt model from all angles
-   Dynamic lighting and environment mapping
-   Smooth interaction optimized for web browsers

### Mobile-Optimized UI
-   Tap targets sized to 44px for mobile accessibility
-   Responsive layout for all screen sizes
-   Pinch-to-zoom and pan gestures supported

------------------------------------------------------------------------

# Technologies

## Core
-   Verge3D (v3d.js) — 3D rendering engine
-   WebGL — browser-based 3D graphics
-   HTML5 Canvas — interactive rendering surface

## Frontend
-   HTML5
-   CSS3 / Tailwind CSS
-   JavaScript (ES6+)

## Asset Pipeline
-   Blender — 3D model creation and optimization
-   GIMP / Photoshop — texture design

## Development
-   Git / GitHub
-   npm / Vercel CLI

------------------------------------------------------------------------

# Project Structure

    3d-t-shirt-custom/
    ├── index.html          # Main application entry point
    ├── tshirt-sizingtest.html  # Sizing test page
    ├── visual_logic.js     # Verge3D visual logic script
    ├── v3d.js              # Verge3D engine
    ├── css/                # Stylesheets (including Webflow exports)
    │   └── dominics-beautiful-site-4-4984901ca9e47.webflow.css
    ├── js/                 # JavaScript utilities
    ├── assets/             # 3D models and textures
    ├── images/             # UI icons and preview images
    ├── canvas_bg/          # Canvas background assets
    └── studio_env.hdr      # HDR environment map for lighting

------------------------------------------------------------------------

# Getting Started

## Prerequisites
-   Modern web browser with WebGL support (Chrome, Firefox, Safari, Edge)
-   Node.js v16+ (optional, for local development server)

## Installation

### Option 1: View Online
Visit the live demo to use the application directly in your browser.

### Option 2: Local Development
1. Clone the repository:

       git clone https://github.com/sudo-prog/3D-T-Shirt-Custom.git
       cd 3D-T-Shirt-Custom

2. Open `index.html` in your browser, or serve with a local HTTP server:

       npx serve

3. Navigate to `http://localhost:3000` (or the port shown)

------------------------------------------------------------------------

# Configuration

### Environment Variables
See `.env.local` for local environment configuration:
-   `VITE_API_URL` — Backend API endpoint
-   `VITE_PAYOS_CLIENT_ID` — Payment gateway client ID

------------------------------------------------------------------------

# Project Goals

This project was built to:
-   Explore **3D on the web platform** with real-time customization
-   Build **intuitive product customization experiences** for e-commerce
-   Research **WebGL performance optimization** in browser environments
-   Create a **mobile-first design** with accessible UI tap targets

------------------------------------------------------------------------

# Future Development

Features planned for future releases:
-   Save and share user designs
-   Integrate an ordering and checkout system
-   Add more garment types (hoodies, hats, bags)
-   Optimize rendering performance for mobile devices
-   Add a product management admin panel

------------------------------------------------------------------------

# Author

**RinkVN** — Frontend Developer (React • Three.js • WebGL)

GitHub: https://github.com/RinkVN

------------------------------------------------------------------------

# License

This project is open source and available under the MIT License.
