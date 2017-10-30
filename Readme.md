# Resnet-Swish

[resnet] + [swish] + [training on ImageNet] in PyTorch

[resnet]: https://github.com/pytorch/vision/blob/master/torchvision/models/resnet.py
[swish]: https://arxiv.org/pdf/1710.05941.pdf
[training on ImageNet]: https://github.com/pytorch/examples/blob/master/imagenet/main.py

## Note

These code is written using pytorch version `67839ce`, which is higher than the latest stable release `0.2.0`.

In `swish.py` it supports in-place option but it is NOT working in pytorch 0.2.0. If you are using older version please turn it off.
