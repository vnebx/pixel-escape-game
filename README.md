# Pixel Escape Game

**Pixel Escape** is a retro-style 2D platformer built with JavaScript.

## 🕹️ Features

- Classic pixel-art aesthetics
- Collision-based level design using images
- Easy-to-add custom levels

## 🧱 How to Add New Levels

To create a new level, simply use a **300x300 PNG image with a transparent background**. The level layout is determined by the pixel data:

- **Fully opaque pixels (100% opacity)** represent **solid blocks** with collision.
- **Pixels with lower opacity (<100%)** are treated as **non-collidable**, used for **background decoration**.

You can draw levels using any image editor (e.g. GIMP, Photoshop, Aseprite) that supports transparency.

> ⚠️ Make sure your image is exactly 300x300 pixels and saved as `.png`.

## 📜 License

This project is licensed under the **GNU General Public License v3.0**.  
See the [LICENSE](./LICENSE) file for full details.