---
title: "6. Review & Final Export"
---
# 06 — Stage 5: Review & Final Export

After you've completed both the Front and Rear panels, you'll reach the final **Review & Export** stage.

## 1. Side-by-Side Verification
- Check both panels look clean and professional.
- Ensure port counts match expectations.
- If something is wrong, click **← Back** and fix it.

## 2. 3D Device Preview (Required)

> [!important]+ Always use 3D Preview before exporting
> This is the easiest way to detect:
> - panel **skew**
> - ports **floating off the device**
> - incorrect **Rack U size** (smushed/stretched appearance)

- Click **[3D Preview 📦]** to open the 3D model view.
- Green cubes represent the marked ports.
- **Rotate**: click + drag  
- **Zoom**: mouse wheel  

### Rack U size check (smushed/stretched)
If the Rack U size is wrong (example: device is **2U** but set to **1U**), the model looks compressed.

- Click **[Edit]** in Review stage → change **Rack U** to correct value
- Re-open **[3D Preview 📦]** and verify again

**✅ Correct (expected Rack U size and proportions)**  
![[Pasted image 20260223145716.png]]

**❌ Incorrect (wrong Rack U size, device looks smushed or stretched)**  
![[Pasted image 20260223145822.png]]

## 3. Exporting Your Work
- **[Export]**: saves PNG + JSON to the project folder
- **[Export & Next ▶]**: saves and jumps to the next incomplete device

## 4. Finding Your Files
Inside **ProcessedDevices**:
- `<vendor_model>_front.png`
- `<vendor_model>_rear.png`
- `<vendor_model>.json`

Congratulations! You've successfully processed the device.