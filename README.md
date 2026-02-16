# Car-1000: A New Large Scale Fine-Grained Visual Categorization Dataset

[![arXiv](https://img.shields.io/badge/arXiv-2503.12385-b31b1b.svg)](https://arxiv.org/abs/2503.12385)

## Introduction

> *Fine-grained visual categorization (FGVC) is a challenging but significant task in computer vision, which aims to recognize different sub-categories of birds, cars, airplanes, etc. Among them, recognizing models of different cars has significant application value in autonomous driving, traffic surveillance and scene understanding, which has received considerable attention in the past few years. However, Stanford-Car, the most widely used fine-grained dataset for car recognition, only has 196 different categories and only includes vehicle models produced earlier than 2013. Due to the rapid advancements in the automotive industry during recent years, the appearances of various car models have become increasingly intricate and sophisticated. Consequently, the previous Stanford-Car dataset fails to capture this evolving landscape and cannot satisfy the requirements of automotive industry. To address these challenges, in our paper, we introduce Car-1000, a large-scale dataset designed specifically for fine-grained visual categorization of diverse car models. Car-1000 encompasses vehicles from 166 different automakers, spanning a wide range of 1000 distinct car models. Additionally, we have reproduced several state-of-the-art FGVC methods on the Car-1000 dataset, establishing a new benchmark for research in this field. We hope that our work will offer a fresh perspective for future FGVC researchers.*

## Dataset Composition

The Car-1000 dataset is distinguished by its scale and diversity:

- **Categories**: 1,000 distinct car models.
- **Images**: 140,267 high-quality images.
- **Automakers**: Vehicles from 166 different automakers.

### File Structure

```text
Car-1000-dataset/
├─ all_images/
│  ├─ 0000/
│  │  ├─ 0000_0001.jpg
│  │  └─ ...
│  └─ <category_id>/
│     ├─ <category_id>_0001.jpg
│     └─ ...
├─ dataset_split/
│  └─ dataset_split.json      # dataset split information (e.g., id/train_data/val_data/test_data)
└─ cls_info/
   └─ class_info.json         # class information (e.g., id/name_from_new/name_from_old/type_info)
```

## Download

Our data could be found at:

- [Baidu Cloud]
- [Google Drive]

You can find all the images, along with the dataset split and the detailed information of each category.

## Citation

If you find this dataset useful for your research, please cite our paper:

```bibtex
@misc{hu2025car1000newlargescale,
      title={Car-1000: A New Large Scale Fine-Grained Visual Categorization Dataset}, 
      author={Yutao Hu and Sen Li and Jincheng Yan and Wenqi Shao and Xiaoyan Luo},
      year={2025},
      eprint={2503.12385},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2503.12385}, 
}
```

[Baidu Cloud]: https://pan.baidu.com/s/1jcHgMuar1iDoa2pBh3VweA?pwd=xnkf
[Google Drive]: https://drive.google.com/file/d/1o60KmvCRA7GhPKw6XlaVI2hkuzJvEJbg/view?usp=sharing
