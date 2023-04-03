# DLAV-3D_detec
3D Object Detection using Monocular Camera

This project aims to detect, recognize and locate objects such as vehicles, pedestrians, bicycles, and animals in 3D space using a single camera. The approach involves training a neural network on a large dataset of labeled images and their corresponding 3D object annotations. The pipeline involves two stages: 2D object detection and 3D estimation using contextual information to predict object position and orientation.
Inputs: RGB images or video
Outputs: 2D Boxes + 3D Boxes (position, orientation, and dimensions) of objects in the image + classes
Datasets: 
- KITTI: https://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=3d
- nuScenes: https://www.nuscenes.org/object-detection?externalData=all&mapData=all&modalities=Any
- Waymo: https://waymo.com/open/challenges/2022/3d-camera-only-detection/
References: 
- 3dDetection: https://github.com/BigTeacher-777/Awesome-Monocular-3D-detection

