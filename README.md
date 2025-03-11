
# Liminality    

Liminality is a multimedia glitch effects application built with Python, OpenCV, PyQt5, and Three.js. It lets you load images, videos, and live feeds from your webcam and applies a variety of real‑time shader effects. You can export your edits into various formats, such as image -> gif / video, randomize effects, and manage presets.

![Liminality Preview](https://i.imgur.com/KpCqVYS.png)



## Features

• Real‑Time Glitch Effects (transformative & filter effects) 

• Video & Image support (MP4, WEBM, PNG, JPEG)

• Preset Management: Save and quickly load presets

• Randomize: Randomly enable/disable effects with random intensities

• Reset: Quickly revert all effects to default (without reloading media)

• Export options for high‑resolution images, GIFs, and MP4 videos

• Webcam support with live glitch effects.




## Installation

I've included an automatic installation script via `install.py` with the source.
This will create all subdirectories needed that aren't present in the .zip as well as a blank presets.json file, and will automatically install the required pip packages. 

Afterwards, you can run `liminality.py`


**If you want to manually install everything:**

- Install required pip packages:

```bash
pip install opencv-python numpy PyQt5 imageio
```
    
In the event that the script does not automatically create your folders / files needed:

Create an empty file named presets.json.
Create the following directory structure:

`Output`

Subdirectories within `Output`:

`Video Gifs Photos Snapshots Webcam`

*It's worth noting that I have included failsafes and automatic creation within the main script, but it never hurts to be thorough.*


## Hardware Requirements


**Minimum:**
+ Dual‑core CPU (e.g., Intel Core 2 Duo)
+ 4 GB RAM
+ Integrated graphics with WebGL support 
+ Windows 7 or later

**Preferred:**
+ Quad‑core CPU (e.g., Intel Core i5 or better)
+ 8 GB RAM or more  (16 GB if managing larger video files)
+ Dedicated GPU with WebGL 2.0 support
+ Windows 10 or later
