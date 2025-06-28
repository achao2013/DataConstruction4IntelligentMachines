# DataConstruction4IntelligentMachines
This repo is constructed for collecting and categorizing papers about data construction for intelligent machines, like autonomous vehicle, embodied robots, etc.

# Techniques

## assert construction
 
### object assert 
**ArtGS: Building Interactable Replicas of Complex Articulated Objects via Gaussian Splatting**\
*Yu Liu, Baoxiong Jia, Ruijie Lu, Junfeng Ni, Song-Chun Zhu, Siyuan Huang*\
*Tsinghua University; National Key Lab of General AI, BIGAI; Peking University*\
ICLR 2025. [Website](https://articulate-gs.github.io/) | [Paper](https://arxiv.org/abs/2502.19459) | [Data](https://huggingface.co/datasets/YuLiu/ArtGS-Dataset) | [Code](https://github.com/YuLiu-LY/ArtGS/tree/main) 

**Object-Aware Gaussian Splatting for Robotic Manipulation**\
*Yulong Li, Deepak Pathak*\
*Carnegie Mellon University*\
ICRA 2024 Workshop. [Website](https://object-aware-gaussian.github.io/) | [Paper](https://openreview.net/forum?id=gdRI43hDgo)


**PartCrafter: Structured 3D Mesh Generation via Compositional Latent Diffusion Transformers**\
*Yuchen Lin, Chenguo Lin, Panwang Pan, Honglei Yan, Yiqiang Feng, Yadong Mu, Katerina Fragkiadaki*\
*Peking University, ByteDance, Carnegie Mellon University*\
arxiv 2025. [Website](https://wgsxm.github.io/projects/partcrafter/) | [Paper](https://arxiv.org/abs/2506.05573) | [Code](https://github.com/wgsxm/PartCrafter)


### static scene assert

**1.synthesis**

**Scenethesis: A Language and Vision Agentic Framework for 3D Scene Generation**\
*Lu Ling, Chen-Hsuan Lin, Tsung-Yi Lin, Yifan Ding, Yu Zeng, Yichen Sheng, Yunhao Ge, Ming-Yu Liu, Aniket Bera* ,Zhaoshuo Li*\
*NVIDIA Research, Purdue University*\
arXiv preprint 2025. [Website](https://research.nvidia.com/labs/dir/scenethesis/) | [Paper](https://arxiv.org/abs/2505.02836)

**SceneLCM: End-to-End Layout-Guided Interactive Indoor Scene Generation with Latent Consistency Model**\
*Yangkai Lin, Jiabao Lei, Kui Jia*\
*School of Electronic and Information Engineering South China University of Technology; The Chinese University of Hong Kong, Shenzhen; School of Data Science The Chinese University of Hong Kong, Shenzhen*\
arxiv 2025. [Website](https://scutyklin.github.io/SceneLCM/) | [Paper](https://arxiv.org/abs/2506.07091) 

**2.one2many**

 **ACDC: Automated Creation of Digital Cousins for Robust Policy Learning**\
 *Tianyuan Dai, Josiah Wong, Yunfan Jiang, Chen Wang, Cem Gokmen, Ruohan Zhang, Jiajun Wu, Li Fei-Fei*\
 *Stanford University*\
 CoRL 2024. [Website](https://digital-cousins.github.io/) | [Paper](https://arxiv.org/abs/2410.07408) | [Code](https://github.com/cremebrule/digital-cousins)
 
**3.recon**

**WildGS-SLAM: Monocular Gaussian Splatting SLAM in Dynamic Environments**\
*Jianhao Zheng, Zihan Zhu, Valentin Bieri, Marc Pollefeys, Songyou Peng, Iro Armeni*\
*Stanford University; ETH Zürich; Microsoft*\
CVPR 2025. [Website](https://wildgs-slam.github.io/) | [Paper](https://arxiv.org/abs/2504.03886) | [Code](https://github.com/GradientSpaces/WildGS-SLAM)

### dynamic scene assert

**1.recon**

**2.one2many**
  
**DexMimicGen: Automated Data Generation for Bimanual Dexterous Manipulation via Imitation Learning**\
*Zhenyu Jiang, Yuqi Xie, Kevin Lin, Zhenjia Xu, Weikang Wan, Ajay Mandlekar†, Linxi “Jim” Fan, Yuke Zhu*\
*NVIDIA Research, UT Austin, UC San Diego*\
ICRA 2025. [Website](https://dexmimicgen.github.io/) |  [Paper](https://arxiv.org/abs/2410.24185) | [Code](https://github.com/NVlabs/dexmimicgen/)

**DemoGen: Synthetic Demonstration Generation for Data-Efficient Visuomotor Policy Learning**\
*Zhengrong Xue, Shuying Deng, Zhenyang Chen, Yixuan Wang, Zhecheng Yuan, Huazhe Xu*\
*Tsinghua University, Shanghai Qi Zhi Institute, Shanghai AI Lab*\
RSS 2025. [Website](https://demo-generation.github.io) | [Paper](https://arxiv.org/abs/2502.16932) | [Code](https://github.com/TEA-Lab/DemoGen)

**3.combination generalization**

**R3D2: Realistic 3D Asset Insertion via Diffusion for Autonomous Driving Simulation**\
*William Ljungbergh†, Bernardo Taveira†, Wenzhao Zheng, Adam Tonderski, Chensheng Peng, Fredrik Kahl, Christoffer Petersson, Michael Felsberg, Kurt Keutzer, Masayoshi Tomizuka, Wei Zhan*\
*Zenseact, Linköping University, Chalmers University, UC Berkeley*\
arxiv 2025. [Website](https://research.zenseact.com/publications/R3D2/) | [Paper](https://arxiv.org/abs/2506.07826)


**EmbodiedGen: Towards a Generative 3D World Engine for Embodied Intelligence**\
*Xinjie Wang, Liu Liu, Yu Cao, Ruiqi Wu, Wenkang Qin, Dehui Wang, Wei Sui, Zhizhong Su*\
*Horizon Robotics; GigaAI; 3D-Robotics; Shanghai Jiao Tong University; VCIP, CS, Nankai University*\
arxiv 2025. [Website](https://horizonrobotics.github.io/robot_lab/embodied_gen/index.html) | [Paper](https://arxiv.org/abs/2506.10600) | [Code](https://github.com/HorizonRobotics/EmbodiedGen)



**4.LLM agent**

**GenSim: A General Social Simulation Platform with Large Language Model based Agents**\
*Jiakai Tang, Heyang Gao, Xuchen Pan, Lei Wang, Haoran Tan, Dawei Gao, Yushuo Chen, Xu Chen, Yankai Lin, Yaliang Li, Bolin Ding, Jingren Zhou, Jun Wang, Ji-Rong Wen*\
*Renmin University of China, University College London, Alibaba Group*\
arXiv 2025. [Paper](https://arxiv.org/abs/2410.04360) | [Code](https://github.com/TangJiakai/GenSim)


**RoboTwin 2.0: A Scalable Data Generator and Benchmark with Strong Domain Randomization for Robust Bimanual Robotic Manipulation**\
*Tianxing Chen, Zanxin Chen, Baijun Chen, Zijian Cai, Yibin Liu, Qiwei Liang, Zixuan Li, Xianliang Lin, Yiheng Ge, Zhenyu Gu, Weiliang Deng, Yubin Guo, Tian Nian, Xuanbing Xie, Qiangyu Chen, Kailun Su, Tianling Xu, Guodong Liu, Mengkang Hu, Huan-ang Gao, Kaixuan Wang, Zhixuan Liang, Yusen Qin, Xiaokang Yang, Ping Luo, Yao Mu*\
*SJTU ScaleLab, HKU MMLab‡, Shanghai AI Lab, 4D-Robotics, SZU, THU, TeleAI, FDU, USTC, SUSTech, SYSU, CSU, NEU, HKU-SH ICRC, NJU, Lumina EAI*\
arxiv2025. [Website](https://robotwin-platform.github.io/) | [Paper](https://arxiv.org/abs/2506.18088) | [Code](https://github.com/robotwin-Platform/RoboTwin)

**5.input2gt**

**Dex1B: Learning with 1B Demonstrations for Dexterous Manipulation**\
*Jianglong Ye, Keyi Wang, Chengjing Yuan, Ruihan Yang, Yiquan Li, Jiyue Zhu, Yuzhe Qin, Xueyan Zou, Xiaolong Wang*\
*UC San Diego*\
RSS 2025. [Website](https://jianglongye.com/dex1b/) | [Paper](https://www.arxiv.org/abs/2506.17198)

### world model

**Cosmos-Drive-Dreams: Scalable Synthetic Driving Data Generation with World Foundation Models**\
*Xuanchi Ren, Yifan Lu, Tianshi Cao, Ruiyuan Gao, Shengyu Huang, Amirmojtaba Sabour, Tianchang Shen, Tobias Pfaff, Jay Zhangjie Wu, Runjian Chen, Seung Wook Kim, Jun Gao, Laura Leal-Taixe, Mike Chen, Sanja Fidler, Huan Ling*\
*NVIDIA*\
arxiv 2025. [Webiste](https://research.nvidia.com/labs/toronto-ai/cosmos_drive_dreams/) | [Paper](https://arxiv.org/abs/2506.09042) | [Code](https://github.com/nv-tlabs/Cosmos-Drive-Dreams)

**DreamGen: Unlocking Generalization in Robot Learning through Video World Models**\
*Joel Jang, Seonghyeon Ye, Zongyu Lin, Jiannan Xiang, Johan Bjorck, Yu Fang, Fengyuan Hu, Spencer Huang, Kaushil Kundalia, Yen-Chen Lin, Loic Magne, Ajay Mandlekar, Avnish Narayan, You Liang Tan, Guanzhi Wang, Jing Wang, Qi Wang, Yinzhen Xu, Xiaohui Zeng, Kaiyuan Zheng, Ruijie Zheng, Ming-Yu Liu, Luke Zettlemoyer, Dieter Fox, Jan Kautz, Scott Reed, Yuke Zhu, Linxi Fan*\
*NVIDIA, University of Washington, KAIST, UCLA, UCSD, CalTech, NTU, University of Maryland, UT Austin*\
arxiv 2025. [Website](https://research.nvidia.com/labs/gear/dreamgen/) | [Paper](https://arxiv.org/abs/2505.12705) | [Code](https://github.com/NVIDIA/GR00T-Dreams)


### condition genaration

**𝒳-Scene: Large-Scale Driving Scene Generation with High Fidelity and Flexible Controllability**\
*Yu Yang, Alan Liang, Jianbiao Mei, Yukai Ma, Yong Liu, Gim Hee Lee*\
*Zhejiang University, National University of Singapore*\
arxiv 2025. [Website](https://x-scene.github.io/) | [Paper](https://arxiv.org/abs/2506.13558) | [Code](https://github.com/yuyang-cloud/X-Scene)



## simulation paradigm

**Pseudo-Simulation for Autonomous Driving**\
*Wei Cao, Marcel Hallgarten, Tianyu Li, Daniel Dauner, Xunjiang Gu, Caojun Wang, Yakov Miron, Marco Aiello, Hongyang Li, Igor Gilitschenski, Boris Ivanovic, Marco Pavone, Andreas Geiger, Kashyap Chitta*\
*University of Tübingen, Tübingen AI Center, NVIDIA Research, Robert Bosch GmbH, OpenDriveLab at Shanghai Innovation Institute, University of Stuttgart, University of Toronto, Vector Institute, Stanford University*\
ArXiv 2025. | [Paper](https://arxiv.org/abs/2506.04218) | [Code](https://github.com/autonomousvision/navsim)

**DriveArena: A Closed-loop Generative Simulation Platform for Autonomous Driving**\
*Xuemeng Yang, Licheng Wen1, Yukai Ma, Jianbiao Mei, Xin Li,Tiantian Wei, Wenjie Lei, Daocheng Fu, Pinlong Cai, Min Dou, Botian Shi, Liang He, Yong Liu, Yu Qiao*\
*Shanghai AI Laboratory, Zhejiang University, Shanghai Jiao Tong University, Technical University of Munich, East China Normal University*\
arXiv 2025. [Website](https://pjlab-adg.github.io/DriveArena/) | [Paper](https://arxiv.org/abs/2408.00415) | [Code](https://github.com/PJLab-ADG/DriveArena)

**RoboGen: Towards Unleashing Infinite Data for Automated Robot Learning via Generative Simulation**\
*Yufei Wang, Zhou Xian, Feng Chen, Tsun-Hsuan Wang, Yian Wang, Katerina Fragkiadaki, Zackory Erickson, David Held, Chuang Gan*\
*CMU, Tsinghua IIIS, MIT CSAIL, UMass Amherst, MIT-IBM AI Lab*\
ICML 2024. [Website](https://robogen-ai.github.io/) | [Paper](https://arxiv.org/abs/2311.01455) | [Code](https://github.com/Genesis-Embodied-AI/RoboGen)

**RoboGSim: A Real2Sim2Real Robotic Gaussian Splatting Simulator**\
*Xinhai Li, Jialin Li, Ziheng Zhang, Rui Zhang, Fan Jia, Tiancai Wang, Haoqiang Fan, Kuo-Kun Tseng, Ruiping Wang*\
*Harbin Institute of Technology, Shenzhen; Institute of Computing Technology, Chinese Academy of Sciences; MEGVII Technology; Zhejiang University*\
arXiv 2025. [Website](https://robogsim.github.io/) | [Paper](https://arxiv.org/abs/2411.11839) 
