# HCLR-Net
```
This Repo includes the training and testing codes of our HCLR-Net. (Pytorch Version)
If you use our code, please cite our paper and hit the star at the top-right corner. Thanks!
```

# Requirement
```
PyTorch  1.9.0
Python  3.8
Cuda  11.1
pip install pytorch_lightning
Download '/core' from "https://github.com/Hikari0608/Eval
```
## Testing

```
0.Download '/core' from "https://github.com/Hikari0608/Eval" or you could use pyiqa
1.Download the code and unzip to '/'
2.Put your testing images in the "test_images" 
3.bash eval.sh
```
For your convenience, we provide all paired training data and testing data used in our paper. 
the weight download url: coming soon




## Training
```
1. Download the code
2. Python train.py
3. Find checkpoint in the ./tb_logs/UCR/version_0/checkpoints

The training data are in the "./Datasets/train/input" folder (underwater images) and "./Datasets/train/gt" folder (ground truth images).
The validation data are in the "./Datasets/val/input" folder (underwater images) and "./Datasets/val/input" folder (ground truth images).
```
