# task_planning
```git clone -b maset https://github.com/KimSeungJun21/task_planning.git``` 


```docker build --tag nvidia_ros:latest .```

```docker run --name ros -it -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY=$DISPLAY -v ~/task_planning:/workspace --gpus all nvidia_ros /bin/bash```

```cd test_pybullet```

if you want example

<stacking example>
```python3 stacking.py```
<clustering example>
```python3 clustering.py```
