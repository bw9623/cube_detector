
# Cube Detection with Oriented Bounding Boxes
![Screenshot](example_video.gif)

# Run inference
```sh
python detect.py --source 0 --weights m640rot.pt --imgsz 640 --conf-thres 0.75
```

# Run as ROS node

```sh
rosrun cube_detector ros_detect.py 
```


# Training

```sh
python3 train.py --img 640 --batch 3 --epochs 3 --data aug_cube.yaml  
```


# Test

```sh
python3 detect.py --source 0 --weights m640rot.pt --img 640 
```

