# 3D Transform Suite - VS Code Setup Guide

## Quick Start with Live Server

### Option 1: Using Live Server Extension (Recommended)

1. **Install Live Server Extension in VS Code:**
   - Open VS Code
   - Press `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (Mac)
   - Search for "Live Server"
   - Click "Install" on the extension by Ritwick Dey

2. **Open the Project in VS Code:**
   - Press `Ctrl+K Ctrl+O` (Windows/Linux) or `Cmd+K Cmd+O` (Mac)
   - Select the folder containing `3d-transform-suite.html`

3. **Run the File:**
   - Right-click on `3d-transform-suite.html`
   - Select "Open with Live Server"
   - Your default browser will open with the 3D application running

### Option 2: Using Python's Built-in Server

1. **Open Terminal in VS Code:**
   - Press `` Ctrl+` ``

2. **Navigate to the folder:**
   ```bash
   cd /path/to/your/folder
   ```

3. **Start Python server:**
   ```bash
   python -m http.server 8000
   ```
   OR (Python 2)
   ```bash
   python -m SimpleHTTPServer 8000
   ```

4. **Open in Browser:**
   - Go to: `http://localhost:8000`
   - Click on `3d-transform-suite.html`

### Option 3: Using Node.js (http-server)

1. **Install http-server globally:**
   ```bash
   npm install -g http-server
   ```

2. **Start the server:**
   ```bash
   http-server .
   ```

3. **Open in Browser:**
   - Go to: `http://127.0.0.1:8080`

---

## Features

✅ 8 Different 3D Objects (Cube, Sphere, Torus, etc.)
✅ Full Transformation Controls:
   - Rotation (X, Y, Z axes)
   - Scale (Uniform)
   - Shear (XY and XZ)
   - Translation (X, Y, Z position)
   - Material Properties (Metalness, Roughness)

✅ Interactive Controls:
   - Drag canvas to rotate
   - Scroll to zoom
   - Real-time value updates
   - Reset button

---

## Browser Requirements

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

**WebGL must be enabled in your browser**

---

## Troubleshooting

**"CORS error" or "Failed to load":**
- Make sure you're using a local server (Live Server, Python, or Node.js)
- Don't just open the file directly from the file system

**"Three.js not found":**
- Check your internet connection (Three.js is loaded from CDN)
- The browser console will show any loading errors

**Performance issues:**
- Lower your screen resolution settings
- Use Chrome for best performance
- Disable browser extensions if having issues

---

## Project Structure

```
your-project-folder/
├── 3d-transform-suite.html (Main application)
└── README.md (This file)
```

All code is contained in a single HTML file - no additional dependencies needed!
