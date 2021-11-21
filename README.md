# ResNet-modified-for-EEG
This is a snippet of Python code defining the Class of ResNet model, based on PyTorch. 
The ResNet framework was based on the code in https://github.com/pytorch/vision/blob/main/torchvision/models/resnet.py. 
The modification was focused on only ResNet18, although it may work on the others. 
 - To instantiate the Resnet18 model modified for EEG signal, please use the Model Instantiation command, as below. 

This is not a complete python script. Please import the required modules where necessary. 
```
import torch
import torch.nn as nn
```
<br/><br/>
# Model Instantiation 
```
model = resnet18(pretrained=False, progress=True)
```
<br/><br/>
# Source Article to Cite
#### if the codes are of any help
###### ~ Thank You ~
- DOI: https://doi.org/10.1155/2021/5599615 
- Article Title: [Optimizing Residual Networks and VGG for Classification of EEG Signals: Identifying Ideal Channels for Emotion Recognition](https://doi.org/10.1155/2021/5599615)
- Journal: Journal of Healthcare Engineering, vol. 2021 
- Article ID 5599615
- Year: 2021 
