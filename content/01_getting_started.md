# 01 — Getting Started: Project & Model List

When you first launch the tool, you'll see a workspace designed to handle multiple devices at once.

## 1. Creating a New Project
Go to **File → New Project** (or press **Ctrl+N**). Give your project a name and choose where you want to save the final textures and data. This folder will be your central export location.

## 2. Importing Your Device List
Most likely, you have a `.txt` file containing a list of vendors and model names (e.g., `Cisco | C9300-48P | 1U`).
*   Go to **File → Import Model List**.
*   Select your text file.
*   The left-side panel will now fill up with a list of devices.

## 3. Verifying the List
Take a look at the model list on the left.
*   **Search**: Use the search bar at the top of the list to find a specific model.
*   **Correction (U height)**: If you notice a model has an incorrect Rack Unit (U) height (e.g., it's listed as 2U but should be 1U), select the model and click the **[Edit]** button at the bottom of the list to fix it.
*   **Status Indicators**: Each model has four dots representing its progress:
    1.  Front Panel Image
    2.  Front Ports Marked
    3.  Rear Panel Image
    4.  Rear Ports Marked
    *   ⚪ Not Started | 🟡 In Progress | 🟢 Done

## 4. Selecting a Model
Click on any model in the list to begin its extraction wizard. The tool will automatically jump to the first incomplete stage for that device.
