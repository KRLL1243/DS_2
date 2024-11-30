# Generative adversarial network CycleGAN

## Dataset
[Click here](https://www.kaggle.com/datasets/suyashdamle/cyclegan?select=facades)

## Example of images
<img src="/hw4/implementations/cyclegan/example_A.png" width="256" height="256"/><img src="/hw4/implementations/cyclegan/example_B.png" width="256" height="256"/>

## Сommand
```
python cyclegan.py --dataset_name facades --n_epochs 50 --decay_epoch 25 --checkpoint_interval 50
```

## Interim results
### Beginning of training
![0.png](/hw4/implementations/cyclegan/images/facades/0.png)

### 1/4 of training
![5000.png](/hw4/implementations/cyclegan/images/facades/5000.png)

### 1/2 of training
![10000.png](/hw4/implementations/cyclegan/images/facades/10000.png)

### 2/3 of training
![17500.png](/hw4/implementations/cyclegan/images/facades/17500.png)

## Final result
![19800.png](/hw4/implementations/cyclegan/images/facades/19800.png)

![19900.png](/hw4/implementations/cyclegan/images/facades/19900.png)



[Original git-repository](https://github.com/eriklindernoren/PyTorch-GAN/tree/master/implementations/cyclegan)