# VIPER: Vision-based system to detect potential predators for herding with robots

This repository introduces a vision system designed for deployment within a ROS2 node to enable autonomous flock herding by detecting potential predators, such as wolves. A pre-trained YOLOv8 model and a pre-trained YOLOv9 model have been fine-tuned to incorporate additional classes not originally supported, including wolves. The models have been re-trained using both the COCO dataset and a newly curated dataset while preserving recognition of previously learned classes alongside the new ones. To achieve this, a dataset of wolf images in open environments was collected and annotated for instance segmentation. The resulting vision model is integrated into a ROS2 node, allowing deployment on robotic platforms such as quadruped robots or rovers. With this vision-based system, a robot can detect potential predators and provide valuable information to the herder, helping to avoid areas where the flock may be at risk. This technology has the potential to enhance extensive livestock farming by assisting in daily herding tasks.

## 📖 Citation

If you use our work, please cite the following paper:

```bibtex
@InProceedings{10.1007/978-3-031-74186-9_18,
  author = "Yang, Xiao and Carnicero, Abel and S{\'a}nchez-Gonz{\'a}lez, Lidia and Rodr{\'i}guez-Lera, Francisco J.",
  editor = "Quinti{\'a}n, H{\'e}ctor and Corchado, Emilio and Troncoso Lora, Alicia and P{\'e}rez Garc{\'i}a, Hilde and Jove P{\'e}rez, Esteban and Calvo Rolle, Jos{\'e} Luis and Mart{\'i}nez de Pis{\'o}n, Francisco Javier and Garc{\'i}a Bringas, Pablo and Mart{\'i}nez {\'A}lvarez, Francisco and Herrero, {\'A}lvaro and Fosci, Paolo",
  title = "VIPER: Vision-Based System to Detect Potential Predators for Herding with Robots",
  booktitle = "Hybrid Artificial Intelligent Systems",
  year = "2025",
  publisher = "Springer Nature Switzerland",
  address = "Cham",
  pages = "214--223",
  isbn = "978-3-031-74186-9"
}
```




## Acknowledgment: SELF-AIR Project

Supporting Extensive Livestock Farming with the use of Autonomous Intelligent Robots 

<img src="https://raw.githubusercontent.com/shepherd-robot/.github/main/profile/robotics_wolf_minimal.png" alt= "SELF_AIR_logo" width="50%" height="50%">

Grant TED2021-132356B-I00 funded by MCIN/AEI/10.13039/501100011033 and by the “European Union NextGenerationEU/PRTR"

![SELF_AIR_EU eu_logo](https://raw.githubusercontent.com/shepherd-robot/.github/main/profile/micin-financiadoUEnextgeneration-prtr-aei.png)
