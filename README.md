### APS360-Skin-Cancer-Classification
A deep learning project from University of Toronto's APS360 course 

**Note: The code should be implemented in Google Colab**

**File Distribution**

| File  | Description |
| ------------- | ------------- |
| img_proc.py  | Image Processing Functions  |
| model360.py  | Our Models  |
| APS360_Project.ipynb  | Main Code  |


**Primary Model**

![image](https://github.com/user-attachments/assets/47c946bb-479b-4582-82fc-8ad54682fbf1)


**Model Training**

We trained multiple neural network models using A100 gpu from Google Colab. A unique training procedure has been used where we alternate between CNN Layers and metadata / classification layers training.


**Results**

| **Model**            | EffNetB0 | EffNetB1 | EffNetB2 | EffNetB3 | ResNet18 | SEResNeXt50 | ResNest101 | SEResNeXt101 | Ensemble |
|------------------|:----------:|:----------:|:----------:|:----------:|:----------:|:--------------:|:------------:|:--------------:|:----------:|
| **Validation Balanced Accuracy** | 0.66 | 0.69 | 0.66 | 0.68 | 0.67 | 0.65 | 0.68 | 0.7 | 0.71 |


Presentation Video: https://youtu.be/OZsxupcjyW4
