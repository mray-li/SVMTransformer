# SVMTransformer
This is a project of implementing SVM Transformer to do machine translation tasks, written in PyTorch. The theory is based on ["Transformers as Support Vector Machines"](https://arxiv.org/abs/2308.16898)



# TIPs
The link for Dataset Multi30k is broken, so I changed the urls inside torchtext into the following:
```
URL = {
    "train": r"https://raw.githubusercontent.com/neychev/small_DL_repo/master/datasets/Multi30k/training.tar.gz",
    "valid": r"https://raw.githubusercontent.com/neychev/small_DL_repo/master/datasets/Multi30k/validation.tar.gz",
    "test": r"https://raw.githubusercontent.com/neychev/small_DL_repo/master/datasets/Multi30k/mmt16_task1_test.tar.gz",
}
```
for more information please see this page, https://github.com/pytorch/text/issues/1756
