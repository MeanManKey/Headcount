### Python = 3.9.19

# `conda` 가상환경 setting

```
conda create -n yolov10 python=3.9 
conda activate yolov10
pip install -r requirements.txt
pip install -e .
```

https://github.com/THU-MIG/yolov10
=> YOLOv10 사용

# Training
```
yolo detect train data=Head005.yaml model=best.pt epochs=500 batch=256 imgsz=640 device=0
```
