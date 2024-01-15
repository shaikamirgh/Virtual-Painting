# Virtual-Painting
Virtually Paint on screen tools-free using Camera.
##### Specially on Jetson Nano, also runs on Desktops

## Getting Started

To get started with Virtual Painting, follow these steps.

### Step 1 - Clone Repo

1. Install OpenCV and mediapipe. To do this on NVIDIA Jetson, we recommend following [this guide](https://forums.developer.nvidia.com/t/72048)

    ```
    git clone https://github.com/shaikamirgh/Virtual-Painting
    cd Virtual-Painting
    ```

### Step 2 -  Install Dependencies
In your  Terminal:
(Right-Click on your folder in VS Code and Open in Integrated Terminal)
```python
pip install -r requirements.txt
```

### Step 3 - Run the example notebook
Open Virtual-Painting.ipynb and Run the cells


#### You can modify the Brush thickness, depending on your use-case

### The Hand Tracking Module python code is separate file so that you can directly use that module in your own projects.

## See also
- [trt_pose_hand](http://github.com/NVIDIA-AI-IOT/trt_pose_hand) - Real-time hand pose estimation based on trt_pose


## References
Hand Tracking Module by Murtaza Hassan 
http://www.youtube.com/c/MurtazasWorkshopRoboticsandAI