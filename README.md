# LuxDrive-Dataset

Welcome to the Luxembourg driving dataset (LuxDrive-Dataset) repository, a fundamental resource designed to support research on perception in autonomous driving environments. This dataset serves as a crucial tool for validating and benchmarking innovative research concepts in autonomous driving, utilizing vehicle-to-everything (V2X) communication. It can be utilized for various purposes spanning computer vision to computer networking.

## Publication
For a comprehensive understanding of the dataset and its applications, we recommend referring to our research paper " **Cooperative Perception using V2X Communications: An Experimental Study**":
- [Read the Full Paper (PDF)]

### Citation:
If you use this dataset in your research, please use the following citation:

```text
@article{hawlader2024,
  title={Cooperative Perception using V2X Communications: An Experimental Study},
  author={Hawlader, Faisal and Robinet, Fran{\c{c}}ois and Frank, Rapha{\"e}l},
  journal={---},
  volume={--},
  pages={--},
  year={},
  publisher={---}
}
```
## Dataset Overview
- Real-world driving dataset captured using a front-facing camera sensor mounted on the rooftop of an autonomous vehicle developed by 360lab, a research group at the University of Luxembourg. The dataset was created while driving around JFK Avenue in Kirchberg, Luxembourg City. 
- The dataset contains 2k camera frames and ground truth bounding box annotations for three classes:
  - **vehicles (bus, car), pedestrians, and traffic lights**
- Split into three subsets:
    - Training (1k images)
    - Validation (0.5k images)
    - and Testing (0.5k images)
```text
LuxDrive Dataset (format):
    - Train
        - images
          - *.bmp
        - labels
          - *.txt
    - Test
        - images
          - *.bmp
        - labels
          - *.txt
    - Validation
        - images
          - *.bmp
        - labels
          - *.txt
```
### Example Images
<img height="190" width="320" alt="image" src="https://github.com/FaisalHawlader/LuxDrive-Dataset/assets/43897254/1199af98-36db-4ccb-b729-e7671a6c1bf4)">


## Downloads
To access the complete dataset, please use the following link:
- [Download the Dataset (15 GB)].

If you encounter any issues or have questions, please feel free to get in touch by sending an email to faisal.hawlader@uni.lu. We'll be happy to assist you!
## Acknowledments
This work is supported by the [Fonds National de la Recherche of Luxembourg (FNR)](https://www.fnr.lu/), under AFR grant agreement No 17020780 and project acronym ACDC.
