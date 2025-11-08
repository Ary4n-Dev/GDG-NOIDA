# 🖐️ HolloDesk — AI-Powered Virtual Whiteboard

<h3 href="https://hollodesk.web.app/">Hollodesk</h3>

**HolloDesk** is a browser-based AI-powered whiteboard that lets you **write, draw, pan, and erase in the air** using just your webcam — no touch or stylus required!  
Built entirely with **HTML, CSS, and JavaScript**, HolloDesk uses **computer vision hand tracking** to detect gestures and map your hand movements into real-time drawing actions.

---

## 🌐 Live Concept

When you land on the webpage:
1. The **camera starts automatically**, filling the background with a live video feed.  
2. An **85% opaque overlay** appears on top — this is your **virtual writing area**.  
3. A **bottom toolbar** appears with:
   - 3 **pen tools** of different colors.
   - **Background selection options** — solid color, ruled page, or Cartesian grid.
4. **Hand gestures control everything**:
   - ✋ **Open palm (5 fingers)** → Eraser mode.  
   - ☝️ **Single finger (index)** → Write or draw.  
   - 🤟 **Three fingers** → Pan or move the writing area.

Everything runs directly in your browser — **no backend, no install, no data upload**.

---

## 🧠 Features

- 🎥 **Live webcam background** (auto-starts when page loads).
- ✍️ **Write and draw in the air** using finger tracking.
- 🧽 **Erase** with an open palm gesture.
- 🖐️ **Pan the screen** with a 3-finger gesture.
- 🧮 Choose between:
  - Solid color background (customizable).
  - Ruled paper (lined layout).
  - Cartesian grid (graph background).
- 🖊️ 3 pen styles with distinct colors and stroke widths.
- 📸 Export your drawing as an image.
- ⚡ Fully client-side (HTML + CSS + JS only).

---

## 🛠️ Tech Stack

- **HTML5** → Structure and video feed.
- **CSS3** → Layout, overlay opacity, toolbar design.
- **JavaScript (ES6)** → Logic for hand tracking, gesture detection, and canvas drawing.
- **MediaPipe Hands / TensorFlow.js Handpose** → Real-time hand landmark detection.
- **Canvas API** → Drawing, erasing, and background overlay rendering.

---

## 📁 Project Structure

