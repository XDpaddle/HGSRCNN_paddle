# Hgsrcnn_paddle

## A heterogeneous group CNN for image super-resolution

Paddle 复现版本

## 数据集

DIV2K
## 训练步骤
### train sr
```bash
python train.py -opt config/train/train_hgsrcnn_xx.yml
```
## 测试步骤
```bash
python test.py -opt config/test/test_hgsrcnn_xx.yml
```