# VER🗣️

The official repo for "[VER: Unifying Verbalizing Entities and Relations](https://arxiv.org/abs/2211.11093)" (Findings of EMNLP '23)


## Introduction

We pretrain VER🗣️: A Unified Model for **V**erbalizing **E**ntities and **R**elations. The model takes any entity or entity set as input and generates a sentence to represent the entities and relations.

![image](https://user-images.githubusercontent.com/47152740/203205857-76643bae-9ba9-4b7d-828b-d6320a55f395.png)

## Requirements

See `requirements.txt`.

## Models

We release the `[RE]VER-base` models on [this link](https://osf.io/7csnf/?view_only=91ec67e05bd44f998d71e63d9cdd25a4) and the `[RE]VER-large` models on [this link](https://drive.google.com/drive/folders/1hvv467D_vsO_4kCZUgPMykz27wZSHWuK?usp=sharing).

## Data

The WiV data are available on [this link](https://osf.io/7csnf/?view_only=91ec67e05bd44f998d71e63d9cdd25a4).

## Preprocessing

You may refer to the preprocessing script on [this repo](https://github.com/jeffhj/open-relation-modeling). 

## Training

```
bash train.sh
```

You can find other scripts (e.g., evaluation)  on [this repo](https://github.com/jeffhj/open-relation-modeling). 

## Citation

The details of this repo are described in the following paper:

```
@inproceedings{huang2023ver,
  title={VER: Unifying Verbalizing Entities and Relations},
  author={Huang, Jie and Chang, Kevin Chen-Chuan},
  booktitle={Findings of the Association for Computational Linguistics: EMNLP 2023},
  pages={15700--15710},
  year={2023}
}
```
