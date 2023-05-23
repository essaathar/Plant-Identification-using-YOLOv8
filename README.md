### This project was for the Computer Vision Course. The goal was to identify and localize various species of plants in Karachi, using any Computer Vision technique. The technique chosen was [YOLOv8](https://docs.ultralytics.com/). The methodology was as follows:
- Collect images of various plants from home lawns/gardens, neighborhoods, streets of Karachi, for the Test Dataset
- Use Web Scrapping for the Training Dataset, using classes from Test Dataset
- Annotate training and test images using [Roboflow](https://roboflow.com/)
- Train, validate, and test the model using [Roboflow workflow for Object Detection using YOLOv8](https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/train-yolov8-object-detection-on-custom-dataset.ipynb?ref=blog.roboflow.com)
