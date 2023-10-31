# CluelessCoders AutoWCEBleedGen Challenge MISAHUB
Welcome to CluelessCoders’ GitHub repository on Auto-WCEBleedGen Challenge MISAHUB 2023! This repository contains code, datasets, and a stored model for the image classification as bleeding or non-bleeding. We also have an Excel sheet containing the image IDs and predicted class labels for testing datasets 1 and 2.

Finalised ColabNotebook is MisaHubResNet_FINAL.ipynb

Achieved evaluation metrics of the validation dataset.

Classification - 

| Parameter     | Score         |
| ------------- | ------------- |
| Accuracy      | 0.99          |
| Recall        | 0.99          |
| F1 - Score    | 0.99          |

Detection - 

| Parameter                              | Score         |
| ---------------------------------------| ------------- |
| Mean average precision                 | 0.58          |
| Intersection over union (IoU) (AVERAGE)| 0.44          |
| Average precision                      | -             |

Screenshot of the best 5 predicted frames with bounding boxes and confidence level from DATASET 1 (including the CI in the screenshot itself)- 

<img width="419" alt="1_3" src="https://github.com/stonerrb/MisaHub/assets/90149808/8f49bae5-fbf8-409f-9d65-99d3e83d34c9">

<img width="404" alt="1_1" src="https://github.com/stonerrb/MisaHub/assets/90149808/8b288937-56be-4fec-816f-a8bc76f08004">

<img width="386" alt="1_4" src="https://github.com/stonerrb/MisaHub/assets/90149808/d55e5e4f-09c2-4462-898f-a533747cef37">

<img width="367" alt="1_2" src="https://github.com/stonerrb/MisaHub/assets/90149808/15ead4e8-c097-4fe7-a8e8-2f439a01128c">

<img width="466" alt="1_5" src="https://github.com/stonerrb/MisaHub/assets/90149808/1b756339-1752-4432-9d36-bf27a9ab830f">

Screenshot of the best 5 predicted frames with bounding boxes and confidence level from DATASET 2 (including the CI in the screenshot itself)- 

<img width="475" alt="2_1" src="https://github.com/stonerrb/MisaHub/assets/90149808/2cc59f67-d18b-46ef-a91d-120f6c787c1b">
<img width="455" alt="2_2" src="https://github.com/stonerrb/MisaHub/assets/90149808/4595ad21-166a-43d0-a037-20ff742741c1">
<img width="446" alt="2_5" src="https://github.com/stonerrb/MisaHub/assets/90149808/9de19acd-cb5b-4dd5-99fb-aae4150d887e">
<img width="409" alt="2_4" src="https://github.com/stonerrb/MisaHub/assets/90149808/7d0c5930-755e-45bb-a71c-31c66cd70f9b">
<img width="442" alt="2_3" src="https://github.com/stonerrb/MisaHub/assets/90149808/39bbcef9-9361-4af6-a090-bd7724265a20">

Stored Model drive link with access : https://drive.google.com/drive/folders/1s5poG5v3myJqoR2GBYZwbCbMeDJ9wSSu?usp=sharing 
resnet_model_MISAHUB for classification <br>
best.pt for yolov5 

