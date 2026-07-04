# UrbanRadio3D

---
## 📡 Welcome to the RadioDiff Family

> Radio map construction via generative diffusion models — UNIC Lab, Xidian University

---

### 🔷 Base Backbone

**RadioDiff** — *The foundational diffusion model for radio map construction.*
&nbsp;&nbsp;📄 [Paper](https://ieeexplore.ieee.org/document/10764739) &nbsp;|&nbsp; 💻 [Code](https://github.com/UNIC-Lab/RadioDiff) &nbsp;|&nbsp; ![IEEE TCCN](https://img.shields.io/badge/IEEE-TCCN%202025-blue)

---

### 🔬 Physics-Informed Extensions

**RadioDiff-k²** — *PINN-enhanced diffusion guided by the Helmholtz equation.*
&nbsp;&nbsp;📄 [Paper](https://ieeexplore.ieee.org/document/11278649) &nbsp;|&nbsp; 💻 [Code](https://github.com/UNIC-Lab/RadioDiff-k) &nbsp;|&nbsp; ![IEEE JSAC](https://img.shields.io/badge/IEEE-JSAC%202026-blue)

**iRadioDiff** — *Indoor radio map construction with physical information integration.*
&nbsp;&nbsp;📄 [Paper](https://arxiv.org/abs/2511.20015) &nbsp;|&nbsp; 💻 [Code](https://github.com/UNIC-Lab/iRadioDiff) &nbsp;|&nbsp; ![IEEE ICC](https://img.shields.io/badge/IEEE-ICC%202026-blue) &nbsp;![Best Paper](https://img.shields.io/badge/🏆-Best%20Paper%20Award-orange)

---

### ⚡ Efficiency & Dynamics

**RadioDiff-Turbo** — *Efficiency-enhanced RadioDiff for accelerated inference.*
&nbsp;&nbsp;📄 [Paper](https://ieeexplore.ieee.org/abstract/document/11152929/) &nbsp;|&nbsp; ![INFOCOM Workshop](https://img.shields.io/badge/IEEE-INFOCOM%20Wksp%202025-lightgrey)

**RadioDiff-Flux** — *Adaptive reconstruction under dynamic environments and base station location changes.*
&nbsp;&nbsp;📄 [Paper](https://ieeexplore.ieee.org/document/11282987/) &nbsp;|&nbsp; ![IEEE TCCN](https://img.shields.io/badge/IEEE-TCCN%202026-blue)

---

### 🌐 Extended Scenarios

**RadioDiff-3D** — *3D radio map construction with the UrbanRadio3D dataset.*
&nbsp;&nbsp;📄 [Paper](https://ieeexplore.ieee.org/document/11083758) &nbsp;|&nbsp; 💻 [Code](https://github.com/UNIC-Lab/UrbanRadio3D) &nbsp;|&nbsp; ![IEEE TNSE](https://img.shields.io/badge/IEEE-TNSE%202025-blue)

**RadioDiff-FS** — *Few-shot learning for radio map construction with limited measurements.*
&nbsp;&nbsp;📄 [Paper](https://ieeexplore.ieee.org/document/11577136) &nbsp;|&nbsp; 💻 [Code](https://github.com/UNIC-Lab/RadioDiff-FS) &nbsp;|&nbsp; ![IEEE IoTJ](https://img.shields.io/badge/IEEE-IoTJ%202026-blue)

---

### 📶 Sparse Measurement & Localization

**RadioDiff-Inverse** — *Sparse measurement-based radio map recovery for ISAC applications.*
&nbsp;&nbsp;📄 [Paper](https://arxiv.org/abs/2504.14298) &nbsp;|&nbsp; 💻 [Code](https://github.com/UNIC-Lab/radiodiff-inverse) &nbsp;|&nbsp; ![IEEE TWC](https://img.shields.io/badge/IEEE-TWC%202026-blue)

**RadioDiff-Loc** — *Sparse measurement-based NLoS localization using diffusion models.*
&nbsp;&nbsp;📄 [Paper](https://www.arxiv.org/abs/2509.01875) &nbsp;|&nbsp; ![arXiv](https://img.shields.io/badge/arXiv-preprint-lightgrey)

---

> 📚 For a comprehensive categorized overview of radio map research, visit [**Awesome-Radio-Map-Categorized**](https://github.com/UNIC-Lab/Awesome-Radio-Map-Categorized).


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
