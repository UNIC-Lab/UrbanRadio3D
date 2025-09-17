# UrbanRadio3D

---
### Welcome to the RadioDiff family

RadioDiff: Base BackBone: [RadioDiff](https://ieeexplore.ieee.org/document/10764739) [GitHub](https://github.com/UNIC-Lab/RadioDiff)

RadioDiff-k^2: PINN Enhanced with Helmholtz Equation: [RadioDiff-$k^2$](https://arxiv.org/pdf/2504.15623)

iRadioDiff: Indoor RM Construction with Physical Information [GitHub](https://github.com/UNIC-Lab/iRadioDiff)

RadioDiff-3D: 3D RM with DataSet: [RadioDiff-3D](https://ieeexplore.ieee.org/document/11083758) [GitHub](https://github.com/UNIC-Lab/UrbanRadio3D)

RadioDiff-Inverse: Sparse Measurement for RM ISAC [RadioDiff-Inverse](https://arxiv.org/abs/2504.14298)

---

This is the demo of the dataset for UrbanRadio3D, which is accepted by [IEEE TNSE](https://ieeexplore.ieee.org/document/11083758).

If you have any questions, please contact me at xcwang_1@stu.xidian.edu.cn
# Citation
~~~
@ARTICLE{11083758,
  author={Wang, Xiucheng and Zhang, Qiming and Cheng, Nan and Chen, Junting and Zhang, Zezhong and Li, Zan and Cui, Shuguang and Shen, Xuemin},
  journal={IEEE Transactions on Network Science and Engineering}, 
  title={RadioDiff-3D: A 3D× 3D Radio Map Dataset and Generative Diffusion Based Benchmark for 6G Environment-Aware Communication}, 
  year={2025},
  volume={},
  number={},
  pages={1-18},
  doi={10.1109/TNSE.2025.3590545}}
~~~


# Dataset Description
All datasets used in this project can be accessed via the following cloud storage links:

- Baidu Cloud Drive: [[link](https://pan.baidu.com/s/1TaHjVrQuIxm_7CcWWVuXcg?pwd=exz2)]  
  Extraction Code: exz2

- OneDrive: [[link](https://1drv.ms/f/s!AitEjoFKe4hDjnCI0Jbbt5rPpyiI?e=FFIztH)]  
  Extraction Code: RadioDiff-3D

## Dataset Splits

We have provided recommended splits of the dataset into training and testing sets to facilitate standardized model training and evaluation.

## File Description

- **Building_Infomation.zip**  
  This archive contains information on building heights and their spatial distribution, which serves as critical geometric features for wireless communication environment modeling.

- **Naming Convention for RM Maps**  
  Each RM (Radio Map) image file follows the naming format:  
  `xxx_Xxxx_Yxx.png`  
  Where:  
  - `xxx` indicates the building distribution map index  
  - `Xxxx` indicates the X-coordinate of the base station  
  - `Yxx` indicates the Y-coordinate of the base station  

This naming scheme allows precise identification of the RM map's corresponding building environment and base station location, facilitating further analysis and experimental reproducibility.

---

For any questions regarding dataset usage or structure, please feel free to contact the project team for further assistance.
