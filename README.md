---
author: sudo-0x2a
completion date: 04/28/2025
---

# Fine-tuning Inception-v4 with CIFAR-10 Dataset
A fine-tuning practice on a classical CNN model. The original Inception-v4 was trained on ImageNet, which outputs 1000 features on the final layer. By modifying the final layer and adjusting all weights to make the model suitable for the CIFAR-10 classification task.  
[CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)  
[Inception-v4](https://arxiv.org/abs/1602.07261)


## Results:
Validate both models on the same CIFAR-10 validation set.
|   | Before | After |
|:-:|:------:|:-----:|
| Accuracy | 0.02% | 95.77% |
| Loss | 9.47 | 0.1227 |

*Before the fine-tuning, the original pre-trained model is basically unusable.

## The Project Tested With the Following Setup:
- Hardware: Macbook Pro 14 M4 pro - 12C16G with 24GB RAM
- Python Version: 3.11.12
