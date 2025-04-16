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
The best results were yielded by using SGD with LR=1e-3.<br>

Learning curves after 55 epochs with SGD with LR=1e-3<br>

![train_loss_plot (2)](https://github.com/user-attachments/assets/73d05c72-ad9b-4791-99b1-54871b802bb6)

![valid_loss_plot (2)](https://github.com/user-attachments/assets/c28cdf1a-bc5b-468d-b989-c2ddcc5ccc53)


## Performance
Performance was evaluated using CodaBench competition.<br>
According to the results of experiments, the best threshold for prediction during the test stage is 0.7 or 0.75.

<img width="866" alt="CodaBench" src="https://github.com/user-attachments/assets/27c03289-f74b-45e0-bb3a-f8f9f16a9ca5" />



