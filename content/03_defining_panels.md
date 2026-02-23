---
title: "3. Defining the Panel"
---
# 03 — Stage 2: Defining the Panel (Corners)

The tool needs to know exactly where the device panel starts and ends in the photo. Correct corners “square up” the image so it can be used as a clean, accurate texture.

> [!warning]+ Do not include rack ears / mounting brackets
> When placing corners, select only the **panel face**.  
> Exclude **mounting brackets / rack ears** and anything extending beyond the main panel surface.
> 
> ![[Pasted image 20260223140024.png]]

## 1. Automatic Detection
The tool will automatically try to detect panel corners after the image is loaded.

- **Cycle Candidates**: use **[◀ Prev]** / **[▶ Next]** to switch between guesses.
- **Auto Detect**: re-run detection if none look correct.

> [!tip]+ Best practice
> Even if the auto-detect is “close”, do a quick manual correction. Small corner errors cause skew later.

## 2. Manual Fine-Tuning (Recommended)
- **Zoom & Pan**:
  - Mouse Wheel = zoom
  - Middle Mouse Drag (or **Spacebar + Left Click**) = pan

- **Drag the Dots**: move **TL / TR / BR / BL** to the literal panel corners.

**✅ Correct**
  ![[Pasted image 20260223151608.png|350]]

**❌ Incorrect**
![[Pasted image 20260223151511.png|350]]

## 3. Helper Tools

> [!info]+ Rotate ↻ changes the image orientation
> Use **Rotate ↻** if the panel is sideways or upside down **before** fine-tuning corners.
> (You want logos/text to read normally.)

When the outline tightly matches the **panel face** (without brackets), click **Next →** to proceed to **[Stage 3: Image Optimization (Warp & Color)](04_image_optimization.md)**.