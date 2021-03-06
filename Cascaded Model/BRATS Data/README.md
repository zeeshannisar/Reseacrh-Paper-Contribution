The entire experiments and evaluations for BRATS data had carried out on BRATS 2017 dataset. We have used
[**CycleGAN:Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks**](https://arxiv.org/abs/1703.10593) as our
**Base-Network/Step-1** to generate a normal distribution against an anomalous distribution. **Step-1** is used for generating pairs i.e., for each anomalous image we get a normal image. The results of the **Step-1** seems like below.

![Step-1 Results](https://github.com/zeeshannisar/Reseacrh-Paper-Contribution/blob/master/Cascaded%20Model/BRATS%20Data/outputs/output-step%231.png)

Finally we have introduced an approach as **Step-2** to detect the infectious region using the concept of **what mask M(x) added to x changes it to y** as stated in [**Visual Feature Attribution using Wasserstein GANs**](https://arxiv.org/abs/1711.08998). In addition to masks we have also generate heatmaps for a better visualization.

![Step-2 Results](https://github.com/zeeshannisar/Reseacrh-Paper-Contribution/blob/master/Cascaded%20Model/BRATS%20Data/outputs/output-step%232.png)


