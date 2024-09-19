# Unsupervised Source-free Cross-modal Adaptation for Event-based Object Recognition

EventDance: Unsupervised Source-free Cross-modal Adaptation for Event-based
Object Recognition [pdf](https://openaccess.thecvf.com/content/CVPR2024/papers/Zheng_EventDance_Unsupervised_Source-free_Cross-modal_Adaptation_for_Event-based_Object_Recognition_CVPR_2024_paper.pdf)

<img width="552" alt="image" src="https://github.com/user-attachments/assets/107b72de-a707-43e5-82ad-a5843a10ab28">

EventDance++: Language-guided Unsupervised Source-free Cross-modal Adaptation for Event-based Object Recognition [pdf]()

## Update
[09/2024], codes for EventDance++ are in progress.
[07/2024], codes for evaluation are released.

## Environments
```
git clone --
cd --
conda create -n evd python=3.9
conda activate evd
pip install -r requirements.txt
```

## Data Preparation
Used Datasets: 
Event Modality: [NMNIST]() / [NCALTECH101]() / [NCIFAR10]() 
Image Modality: [MNIST]() / [CALTECH101]() / [CIFAR10]() 
```
datasets/
├── NMIST
│   ├── Test
│   └── Train
├── MNIST
│   ├── image
│   └── raw
├── NCALTECH101
│   ├── accordion
│   │   ...
│   └── yin_yang
├── CALTECH101
│   ├── 101_ObjectCategories
│   └── Annotations
```

## References
We appreciate the previous open-source works: [Back to Event Basics: Self-Supervised Learning of Image Reconstruction for Event Cameras via Photometric Constancy](https://openaccess.thecvf.com/content/CVPR2021/papers/Paredes-Valles_Back_to_Event_Basics_Self-Supervised_Learning_of_Image_Reconstruction_for_CVPR_2021_paper.pdf)

## Citations
If you are interested in this work, please cite the following works: 
```
@inproceedings{zheng2024eventdance,
  title={EventDance: Unsupervised Source-free Cross-modal Adaptation for Event-based Object Recognition},
  author={Zheng, Xu and Wang, Lin},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={17448--17458},
  year={2024}
}
```
