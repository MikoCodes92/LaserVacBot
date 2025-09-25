# LaserVacBot

## Overview
LaserVacBot is a Python Pygame simulation of a smart robot vacuum. The robot automatically finds and cleans dirt using **Dijkstra pathfinding**. A realistic red laser beam visualizes the path to the nearest dirt.

## Features
- Automatic dirt detection and cleaning
- Shortest path-first dirt targeting using Dijkstra algorithm
- Realistic laser beam from robot edge to dirt
- Progress tracking: cleaned vs total dirts
- User-friendly exit after cleaning completes

## Installation
1. Clone the repository:
```bash
git clone https://github.com/MikoCodes92/LaserVacBot.git

2. Install dependencies:
   pip install pygame

3. Place images in the project folder: vc_1.png, d.png, background.jpg
   Usage
     python laser_vac_bot.py
     The robot will automatically clean all dirt.

 Press ESC or click to quit after cleaning.
