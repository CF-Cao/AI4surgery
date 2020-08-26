<div align="center">
<a href="http://camma.u-strasbg.fr/">
<img src="figs/data_camma_logo_tr.png" width="20%">
</a>
</div>

# AI4Surgery

**Neural Networks and Deep Learning**

_Deepak Alapatt and Pietro Mascagni, Vinkle Srivastav, Nicolas Padoy_

This short tutorial is designed to offer hands-on experience with artifical neural networks to surgeons with little to no coding experience.  

Following the structure of the associated "Neural Networks and Deep Learning" chapter from the "Artificial Intelligence in Surgery: An AI Primer for Surgical Practice" book, this notebook walks the users through a basic neural network implementation pipeline, from basic programming concepts to data handling and deep learning operations.      Finally, the user will be able to design, train and test a simple neural network for surgical tool classification.

<br/><br/>

<div align="center">
<a href="http://camma.u-strasbg.fr/">
<img src="figs/neural_network.png" width="60%">
</a>
</div>

<br/><br/>


To begin, click the link below to launch your experiments in Google Colab, a cloud based platform giving you access to GPUs and TPUs to speed up your training.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15KAgReMRRL3W6wWZzyiN5IISyHT4WYn5)

## License
This source code, dataset, and annotations are licensed under the license found in the [`LICENSE`](LICENSE) file in the root directory of this source tree.
The modified Cholec80 dataset used in this repository is publicly released under the Creative Commons licence CC-BY-NC-SA 4.0. This implies that:
- the dataset cannot be used for commercial purposes,
- the dataset can be transformed (additional annotations, etc.),
- the dataset can be redistributed as long as it is redistributed under the same license with the obligation to cite the contributing work which led to the generation of the Cholec80 dataset (mentioned below).

By downloading and using this dataset, you agree on these terms and conditions.

## Citation
```bibtex
@book{alapatt2021aiinsurgery,
  author       = {Deepak Alapatt, Pietro Mascagni, Vinkle Srivastav, Nicolas Padoy}, 
  title        = {Artificial Intelligence in Surgery: Understanding the Role of AI in Surgical Practice (chapter: Neural Networks and Deep Learning)},
  publisher    = {McGraw-Hill Education / Medical},
  language     = {English},
  year         = 2021,
  volume       = 1,
  ISBN-10      = {1260452735},
  ISBN-13      = {978-1260452730}
}
```
If you use the Cholec80 dataset or the variant used in the demo notebook, you are kindly requested to cite the work that led to the generation of this dataset:
```bibtex
@article{twinanda2016endonet,
  title={Endonet: a deep architecture for recognition tasks on laparoscopic videos},
  author={Twinanda, Andru P and Shehata, Sherif and Mutter, Didier and Marescaux, Jacques and De Mathelin, Michel and Padoy, Nicolas},
  journal={IEEE transactions on medical imaging},
  volume={36},
  number={1},
  pages={86--97},
  year={2016},
  publisher={IEEE}
}
```
[[`Download PDF`](https://arxiv.org/abs/1602.03012)]

