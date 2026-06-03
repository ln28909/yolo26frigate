# yolo26frigate
Yolo26 models with end2end disable for compatibility with Frigate object detection

Here is the detailed export config

model.export(
    format="onnx",
    imgsz=320,
    opset=12,
    simplify=True,
    dynamic=False,
    half=True,
    nms=False,
    end2end=False
)
