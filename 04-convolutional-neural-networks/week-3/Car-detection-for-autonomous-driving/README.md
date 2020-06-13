# Car detection for autonomous driving

## Setup

YOLO (v2) weights and .cfg obtained following the guide mentioned in the link below:

https://github.com/JudasDie/deeplearning.ai/issues/2

Once YOLO v2 weights and .cfg file downloaded, the yolo.h5 file generated using the following command:

```cmd
python3 \
  YAD2K\yad2k.py \
  model_weights\yolov2.cfg \
  model_weights\yolov2.weights \
  model_data\yolo.h5
```

**Update**: due to 'bad marshal data' error, used the yolo.h5 file from [Kaggle](https://www.kaggle.com/rmoharir8396/yolo-h5-file)

## Notebooks

Refer to the v3a notebook [link](Autonomous_driving_application_Car_detection_v3a.ipynb) for the latest version