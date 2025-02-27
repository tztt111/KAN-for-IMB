## Learning Imbalanced Datasets with KAN


### Training 

We provide several training examples with this repo:

- To train the resnet baseline on long-tailed imbalance with ratio of 100

```bash
python cifar_train.py --gpu 0 --imb_type exp --imb_factor 0.01 --loss_type LA --train_rule None
```

- To train with kan training on long-tailed imbalance with ratio of 100

```bash

python cifar_train_la.py --gpu 0 --imb_type exp --imb_factor 0.01 --loss_type LA --train_rule None --kan      
```
