# Distillation Techniques for Pseudo-rehearsal Based Incremental Learning
This repository contains the Pytorch code for the paper:

**Title:** [Distillation Techniques for Pseudo-rehearsal Based Incremental Learning](https://arxiv.org/abs/1807.02799).

**Authors:** Haseeb Shah, Khurram Javed and Faisal Shafait

**Affiliation:** National University of Science and Technology.

**Abstract:**
The ability to learn from incrementally arriving data is essential for any life-long learning system. However, standard deep neural networks forget the knowledge about the old tasks, a phenomenon called catastrophic forgetting, when trained on incrementally arriving data. We discuss the biases in current Generative Adversarial Networks (GAN) based approaches that learn the classifier by knowledge distillation from previously trained classifiers. These biases cause the trained classifier to perform poorly. We propose an approach to remove these biases by distilling knowledge from the classifier of AC-GAN. Experiments on MNIST and CIFAR10 show that this method is comparable to current state of the art rehearsal based approaches.

## Dependencies
The requirements.txt file contains all the dependencies along with their specific versions. These dependencies can be fulfilled by using `pip install -r requirements.txt`

## Usage
TODO

## Results
TODO

## Paper citation
If you used this code for your experiments or found it helpful, consider citing the following paper:
```
@article{2018arXiv180702799S,
   author = {{Shah}, H. and {Javed}, K. and {Shafait}, F.},
    title = "{Distillation Techniques for Pseudo-rehearsal Based Incremental Learning}",
  journal = {ArXiv e-prints},
     year = 2018,
}
```
