OpenCV and Numpy Point cloud Software Renderer

Usage:
------
Mouse: 
    Drag with left button to rotate around pivot (thick small axes), 
    with right button to translate and the wheel to zoom.

Keyboard: 
    [p]     Pause
    [r]     Reset View
    [d]     Cycle through decimation values
    [z]     Toggle point scaling
    [c]     Toggle color source
    [s]     Save PNG (./out.png)
    [e]     Export points to ply (./out.ply)
    [q/ESC] Quit

This software uses OpenCV and Numpy along with the pyrealsense2 library to render point clouds from a RealSense camera. It provides interactive controls for manipulating the view of the point cloud.

2019 Kevin Peivareh. All Rights Reserved.
