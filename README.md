# UrbanRadio3D

---
### Welcome to the RadioDiff family

Base BackBone, Paper Link: [RadioDiff](https://ieeexplore.ieee.org/document/10764739), Code Link: [GitHub](https://github.com/UNIC-Lab/RadioDiff)

PINN Enhanced with Helmholtz Equation, Paper Link: [RadioDiff-$k^2$](https://ieeexplore.ieee.org/document/11278649), Code Link: [GitHub](https://github.com/UNIC-Lab/RadioDiff-k)

Efficiency Enhanced RadioDiff, Paper Link: [RadioDiff-Turbo](https://ieeexplore.ieee.org/abstract/document/11152929/)

Indoor RM Construction with Physical Information, Paper Link: [iRadioDiff](https://arxiv.org/abs/2511.20015), Code Link: [GitHub](https://github.com/UNIC-Lab/iRadioDiff)

3D RM with DataSet, Paper Link: [RadioDiff-3D](https://ieeexplore.ieee.org/document/11083758), Code Link: [GitHub](https://github.com/UNIC-Lab/UrbanRadio3D)

Sparse Measurement for RM ISAC, Paper Link: [RadioDiff-Inverse](https://arxiv.org/abs/2504.14298)

Sparse Measurement for NLoS Localization, Paper Link: [RadioDiff-Loc](https://www.arxiv.org/abs/2509.01875)

For more RM information, please visit the repo of [Awesome-Radio-Map-Categorized](https://github.com/UNIC-Lab/Awesome-Radio-Map-Categorized)

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

- Baidu Cloud Drive: [[link](https://pan.baidu.com/s/1nOyjVR3QHyGxzHzBWfbz6Q)]  
  Extraction Code is required.

- OneDrive: [[link](https://1drv.ms/f/c/43887b4a818e442b/EitEjoFKe4gggENwBwAAAAABbruOTF4HjJuAMgfCVmN-4A?e=M6CMQp)]  
  Extraction Code is required.

- For the Extraction Code, please click [[link](https://www.wjx.cn/vm/YDv1kEG.aspx)]

**The extraction code is located at the top of the redirect page after you complete the questionnaire. If you cannot find it, you may contact us via email at xcwang_1@stu.xidian.edu.cn.**

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
