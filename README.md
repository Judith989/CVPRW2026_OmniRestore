# OmniRestore: A Parameter-Efficient Framework for Universal Adverse-Weather Image Restoration

Official project page for our CVPR Workshop 2026 paper.

## Overview
OmniRestore is a lightweight multimodal framework for universal adverse-weather image restoration across:
- Rain
- Snow
- Fog / haze
- Low-light
- Composite degradations

Our method combines:
- CLIP-guided weather semantic conditioning
- KAN-enhanced multimodal embeddings
- Lightweight hybrid attention restoration backbone
- Adaptive refinement stage (ARS)

Despite using only **2.6M parameters**, OmniRestore achieves state-of-the-art restoration quality on CDD-11 and multiple adverse-weather benchmarks.

---

## Paper
[CVPR Workshop Paper](https://openaccess.thecvf.com/content/CVPR2026W/NTIRE/papers/Njoku_OmniRestore_A_Parameter-Efficient_Framework_for_Universal_Adverse-Weather_Image_Restoration_CVPRW_2026_paper.pdf)

## Supplementary Material
[Supplementary PDF](https://openaccess.thecvf.com/content/CVPR2026W/NTIRE/supplemental/Njoku_OmniRestore_A_Parameter-Efficient_CVPRW_2026_supplemental.pdf)

## Authors
- Judith N. Njoku
- Diksha Shukla

Department of Electrical Engineering & Computer Science  
University of Wyoming, USA

## Citation
```bibtex
@InProceedings{Njoku_2026_CVPR,
    author    = {Njoku, Judith and Shukla, Diksha},
    title     = {OmniRestore: A Parameter-Efficient Framework for Universal Adverse-Weather Image Restoration},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    month     = {June},
    year      = {2026},
    pages     = {2236-2246}
}