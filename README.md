# High-Capacity Expert Binary Networks (ICLR 2021)

(Note that this repository is for seminar in MLILAB) This code provides the core components for building networks based on the architectures and Expert Binary Convolutional Block introduced in the _High-Capacity Expert Binary Networks_ paper. You can find the full version of the paper [here](https://arxiv.org/pdf/2010.03558).

## 1. Installation
The repository is based on python==3.7

### 1.1 Requirements
You can install requirements by

    pip install -r requirements.txt


### 1.2. Data preparation
 Download the dataset from the official [webpage](http://image-net.org/download-images), creating a folder with the following structure: 
```
│imagenet/
├──train/
│  ├── n01440764
│  │   ├── n01440764_10026.JPEG
│  │   ├── n01440764_10027.JPEG
│  │   ├── ......
│  ├── ......
├──val/
│  ├── n01440764
│  │   ├── ILSVRC2012_val_00000293.JPEG
│  │   ├── ILSVRC2012_val_00002138.JPEG
│  │   ├── ......
│  ├── ......
```
You can construct this structure using for example the script found [here](https://gist.github.com/BIGBALLON/8a71d225eff18d88e469e6ea9b39cef4).

## 2. Task
Modify the code (Refer to #ToDo marks). You may freely modify any segment.
1. 
## Sample Result
