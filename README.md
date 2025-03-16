# Lava 3D Model in Maya using Python

## Description
This module creates a **Lava** model and applies procedural shaders using Python in **Autodesk Maya**.

## Features
- Creating a lava surface using polygonal primitives.
- Deforming geometry by modifying vertices, extruding faces, and applying transformations.
- Using **aiStandardSurface** for realistic material properties.
- Applying **aiNoise**, **aiCellNoise**, and **aiColorCorrect** to generate lava textures.
- Using **aiRange** to refine color correction and contrast.
- Assigning a **displacement shader** for realistic rock formations.
- Adding **bump mapping** to create surface details.
- Implementing **aiSkyDomeLight** with an HDRI image for realistic lighting.

## Process Overview
1. Created a base plane and applied procedural deformations.
2. Added **aiStandardSurface** with emission settings for a glowing lava effect.
3. Used **aiNoise** and **aiCellNoise** to generate organic lava patterns.
4. Applied **aiColorCorrect** and **aiRange** to enhance shading and contrast.
5. Implemented a **displacement shader** for rocky surface details.
6. Used a **bump map** for finer texture variations.
7. Set up **aiSkyDomeLight** with an HDRI for realistic environment lighting.
8. Adjusted **subdivision settings** for a smoother render.

## Rendering
- Prepared the model for rendering using **Arnold Renderer**.
- Applied advanced shading and texture mapping for a high-quality lava effect.

## Output
The final model is a fully textured **3D Lava Scene**, optimized for rendering and further modifications.

## Requirements
- Autodesk Maya
- Python (for scripting in Maya)
- Arnold Renderer

## Usage
To execute the script in Maya:
1. Open Maya.
2. Run the Python script in the **Script Editor**.
3. Adjust shading and textures as needed.
4. Render using Arnold for the final output.

