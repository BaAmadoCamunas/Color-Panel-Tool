# Color Panel Tool for Maya

Professional color and render settings tool for Maya control rigs, designed for animation and game production workflows.

---

## Overview

The Color Panel Tool is a Maya workspace tool that allows riggers and Rigging TDs to quickly assign viewport colors and Arnold render settings to control curves.

It is designed to improve rig readability, standardize control colors, and automate render curve setup in production environments.

This tool is suitable for:

- Rigging TD workflows  
- Animation rigs  
- Game-ready rigs  
- Pipeline integration

---

## Features

### Color Management

- Assign Maya indexed colors  
- Assign custom RGB colors  
- Organized color blocks (Main, Side, Secondary controls)  
- Visual color preview  
- Save and load color presets (JSON)  

### Arnold Render Setup

- Apply Arnold curve render settings  
- Automatic ramp shader creation  
- Automatic place2dTexture connection  
- Curve width control  
- Sample rate control  
- Automatic cleanup of unused nodes  

### UI Integration

- Dockable workspace panel  
- Persistent settings  
- Production-friendly interface  

---

## Installation

1. Download the file: color_panel.py
2. Move it to your Maya scripts folder:

    - **Windows:** Documents/maya/2026/scripts/
    - **Mac / Linux:**  ~/maya/scripts/
      
3. Run in Maya Script Editor:

```python
import color_panel
color_panel.show_color_panel()

