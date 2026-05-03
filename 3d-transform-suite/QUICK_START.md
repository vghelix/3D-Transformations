# 🚀 Quick Start Guide - VS Code

## 3 Easiest Ways to Run This Project

---

## ⭐ Method 1: Live Server (RECOMMENDED - Easiest)

### Step 1: Install Extension (1 minute)
```
1. Press Ctrl+Shift+X (Windows/Linux) or Cmd+Shift+X (Mac)
2. Search for "Live Server"
3. Click "Install" by Ritwick Dey
```

### Step 2: Run the Project (10 seconds)
```
1. Right-click on "3d-transform-suite.html"
2. Click "Open with Live Server"
3. Browser opens automatically! 🎉
```

---

## Method 2: Python Server (No Installation)

### Step 1: Open Terminal in VS Code
```
Press Ctrl+` (backtick)
```

### Step 2: Run Python Command
```bash
python -m http.server 8000
```

### Step 3: Open Browser
```
Go to: http://localhost:8000
Click on: 3d-transform-suite.html
```

---

## Method 3: Node.js Server

### Step 1: Install http-server
```bash
npm install -g http-server
```

### Step 2: Start Server
```bash
cd /path/to/project
http-server .
```

### Step 3: Open Browser
```
Go to: http://127.0.0.1:8080
```

---

## ✅ Verification Checklist

- [ ] File opens in browser
- [ ] 3D object appears in center
- [ ] You can drag to rotate
- [ ] Sliders on right side work
- [ ] Objects in left sidebar clickable
- [ ] No errors in browser console

---

## Common Issues & Fixes

**Issue: "Cannot GET /" error**
→ Make sure you're using a local server (not opening file directly)

**Issue: Three.js not loading**
→ Check your internet connection (it loads from CDN)
→ Open DevTools (F12) and check Console tab

**Issue: WebGL not supported**
→ Update your browser to latest version
→ Try Chrome, Firefox, or Edge

---

## File Structure

```
your-folder/
├── 3d-transform-suite.html    ← Main application
├── index.html                 ← Landing page (optional)
├── README.md                  ← Full documentation
├── QUICK_START.md             ← This file
└── .vscode/
    └── settings.json          ← VS Code config
```

---

## What You Can Do

✅ Choose 8 different 3D objects (Cube, Sphere, Torus, etc.)
✅ Rotate in 3D space (X, Y, Z axes)
✅ Scale objects (0.1x to 3x)
✅ Shear transformations
✅ Move objects in 3D space
✅ Adjust material properties
✅ Drag canvas to rotate interactively
✅ Scroll to zoom

---

## Need Help?

**VS Code Issues:**
- File → Preferences → Extensions → Make sure Live Server is installed

**Browser Issues:**
- Press F12 → Console tab → Check for red errors

**Connection Issues:**
- Make sure server is running before opening browser
- Check the terminal shows "Server running on..."

---

**Ready? Choose Method 1 (Live Server) and you'll be running in 30 seconds!** ⚡

