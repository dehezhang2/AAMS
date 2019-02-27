# Attention-aware Multi-stroke Style Transfer

This is the offical Tensorflow implementation of [Attention-aware Multi-stroke Style Transfer](https://arxiv.org/abs/1901.05127), CVPR 2019

## Requirement
- python (version 2.7)
- Tensorflow (>=1.4)
- Numpy
- Matplotlib

## Usage
### Test

```
$ python test.py --model tfmodel/aams.pb \
                        --content images/content/lenna_cropped.jpg \
                        --style images/style/candy.jpg \
                        --inter_weight 1.0
```
### Train
```
$ python train.py --dataset datasets/COCO_Datasets/val2014
```

## Examples
<div align='center'>
  <img src='https://github.com/JianqiangRen/AAMS/blob/master/images/guideline/fig1.jpg?raw=true' height="350px">
</div>



## Acknowledgement
we acknowledge [avatar-net](https://github.com/LucasSheng/avatar-net) for their work.