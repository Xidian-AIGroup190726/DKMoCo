# DKMoCo
## Installation
Clone the repository and run

```bash
conda env create --name DKMoCo --file env.yml
conda activate DKMoCo

## Pretrain and Evaluation

Two-Stage Pre-training

```python -m Pretrained.train_moco```

Fine-tuning and Testing

```python -m Downstream.train_and_test```

## Xi'an Urban Dataset

We released the xi'an urban dataset in the xian urban.zip

