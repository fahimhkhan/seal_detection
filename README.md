# seal_detection

It is recommended to create a new anaconda virtual environment using the following command.

```conda create -n seal_det pip python=3.9```

Activate the virtual environment using the following command.

```conda activate seal_det```

## For detection using EfficientDet model

Install the required dependencies

```pip install -r requirements_tf.txt```

Run the program using the following command

```python stream_effdet2.py```
or
```python stream_effdet3.py```
or
```python stream_effdet_loop.py```

## For detection using YOLOv8 model

Install the required dependencies

```pip install -r requirements_pt.txt```

Run the program using the following command

```python stream_yolov8_loop```

