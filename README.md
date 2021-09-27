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
 ### Training
![confusion_matrix](https://user-images.githubusercontent.com/62469567/134887027-3f80eb9a-f22c-421b-8f7a-f0e48fd200df.png)
![F1_curve](https://user-images.githubusercontent.com/62469567/134887057-3c08f604-3da1-44bd-a518-6f8b5dc68603.png)
![P_curve](https://user-images.githubusercontent.com/62469567/134887093-2cc398be-03db-45a1-a945-25216f07a526.png)
![PR_curve](https://user-images.githubusercontent.com/62469567/134887119-0a3a9939-815d-4d41-ba61-e35ff9810c80.png)
![R_curve](https://user-images.githubusercontent.com/62469567/134887144-5b110ade-9307-4c15-bfbf-e478ae392a1a.png)

### Batch
![train_batch0](https://user-images.githubusercontent.com/62469567/134887223-40b6fe17-1c3d-4916-b9b5-92ea8c464cd2.jpg)
![train_batch1](https://user-images.githubusercontent.com/62469567/134887252-d64ce6df-0ee0-4d39-ad7d-6c3096c367b9.jpg)
![train_batch2](https://user-images.githubusercontent.com/62469567/134887273-6143cf6d-d3ef-4d12-9dbe-d6f99dfaadb3.jpg)

### Validation
![val_batch0_labels](https://user-images.githubusercontent.com/62469567/134887362-4b6f34d2-c656-4ec6-a9c7-a72ba7158f8b.jpg)
![val_batch0_pred](https://user-images.githubusercontent.com/62469567/134887390-e91fe581-0eb6-4065-992e-f75390f4a331.jpg)
![val_batch1_labels](https://user-images.githubusercontent.com/62469567/134887411-965115d4-8124-4b27-abad-1087a1fccab0.jpg)
![val_batch1_pred](https://user-images.githubusercontent.com/62469567/134887427-fb30e575-276b-4f8d-b573-1d68a26b48fc.jpg)
![val_batch2_labels](https://user-images.githubusercontent.com/62469567/134887453-cc236bbf-c18b-4567-9d8c-dbdf6f9b743c.jpg)
![val_batch2_pred](https://user-images.githubusercontent.com/62469567/134887470-b0598abc-3c8e-45d0-b02e-74cde2666a66.jpg)


# Results
![results](https://user-images.githubusercontent.com/62469567/134887177-09440c1b-0600-48a3-bba8-f7dea11a9a31.png)





# VİEW

# LICENSE
This code is released under the MIT License
