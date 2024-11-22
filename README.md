# COSC 4372 Group Project
Our COSC 4372 Group Project is a mammography simulator which detects lesions in a 3d breast phantom.
## Installation
- Install MATLAB and necessary add-ons (Image Processing Toolbox).
- Download "MammographySimulatorApp.mlapp" and "phantom3d.m" into one folder.
## Usage
- Launch MammographySimulatorApp.mlapp
- Click "Run" in the "Designer" tab found at the top of MATLAB and you should see a GUI pop up.
- In the app there are 5 parameters you can change via dropdown: Energy, Angle, SID, OID, and Phantom Thickness.
- You can then click "Generate 1D Profile From 2D Phantom" to view the 1D Profile of the x-ray, or "Generate 2D Image for 3D Phantom" to view the resulting x-ray image for the acquisition parameters you provided.
- Click "Reset" when you are done looking at the output and then continue to experiment with different acquisition parameters.
## Code
When you launch "MammographySimulatorApp.mlapp", App Designer will open up the design view of the application. You can see the code we used by clicking "Code View" at the top right of App Designer.