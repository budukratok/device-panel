---
title: "5. Marking Network Ports"
---
# 05 — Stage 4: Marking Network Ports

This is the most important stage. Here you mark ports on the panel and give them correct names.

> [!important]+ Main rule
> Names must be **unique**.  
> Duplicate names are flagged **in red** and must be fixed.

## What to mark

> [!info]+ What counts as a “network / connector port”
> - **Mark**: RJ45, SFP/SFP+/SFP28, QSFP/QSFP28, HSCI, and other data/uplink connectors.
> - **Do NOT mark**: USB, power inputs, fans/vents, serial/DB9, or non-connector elements.

> [!note]+ MGMT / Console
> Marking **MGMT / Management** or **Console** is allowed.  
> If you mark them, still follow the naming rules below.

![[Pasted image 20260223144139.png]]

## 1. Automatic Tools (Assistants)
- **Auto Detect All**: scans for port-like shapes
- **Snap Selected**: snaps a point into the nearest connector center

> [!tip]+ Always review auto-detect
> Auto tools speed things up, but they can miss ports or detect wrong rectangles.

## 2. Manual Marking
- **[● Add]**: click in the center of each port
- **[○ Delete]**: remove a wrong point
- **Move**: drag a point to reposition it

## 3. Naming, Numbering, and Sorting

> [!important]+ Prefer labels printed on the panel
> If a label is visible, use it exactly as printed:
> - **HSCI** (not `25`)
> - **HA1-A**, **HA1-B**, **WAN**, **LAN1**, etc.

![[Pasted image 20260223144404.png]]

> [!tip]+ If labels are not visible
> Use a consistent logic (example: **Left→Right**, **Top→Bottom**).
> - **Spatial Auto Number** helps generate a clean sequence quickly.
> - You can then **Manual Edit** names as needed.

## 4. Debug Offset (Tuning Auto-Detection)

> [!warning]+ Use only when auto-detection is failing broadly
> Sometimes connectors are detected inconsistently (missing ports, unstable detection).
> - Enable **Debug** to show the **Offset** control.
> - Adjust **Offset** to tune detection sensitivity (similar to contrast/threshold) until connectors start being detected reliably.

If only a few ports are wrong, it’s usually faster to fix/place them manually.

When every required port is marked and all names are correct and unique, click **Next →**.

> [!info]+ Rear panel workflow
> You will repeat the same workflow for the **Rear Panel**:
> **Load Image → Define Panel → Optimize Image → Mark Ports**

 After the rear panel is completed, click **Next →** to proceed to **[Stage 5: Review & Final Export](06_review_export.md)**.