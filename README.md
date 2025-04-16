# Selected Topics in Visual Recognition using Deep Learning, Spring 2025: Homework 2
Course instructor: 林彥宇<br>
<br>
StudentID: 313540002<br>
Name: Leontieva Mariia, 馬莉亞<br>

### Introduction

In this assignment, we aim to solve digit recognition problem using a Faster R-CNN network, using the [dataset](https://drive.google.com/file/d/1fx4Z6xl5b6r4UFkBrn5l0oPEIagZxQ5u/view?usp=drive_link) that contains 30,062 images for Training, 3,340 for Validation and 13,068 images for Test.<br>
The bounding boxes inside dataset are specified in the COCO format:<br> “bbox”: [xmin, ymin, w, w]
To solve this problem, I chose a Faster R-CNN model with a Resnet-50 backbone and pre-trained weights.<br>


## Results
Results without data augmentation:<br>

Learning curve after 20 epochs with LR = 0.0001<br>
![curve1](https://github.com/user-attachments/assets/92639943-a063-4a75-9dc1-ff5ce6ec1791)<br>
Confusion matrix<br>
![Confusion_matrix_1](https://github.com/user-attachments/assets/1e14b4bf-f9fe-4f75-8117-4f7131c33b02)<br>

Results with data augmentation<br>
Learning curve after 20 epochs with LR = 0.0001<br>
![curve2](https://github.com/user-attachments/assets/2d3b6cf8-b5be-49d7-b551-222615d9f873)<br>
Confusion matrix<br>
![Confusion_matrix2](https://github.com/user-attachments/assets/1a389d9f-2bd6-44eb-97bd-68e511b2b8eb)<br>

## Performance
Performance was evaluated only without data augmentation, due to competition closing early.<br>
<img width="902" alt="image" src="https://github.com/user-attachments/assets/873dde7a-9f8c-430e-a835-e428405e4169" />


