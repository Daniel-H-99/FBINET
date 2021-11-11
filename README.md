# High-Capacity Expert Binary Networks (ICLR 2021)

(Note that this repository is for seminar in MLILAB) This code provides the core components for building networks based on the architectures and Expert Binary Convolutional Block introduced in the _High-Capacity Expert Binary Networks_ paper. You can find the full version of the paper [here](https://arxiv.org/pdf/2010.03558).

## 1. Installation
The repository is based on python==3.7

### 1.1 Requirements
You can install requirements by

    pip install -r requirements.txt


### 1.2. Data preparation
 You can download tiny imagenet data by

    sh tinyimagenet.sh

 The data folder may be like the following structure: 
```
│imagenet/
├──train/
│  ├── n01440764
│  │   ├── n01440764_10026.JPEG
│  │   ├── n01440764_10027.JPEG
│  │   ├── ......
│  ├── ......
├──valid/
│  ├── n01440764
│  │   ├── ILSVRC2012_val_00000293.JPEG
│  │   ├── ILSVRC2012_val_00002138.JPEG
│  │   ├── ......
│  ├── ......
```

## 2. Task
+Complete Expert Binary Convolution (models/ebconv.py)
+Train your model with n_experts = 4, width_multiplier = 2 and report result
+Refer to 2 - step training strategy 
+Try 2 modification of model
+Varying Number of experts / Width Multiplier
+Replacement of Softmax with Sigmoid
+Varying temperature in Softmax
+Varying number of groups for grouped convolution
+…
+Try to add inference time as well as  accuracy when reporting results
+Refer to opts.py for conducting experiments
