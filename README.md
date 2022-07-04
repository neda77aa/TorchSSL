# TorchSSL


# Trying Microsoft's TorchSSL library for AS dataset

## Citing TorchSSL

If you think this toolkit or the results are helpful to you and your research, please cite our paper:

```
@article{zhang2021flexmatch},
  title={FlexMatch: Boosting Semi-supervised Learning with Curriculum Pseudo Labeling},
  author={Zhang, Bowen and Wang, Yidong and Hou, Wenxin and Wu, Hao and Wang, Jindong and Okumura, Manabu and Shinozaki, Takahiro},
  booktitle={Neural Information Processing Systems (NeurIPS)},
  year={2021}
}
```

## Maintainers

Yidong Wang<sup>1</sup>, Hao Chen<sup>2</sup>, Yue Fan<sup>3</sup>, Hao Wu<sup>1</sup>, Bowen Zhang<sup>1</sup>, Wenxin Hou<sup>1,4</sup>, Yuhao Chen<sup>5</sup>, Jindong Wang<sup>4</sup>

Tokyo Institute of Technology<sup>1</sup>

Carnegie Mellon University<sup>2</sup>

Max-Planck-Institut für Informatik<sup>3</sup>

Microsoft Research Asia<sup>4</sup>

Megvii<sup>5</sup>

## Contributing

1. You are welcome to open an issue on bugs, questions, and suggestions.
2. If you want to join TorchSSL team, please e-mail Yidong Wang (646842131@qq.com; yidongwang37@gmail.com) for more information. We plan to add more SSL algorithms and expand TorchSSL from CV to NLP and Speech.

## Statements

*For ImageNet datasets:* Please download the ImageNet 2014 dataset (unchanged from 2012) from the official site (link: https://image-net.org/challenges/LSVRC/2012/2012-downloads.php)
Extract the train and the val set into *subfolders* (the test set is not used), and put them under `train/` and `val/` respectively. Each subfolder will represent a class.
Note: the offical val set is not zipped into subfolders by classes, you may want to use: https://github.com/jiweibo/ImageNet/blob/master/valprep.sh, which is a nice script for preparing the file structure.

## References

[1] Antti Rasmus, Harri Valpola, Mikko Honkala, Mathias Berglund, and Tapani Raiko.  Semi-supervised learning with ladder networks. InNeurIPS, pages 3546–3554, 2015.

[2] Antti Tarvainen and Harri Valpola.  Mean teachers are better role models:  Weight-averagedconsistency targets improve semi-supervised deep learning results. InNeurIPS, pages 1195–1204, 2017.

[3] Dong-Hyun Lee et al. Pseudo-label: The simple and efficient semi-supervised learning methodfor  deep  neural  networks.   InWorkshop  on  challenges  in  representation  learning,  ICML,volume 3, 2013.

[4] Takeru Miyato, Shin-ichi Maeda, Masanori Koyama, and Shin Ishii. Virtual adversarial training:a regularization method for supervised and semi-supervised learning.IEEE TPAMI, 41(8):1979–1993, 2018.

[5] David Berthelot, Nicholas Carlini, Ian Goodfellow, Nicolas Papernot, Avital Oliver, and ColinRaffel. Mixmatch: A holistic approach to semi-supervised learning.NeurIPS, page 5050–5060,2019.

[6] Qizhe Xie, Zihang Dai, Eduard Hovy, Thang Luong, and Quoc Le. Unsupervised data augmen-tation for consistency training.NeurIPS, 33, 2020.

[7] David Berthelot, Nicholas Carlini, Ekin D Cubuk, Alex Kurakin, Kihyuk Sohn, Han Zhang,and Colin Raffel.   Remixmatch:  Semi-supervised learning with distribution matching andaugmentation anchoring. InICLR, 2019.

[8] Kihyuk Sohn, David Berthelot, Nicholas Carlini, Zizhao Zhang, Han Zhang, Colin A Raf-fel, Ekin Dogus Cubuk, Alexey Kurakin, and Chun-Liang Li.  Fixmatch:  Simplifying semi-supervised learning with consistency and confidence.NeurIPS, 33, 2020.

[9] Bowen Zhang, Yidong Wang, Wenxin Hou, Hao wu, Jindong Wang, Okumura Manabu, and Shinozaki Takahiro. FlexMatch: Boosting Semi-Supervised Learning with Curriculum Pseudo Labeling. NeurIPS, 2021.
