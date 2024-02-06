# Mars Terrain Analysis Project

## Overview
This project utilizes Python, Tkinter, and OpenCV libraries to analyze the terrain of Mars. It involves scanning a specified area on Mars's surface using rectangular grids and statistically evaluating each grid's terrain features based on grayscale and color images.

## Features
- Loads and processes grayscale and color images of Mars's surface.
- Calculates statistical measures (mean, peak-to-peak distance, standard deviation) within each rectangular grid.
- Filters and selects grids based on specific criteria.
- Visualizes the selected grids on the original color image.
- Displays the final analysis results through a Tkinter-based GUI.

## Installation
To run this project, you need Python installed on your system along with the Tkinter, PIL (Pillow), NumPy, and OpenCV libraries. You can install the required libraries using pip:


## Usage
To start the terrain analysis, navigate to the project directory and run the main script:


## How It Works
1. **Image Loading and Preprocessing**: Load the grayscale and color images of Mars's terrain and set the dimensions for the analysis grids.
2. **Grid Analysis**: For each grid, compute statistical measures to evaluate the terrain features.
3. **Grid Filtering and Selection**: Based on the computed statistics, filter and select the grids that meet specific criteria.
4. **Visualization**: Overlay the selected grids on the original color image to visually represent the analysis results.
5. **Tkinter GUI**: Use a Tkinter GUI to display the final analysis results to the user.

## Contributing
Contributions to the Mars Terrain Analysis Project are welcome. Please feel free to fork the repository, make changes, and submit pull requests.

