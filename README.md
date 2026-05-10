# Awesome Binary Neural Networks

[![Awesome][awesome-badge]][awesome-link]

> A curated list of binary, ternary (1.58-bit), and 2-bit neural network research papers, software packages, and resources.


## Table of Contents

- [Research Papers](#research-papers)
- [Software and Repositories](#software-and-repositories)
- [Organisations](#organisations)
- [Relevant Awesome Lists](#relevant-awesome-lists)
- [Contribute](#contribute)
- [Credits](#credits)
- [License](#license)

## Research Papers

This section contains research papers in chronological order, spanning from the early foundations of BNNs to the modern era of 1-bit and 1.58-bit Large Language Models.

- [BinaryConnect: Training Deep Neural Networks with binary weights during propagations](https://arxiv.org/abs/1511.00363)
    - 2015
    - Matthieu Courbariaux, Yoshua Bengio, Jean-Pierre David
- [Binarized Neural Networks: Training Deep Neural Networks with Weights and Activations Constrained to +1 or -1](https://arxiv.org/abs/1602.02830)
    - 2016
    - Matthieu Courbariaux, Itay Hubara, Daniel Soudry, Ran El-Yaniv, Yoshua Bengio
- [XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks](https://arxiv.org/abs/1603.05279)
    - 2016
    - Mohammad Rastegari, Vicente Ordonez, Joseph Redmon, Ali Farhadi
- [Convolutional Networks for Fast, Energy-Efficient Neuromorphic Computing](https://arxiv.org/abs/1603.08270)
    - 2016
    - Steven K. Esser, Paul A. Merolla, John V. Arthur, Andrew S. Cassidy, Rathinakumar Appuswamy, Alexander Andreopoulos, David J. Berg, Jeffrey L. McKinstry, Timothy Melano, Davis R. Barch, Carmelo di Nolfo, Pallab Datta, Arnon Amir, Brian Taba, Myron D. Flickner, Dharmendra S. Modha
- [Ternary Weight Networks](https://arxiv.org/abs/1605.04711)
    - 2016
    - Fengfu Li, Bo Zhang, Bin Liu
- [DoReFa-Net: Training Low Bitwidth Convolutional Neural Networks with Low Bitwidth Gradients](https://arxiv.org/abs/1606.06160)
    - 2016
    - Shuchang Zhou, Yuxin Wu, Zekun Ni, Xinyu Zhou, He Wen, Yuheng Zou
- [Flexible Network Binarization with Layer-wise Priority](https://arxiv.org/abs/1709.04344)
    - 2017
    - Lixue Zhuang, Yi Xu, Bingbing Ni, Hongteng Xu
- [ReBNet: Residual Binarized Neural Network](https://arxiv.org/abs/1711.01243)
    - 2017
    - Mohammad Ghasemzadeh, Mohammad Samragh, Farinaz Koushanfar
- [Towards Accurate Binary Convolutional Neural Network](https://arxiv.org/abs/1711.11294)
    - 2017
    - Xiaofan Lin, Cong Zhao, Wei Pan
- [Training a Binary Weight Object Detector by Knowledge Transfer for Autonomous Driving](https://arxiv.org/abs/1804.06332)
    - 2018
    - Jiaolong Xu, Peng Wang, Heng Yang, Antonio M. López
- [Self-Binarizing Networks](https://arxiv.org/abs/1902.00730)
    - 2019
    - Fayez Lahoud, Radhakrishna Achanta, Pablo Márquez-Neila, Sabine Süsstrunk
- [Latent Weights Do Not Exist: Rethinking Binarized Neural Network Optimization](https://arxiv.org/abs/1906.02107)
    - 2019
    - Koen Helwegen, James Widdicombe, Lukas Geiger, Zechun Liu, Kwang-Ting Cheng, Roeland Nusselder
- [Least squares binary quantization of neural networks](https://arxiv.org/abs/2001.02786v1)
    - 2020
    - Hadi Pouransari, Oncel Tuzel
- [Widening and Squeezing: Towards Accurate and Efficient QNNs](https://arxiv.org/abs/2002.00555)
    - 2020
    - Chuanjian Liu, Kai Han, Yunhe Wang, Hanting Chen, Chunjing Xu, Qi Tian
- [MeliusNet: Can Binary Neural Networks Achieve MobileNet-level Accuracy?](https://arxiv.org/abs/2001.05936)
    - 2020
    - Joseph Bethge, Christian Bartz, Haojin Yang, Ying Chen, Christoph Meinel
- [FracBNN: Accurate and FPGA-Efficient Binary Neural Networks with Fractional Activations](https://arxiv.org/abs/2012.11800)
  - 2021
  - Yichi Zhang, Junhao Pan, Xinheng Liu, Hongzheng Chen, Deming Chen, Zhiru Zhang
- [Binary Neural Networks as a general-propose compute paradigm for on-device computer vision](https://arxiv.org/abs/2202.03716)
  - 2022
  - Haojin Yang, Martin Danelljan, et al.
- [BitNet: Scaling 1-bit Transformers for Large Language Models](https://arxiv.org/abs/2310.11453)
  - 2023
  - Hongyu Wang, Shuming Ma, Li Dong, Shaohan Huang, et al. (Microsoft)
- [The Era of 1-bit LLMs: All Large Language Models are in 1.58 Bits](https://arxiv.org/abs/2402.17764)
  - 2024
  - Shuming Ma, Hongyu Wang, Lingxiao Ma, Lei Wang, et al. (Microsoft)
- [A&B BNN: Add&Bit-Operation-Only Hardware-Friendly Binary Neural Network](https://openaccess.thecvf.com/content/CVPR2024/html/Ma_AB_BNN_AddBit-Operation-Only_Hardware-Friendly_Binary_Neural_Network_CVPR_2024_paper.html)
  - 2024
  - Ruichen Ma, Guanchao Qiao, Yian Liu, Liwei Meng, Ning Ning, Yang Liu, Shaogang Hu
- [BitNet b1.58 2B4T Technical Report](https://arxiv.org/abs/2504.12285)
  - 2025
  - Microsoft Research
- [1 BIT IS ALL WE NEED: Binary Normalized Neural Networks](https://arxiv.org/abs/2509.07025)
  - 2025
  - Eduardo Lobo Lustoda Cabral, Paulo Pirozelli, Larissa Driemeier

## Software and Repositories

- [Larq](https://github.com/larq/larq) - An open-source deep learning library based on the `tf.keras` interface.
- [microsoft/BitNet](https://github.com/microsoft/BitNet) - Official inference framework (bitnet.cpp) for 1-bit LLMs and 1.58-bit models (e.g., BitNet b1.58).
- [kevbuh/bitnet](https://github.com/kevbuh/bitnet) - A pure PyTorch implementation of Microsoft's BitNet b1.58 2B4T binarized LLaMA-style LLM.
- [hpi-xnor/BMXNet-v2](https://github.com/hpi-xnor/BMXNet-v2) - An open-source binary neural network implementation based on MXNet.
- [hpi-xnor/bitorch](https://github.com/hpi-xnor/bitorch) - An open-source implementation of Binary Neural Networks within PyTorch.
- [Ruichen0424/AB-BNN](https://github.com/Ruichen0424/AB-BNN) - The official PyTorch implementation for the CVPR 2024 paper "A&B BNN".

## Organisations

- [Plumerai](https://www.plumerai.com/) - Plumerai is enabling devices like robots and drones to use deep learning locally and in real-time with binarised neural networks.
- [Microsoft Research](https://www.microsoft.com/en-us/research/) - Pioneers of the BitNet architecture, advancing the "Era of 1-bit and 1.58-bit LLMs" to democratize large language models.

## Relevant Awesome Lists

* [awesome-awesome](https://github.com/emijrp/awesome-awesome)
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)
* [sindresorhus/awesome](https://github.com/sindresorhus/awesome)
* [The Warren](https://github.com/torchhound/warren)

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## Credits

This project was initially created with [Cookiecutter][cookiecutter] and the custom [cookiecutter-awesome][cookiecutter-awesome] :cookie:

## License

[![CC0][CC0-badge]][CC0-link]

To the extent possible under law, Michael Tinsley has waived all copyright
and related or neighboring rights to this work. See [LICENSE](LICENSE).

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
[awesome-link]: https://github.com/sindresorhus/awesome
[CC0-badge]: http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg
[CC0-link]: https://creativecommons.org/publicdomain/zero/1.0/
[cookiecutter]: https://github.com/audreyr/cookiecutter
[cookiecutter-awesome]: https://github.com/moodule/cookiecutter-git
