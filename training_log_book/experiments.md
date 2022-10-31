
## 📌  Training ViT Base using DDP (1 GPU x 4 Nodes)

- The ViT model has been trained for 30 epochs on 4 nodes, each node consisting of 1 GPU
- The highest batch size achieved is 48
- The best checkpoint is stored into AWS S3
- Training Time: 12109.557782888412 (s)

**Link to Tensorboard logs on Tensorboard.dev**

```
https://tensorboard.dev/experiment/UGRDvNZNSJGVYN8j7yjXoA
```

**GPU Utilization & GPU memory usage NVIDIA SMI Dump**

<p align="center">
  <img src="https://user-images.githubusercontent.com/71654199/199017725-c7aa47be-7e8d-468d-be47-113663be1774.png" alt="drawing" width="225" height="225"/>
  <img src="https://user-images.githubusercontent.com/71654199/199017762-286c718c-7490-48c1-bd01-9e97864916e9.png" alt="drawing" width="225" height="225"/>
  <img src="https://user-images.githubusercontent.com/71654199/199017796-0d2d6623-d627-4aec-b6d6-77b02711ee84.png" alt="drawing" width="225" height="225"/>
  <img src="https://user-images.githubusercontent.com/71654199/199017868-68012817-b210-4d79-85e5-e9aff8d3854d.png" alt="drawing" width="225" height="225"/>
</p>


**MODEL TRAINING AND VALIDATION METRICS**

<p align="center">
  DDP Training Accuracy and Traning Loss graphs<br>
  <img src="https://user-images.githubusercontent.com/71654199/198999103-9333b012-b371-4ad9-b35c-083ec95b0312.svg" alt="drawing" width="500"/>
  <img src="https://user-images.githubusercontent.com/71654199/198999021-e5bb8c7f-402d-4010-a8c5-73db585f3bca.svg" alt="drawing" width="500"/>
</p>

<p align="center">
  DDP Validation Accuracy, Validation Accuracy (Best) and Validation Loss graphs<br>
  <img src="https://user-images.githubusercontent.com/71654199/198999201-7d87d33e-ff60-472f-ba08-ad58c4b1d81c.svg" alt="drawing" width="333"/>
  <img src="https://user-images.githubusercontent.com/71654199/198999247-d466829d-cf1c-473c-8163-c7fe7fd23b7b.svg" alt="drawing" width="333"/>
  <img src="https://user-images.githubusercontent.com/71654199/198999290-3ddbcd20-59dd-4ddc-a607-aadb8acfb678.svg" alt="drawing" width="333"/>
</p>


## 📌  Training ViT Base using FSDP (1 GPU x 2 Nodes)

- The ViT model has been trained for 6 epochs on 2 nodes, each node consisting of 1 GPU
- The highest batch size achieved is 32
- The best checkpoint is stored into AWS S3
- Training Time: 92.13350081443787 (s)

**Link to Tensorboard logs on Tensorboard.dev**

```
https://tensorboard.dev/experiment/1cYfxjMBS9260B3xTe7Jeg
```

**GPU Utilization & GPU memory usage NVIDIA SMI Dump**

<p align="center">
  <img src="https://user-images.githubusercontent.com/71654199/199027150-1f166306-7d08-405f-bf3e-de3c1de27d31.png" alt="drawing" width="450" height="450"/>
  <img src="https://user-images.githubusercontent.com/71654199/199027228-74b76092-058d-479c-98fa-9d30c36f6fab.png" alt="drawing" width="450" height="450"/>
</p>


**MODEL TRAINING AND VALIDATION METRICS**

<p align="center">
  DDP Training Accuracy and Traning Loss graphs<br>
  <img src="https://user-images.githubusercontent.com/71654199/198999103-9333b012-b371-4ad9-b35c-083ec95b0312.svg" alt="drawing" width="500"/>
  <img src="https://user-images.githubusercontent.com/71654199/198999021-e5bb8c7f-402d-4010-a8c5-73db585f3bca.svg" alt="drawing" width="500"/>
</p>

<p align="center">
  DDP Validation Accuracy, Validation Accuracy (Best) and Validation Loss graphs<br>
  <img src="https://user-images.githubusercontent.com/71654199/198999201-7d87d33e-ff60-472f-ba08-ad58c4b1d81c.svg" alt="drawing" width="333"/>
  <img src="https://user-images.githubusercontent.com/71654199/198999247-d466829d-cf1c-473c-8163-c7fe7fd23b7b.svg" alt="drawing" width="333"/>
  <img src="https://user-images.githubusercontent.com/71654199/198999290-3ddbcd20-59dd-4ddc-a607-aadb8acfb678.svg" alt="drawing" width="333"/>
</p>
