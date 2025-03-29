# Deep CNNs for Palm Fruit Maturity Classification

A deep learning-based classification method for **palm fruit maturity** using **CNN models**, including **ResNet50** and **InceptionV3**. This project leverages **transfer learning** with fine-tuning to classify palm fruit bunches into five maturity stages: **unripe, under-ripe, medium-ripe, ripe, and over-ripe**.

## 🚀 Features
- **Deep CNN models**: Baseline CNN, ResNet50, and InceptionV3
- **Transfer learning** with pre-trained models
- **Dataset preprocessing** and augmentation
- **Evaluation metrics**: Accuracy, AUC, F1-score, ROC curves, and confusion matrices

## 📂 Dataset
The original dataset can be found [here](https://ieee-dataport.org/open-access/date-fruit-dataset-automated-harvesting-and-visual-yield-estimation) and was modified for this study. The modified version, which can be downloaded [here](https://drive.google.com/file/d/1qTVoWL0EDdJx6Soj_4sPpOOAySKeJeBq/view?usp=drive_link), consists of images captured in natural orchard environments. The dataset was split into 80% for training and 20% for testing.

## 📖 Citation

You can access the full paper [here](https://arxiv.org/abs/2502.20223).

If you use this work, please cite:

```bibtex
@article{han2025deep,
  title={Deep Convolutional Neural Networks for Palm Fruit Maturity Classification},
  author={Han, Mingqiang and Yi, Chunlin},
  journal={arXiv preprint arXiv:2502.20223},
  year={2025},
  archivePrefix={arXiv},
  primaryClass={cs.CV}
}
