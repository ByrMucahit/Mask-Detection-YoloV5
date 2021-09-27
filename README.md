![face_recognition_mask_by_viktoriia_miroshnikovadreamstime com_](https://user-images.githubusercontent.com/62469567/134882192-84d2a479-0dca-42df-bef4-b37fcd9b3e2d.jpg)
![tumblr_nu16rpeDrO1ur0lryo1_500](https://user-images.githubusercontent.com/62469567/134882427-bc2f0aef-0d37-430c-8153-cf122573db2e.png)

[![python version](https://img.shields.io/badge/Python-3.7.0-blue)](https://docs.python.org/3/)  [![YOLO version](https://img.shields.io/badge/YOLO-V5-brightgreen)](https://github.com/ultralytics/yolov5)   [![COLAB version](https://img.shields.io/badge/COLAB-new-orange)](https://colab.research.google.com/drive/1n9pLI9UTBad8xH2KwSjLNCUjQi7o7os1) 
# Mask-Detection

# Description
This project can detect people mask on or off. data of  project that developed using deep learning is found from internet envionrenment,and achived 85% accuracy.
used deep learning model is YOLO Version 5.

# CREDIT

# Contribution
There are many ways you can contribute to this project.

- You can suggest new features.
- You can help review new features.
- You can submit new components.
- You can let us know if there are bugs.
- You can share the results of an experiment you ran using these tools.
- You can let us know if the components in this library help you.

# Install 
Python>=3.6.0 is required with all requirements.txt installed including PyTorch>=1.7:
<pre><code>$ git clone https://github.com/ultralytics/yolov5</code></pre>
<pre><code>$ cd yolov5</code></pre>
<pre><code>$ pip install -r requirements.txt</code></pre>

### Inference 
```
import torch
# Model
model = torch.hub.load('ultralytics/yolov5', 'yolov5s')  # or yolov5m, yolov5l, yolov5x, custom

# Images
img = 'https://ultralytics.com/images/zidane.jpg'  # or file, Path, PIL, OpenCV, numpy, list

# Inference
results = model(img)

# Results
results.print()  # or .show(), .save(), .crop(), .pandas(), etc.
```

### Inference with detect.py
<pre><code>$ python detect.py --source 0  # webcam
                            file.jpg  # image 
                            file.mp4  # video
                            path/  # directory
                            path/*.jpg  # glob
                            'https://youtu.be/NUsoVlDFqZg'  # YouTube
                            'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream</code></pre>

# Software

# LICENSE
This code is released under the MIT License
