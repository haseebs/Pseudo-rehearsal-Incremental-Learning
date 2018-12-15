# Distillation Techniques for Pseudo-rehearsal Based Incremental Learning
This repository contains the Pytorch code for [Distillation Techniques for Pseudo-rehearsal Based Incremental Learning](https://arxiv.org/abs/1807.02799).

**Abstract:**
The ability to learn from incrementally arriving data is essential for any life-long learning system. However, standard deep neural networks forget the knowledge about the old tasks, a phenomenon called catastrophic forgetting, when trained on incrementally arriving data. We discuss the biases in current Generative Adversarial Networks (GAN) based approaches that learn the classifier by knowledge distillation from previously trained classifiers. These biases cause the trained classifier to perform poorly. We propose an approach to remove these biases by distilling knowledge from the classifier of AC-GAN. Experiments on MNIST and CIFAR10 show that this method is comparable to current state of the art rehearsal based approaches.

## Dependencies
The requirements.txt file contains all the dependencies along with their specific versions. These dependencies can be fulfilled by using `pip install -r requirements.txt`

## Usage
Use the following interface to run the experiments. The description for each argument is given in the runExperiment.py file.

```
python runExperiment.py [-h] [--batch-size N] [--test-batch-size N]
                        [--epochs N] [--lr LR]
                        [--schedule SCHEDULE [SCHEDULE ...]]
                        [--gammas GAMMAS [GAMMAS ...]] [--momentum M]
                        [--no-cuda] [--no-distill] [--no-random]
                        [--no-herding] [--seed S] [--log-interval N]
                        [--model-type MODEL_TYPE] [--name NAME]
                        [--sortby SORTBY] [--decay DECAY]
                        [--step-size STEP_SIZE]
                        [--memory-budget MEMORY_BUDGET]
                        [--epochs-class EPOCHS_CLASS] [--dataset DATASET]
                        [--no-upsampling] [--process PROCESS]
                        [--gan-epochs GAN_EPOCHS [GAN_EPOCHS ...]]
                        [--gan-d GAN_D] [--gan-lr GAN_LR]
                        [--gan-batch-size GAN_BATCH_SIZE]
                        [--gan-num-examples GAN_NUM_EXAMPLES]
                        [--gan-schedule GAN_SCHEDULE [GAN_SCHEDULE ...]]
                        [--gan-gammas GAN_GAMMAS [GAN_GAMMAS ...]]
                        [--persist-gan]
                        [--gan-img-save-interval GAN_IMG_SAVE_INTERVAL]
                        [--d-iter D_ITER] [--ckpt-interval CKPT_INTERVAL]
                        [--load-g-ckpt LOAD_G_CKPT] [--T T] [--save-g-ckpt]
                        [--gan-save-classes GAN_SAVE_CLASSES]
                        [--label-smoothing] [--minibatch-discrimination]
                        [--ideal-nmc] [--optimize-features]
                        [--optimize-feat-epochs OPTIMIZE_FEAT_EPOCHS]
                        [--optimize-feat-lr OPTIMIZE_FEAT_LR]
                        [--joint-gan-obj] [--joint-gan-alpha JOINT_GAN_ALPHA]
                        [--ac-distill] [--filter-using-disc]
                        [--filter-val FILTER_VAL] [--disc-eval]
```

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
