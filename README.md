# Domain Generalization via Rationale Invariance (ICCV'23)

Official PyTorch implementation of "Domain Generalization via Rationale Invariance".

Liang Chen, Yong Zhang, Yibing Song, Anton van den Hengel, Lingqiao Liu

## Preparation

### Dependencies

```sh
pip install -r requirements.txt
```

### Datasets

```sh
python -m domainbed.scripts.download --data_dir=/my/datasets/path
```

### Environments

Environment details used for the main experiments. Every main experiment is conducted on a single NVIDIA V100 GPU.

```
Environment:
	Python: 3.7.7
	PyTorch: 1.7.1
	Torchvision: 0.8.2
	CUDA: 10.1
	CUDNN: 7603
	NumPy: 1.21.4
	PIL: 7.2.0
```

## Citation

```
@inproceedings{chen2023domain,
  title={Domain Generalization via Rationale Invariance},
  author={Chen, Liang and Zhang, Yong and Song, Yibing and Hengel, Anton van den and Liu, Lingqiao},
  booktitle={ICCV},
  year={2023}
}

```

Please contact me via email (liangchen527@gmail.com) if you have any questions regarding this project.
