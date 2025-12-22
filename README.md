# Ai Data And Simulation Closed Loop for Intelligent Machines
This repo is constructed for collecting and categorizing papers about data construction for intelligent machines, like autonomous vehicle, embodied robots, etc.

# Techniques

## assert generation
 
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

**Hand-held Object Reconstruction from RGB Video with Dynamic Interaction**\
*Shijian Jiang, Qi Ye, Rengan Xie, Yuchi Huo, Xiang Li, Yang Zhou, Jiming Chen*\
*College of Control Science and Engineering, Zhejiang University; Key Lab of CS&AUS of Zhejiang Province; State Key Lab of CAD&CG, Zhejiang University; Zhejiang Lab; OPPO USResearch Center*\
CVPR 2025. [Website](https://east-j.github.io/dynhor/) | [Paper](https://arxiv.org/abs/2312.16425) | [Code](https://github.com/EAST-J/Dynhor)

**ArtVIP: Articulated Digital Assets of Visual Realism, Modular Interaction, and Physical Fidelity for Robot Learning**\
*Zhao Jin, Zhengping Che, Zhen Zhao, Kun Wu, Yuheng Zhang, Yinuo Zhao, Zehui Liu, Qiang Zhang, Xiaozhu Ju, Jing Tian, Yousong Xue, Jian Tang*\
*Beijing Innovation Center of Humanoid Robotics, Beijing Institute of Architectural Design*\
arxiv 2025. [Website](https://x-humanoid-artvip.github.io/) | [Paper](https://www.arxiv.org/abs/2506.04941) | [dataset](https://github.com/x-humanoid-artvip/x-humanoid-artvip.github.io) 

**PhysX: Physical-Grounded 3D Asset Generation**\
*Ziang Cao, Zhaoxi Chen, Liang Pan, Ziwei Liu*\
*Nanyang Technological University, Shanghai AI Lab*\
arxiv 2025. [Website](https://physx-3d.github.io/) | [Paper](https://arxiv.org/abs/2507.12465) | [Code](https://github.com/ziangcao0312/PhysX)

**SAM3D:3Dfy Anything in Images**\
*XingyuChen∗, Fu-JenChu∗, PierreGleize∗, KevinJLiang∗, AlexanderSax∗, HaoTang∗, WeiyaoWang∗, MichelleGuo, ThibautHardin, XiangLi◦, AohanLin, JiaweiLiu, ZiqiMa◦, AnushkaSagar, BowenSong◦, XiaodongWang, JianingYang◦, BowenZhang◦, PiotrDollár†, GeorgiaGkioxari†, Matt Feiszli†§, Jitendra Malik*\
*Meta Superintelligence Labs*\
arXiv 2025. [Website](https://ai.meta.com/sam3d/) | [Paper](https://ai.meta.com/research/publications/sam-3d-3dfy-anything-in-images/) |  [Code](https://github.com/facebookresearch/sam-3d-objects)

**SAM 3D Body: Robust Full-Body Human Mesh Recovery**\
*Xitong Yang*, Devansh Kukreja*, Don Pinkus*, Anushka Sagar, Taosha Fan, Jinhyung Park⚬, Soyong Shin⚬, Jinkun Cao, Jiawei Liu, Nicolas Ugrinovic, Matt Feiszli†, Jitendra Malik†, Piotr Dollar†, Kris Kitani†*\
*Meta Superintelligence Labs*\
arXiv 2025.  [Website](https://ai.meta.com/blog/sam-3d/) | [Paper](https://ai.meta.com/research/publications/sam-3d-body-robust-full-body-human-mesh-recovery/) | [Code](https://github.com/facebookresearch/sam-3d-body)

**DIPO: Dual-State Images Controlled Articulated Object Generation Powered by Diverse Data**
*Ruqi Wu, Xinjie Wang, Liu Liu, Chunle Guo, Jiaxiong Qiu, Chongyi Li, Lichao Huang, Zhizhong Su, Ming-Ming Cheng*
*VCIP, CS, Nankai University; NKIARI, Shenzhen Futian; Horizon Robotics*
arXiv 2025. [Website](https://rq-wu.github.io/projects/DIPO/) | [Paper](https://arxiv.org/abs/2505.20460) | [Code](https://github.com/BellmanTimeHut/DIPO)

**PhysX-Anything: Simulation-Ready Physical 3D Assets from Single Image**
*Ziang Cao, Xinyu Li, Songyang Zhang, Wenbing Huang, Zhiqi Li, Yanyu Xu, Jianan Li, Shuai Yi*
*SenseTime Research & Tsinghua University*
arXiv 2025. [Website](https://physx-anything.github.io/) | [Paper](https://arxiv.org/abs/2511.13648) | [Code](https://github.com/ziangcao0312/PhysX-Anything)



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

**LongSplat: Robust Unposed 3D Gaussian Splatting for Casual Long Videos**\
*Chin-Yang Lin, Cheng Sun, Fu-En Yang, Min-Hung Chen, Yen-Yu Lin, Yu-Lun Liu*\
*National Yang Ming Chiao Tung University， NVIDIA Research*\
ICCV2025. [Website](https://linjohnss.github.io/longsplat/) | [Paper](https://arxiv.org/abs/2508.14041) | [Code](https://github.com/NVlabs/LongSplat)



**4.real2sim**

**LiteReality: Graphics-Ready 3D Scene Reconstruction from RGB-D Scans**\
*Zhening Huang, Xiaoyang Wu, Fangcheng Zhong, Hengshuang Zhao, Matthias Nießner, Joan Lasenby*\
*University of Cambridge, The University of Hong Kong, Technical University of Munich*\
arxiv2025. [Website](https://litereality.github.io/) | [Paper](https://arxiv.org/abs/2507.02861) | [Code](https://github.com/LiteReality/LiteReality)

**SceneGen: Single-Image 3D Scene Generation in One Feedforward Pass**\
*Yanxu Meng, Haoning Wu, Ya Zhang, Weidi Xie*\
*School of Artificial Intelligence, Shanghai Jiao Tong University*\
arXiv202508. [Website](https://mengmouxu.github.io/SceneGen/) | [Paper](https://arxiv.org/abs/2508.15769) | [Code](https://github.com/Mengmouxu/SceneGen)

**WorldSplat: Gaussian-Centric Feed-Forward 4D Scene Generation for Autonomous Driving**\
*Ziyue Zhu, Zhanqian Wu, Zhenxin Zhu, Lijun Zhou, Haiyang Sun, Bing Wan, Kun Ma, Guang Chen, Hangjun Ye, Jin Xie, jian Yang*\
*Nankai University, Xiaomi EV, Nanjing University, Suzhou*
. [Website](https://wm-research.github.io/worldsplat/) | [Paper](https://www.arxiv.org/abs/2509.23402) | [Code](https://github.com/wm-research/worldsplat)


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

**Novel Demonstration Generation with Gaussian Splatting Enables Robust One-Shot Manipulation**\
*Sizhe Yang, Wenye Yu, Jia Zeng, Jun Lv, Kerui Ren, Cewu Lu, Dahua Lin, Jiangmiao Pang*\
*Shanghai AI Laboratory， The Chinese University of Hong Kong， Shanghai Jiao Tong University*\
RSS 2025. [Website](https://yangsizhe.github.io/robosplat/) | [Paper](https://arxiv.org/abs/2504.13175) | [Code](https://github.com/OpenRobotLab/robosplat)


**ReBot: Scaling Robot Learning with Real-to-Sim-to-Real Robotic Video Synthesis**\
*Yu Fang, Yue Yang, Xinghao Zhu, Kaiyuan Zheng, Gedas Bertasius, Daniel Szafir, Mingyu Ding*\
*Department of Computer Science, University of North Carolina,Robotics and AI Institute, Department of Electrical and Computer Engineering, University of Washington*\
arxiv2025. [Website](https://yuffish.github.io/rebot/) | [Paper](https://arxiv.org/abs/2503.14526) | [Code](https://github.com/yuffish/rebot)

**3.combination generalization**

**R3D2: Realistic 3D Asset Insertion via Diffusion for Autonomous Driving Simulation**\
*William Ljungbergh†, Bernardo Taveira†, Wenzhao Zheng, Adam Tonderski, Chensheng Peng, Fredrik Kahl, Christoffer Petersson, Michael Felsberg, Kurt Keutzer, Masayoshi Tomizuka, Wei Zhan*\
*Zenseact, Linköping University, Chalmers University, UC Berkeley*\
arxiv 2025. [Website](https://research.zenseact.com/publications/R3D2/) | [Paper](https://arxiv.org/abs/2506.07826)


**EmbodiedGen: Towards a Generative 3D World Engine for Embodied Intelligence**\
*Xinjie Wang, Liu Liu, Yu Cao, Ruiqi Wu, Wenkang Qin, Dehui Wang, Wei Sui, Zhizhong Su*\
*Horizon Robotics; GigaAI; 3D-Robotics; Shanghai Jiao Tong University; VCIP, CS, Nankai University*\
arxiv 2025. [Website](https://horizonrobotics.github.io/robot_lab/embodied_gen/index.html) | [Paper](https://arxiv.org/abs/2506.10600) | [Code](https://github.com/HorizonRobotics/EmbodiedGen)

**SplatSim: Zero-Shot Sim2Real Transfer of RGB Manipulation Policies Using Gaussian Splatting**\
*Mohammad Nomaan Qureshi, Sparsh Garg, Francisco Yandun, David Held, George Kantor, Abhisesh Silwal*\
*Carnegie Mellon University*\
ICRA 2025. [Website](https://splatsim.github.io/) | [Paper](https://arxiv.org/abs/2409.10161) | [Code](https://github.com/qureshinomaan/SplatSim)


**4.LLM agent**

**GenSim: A General Social Simulation Platform with Large Language Model based Agents**\
*Jiakai Tang, Heyang Gao, Xuchen Pan, Lei Wang, Haoran Tan, Dawei Gao, Yushuo Chen, Xu Chen, Yankai Lin, Yaliang Li, Bolin Ding, Jingren Zhou, Jun Wang, Ji-Rong Wen*\
*Renmin University of China, University College London, Alibaba Group*\
arXiv 2025. [Paper](https://arxiv.org/abs/2410.04360) | [Code](https://github.com/TangJiakai/GenSim)

**GenSim2: Scaling Robot Data Generation with Multi-modal and Reasoning LLMs**\
*Pu Hua, Minghuan Liu, Annabella Macaluso, Yunfeng Lin, Weinan Zhang, Huazhe Xu, Lirui Wang*\
*Tsinghua University, UCSD, Shanghai Jiao Tong University, MIT CSAIL*\
CoRL 2024. [Website](https://gensim2.github.io/) | [Paper](https://arxiv.org/abs/2410.03645) | [Code](https://github.com/GenSim2/gensim2)

**RoboTwin 2.0: A Scalable Data Generator and Benchmark with Strong Domain Randomization for Robust Bimanual Robotic Manipulation**\
*Tianxing Chen, Zanxin Chen, Baijun Chen, Zijian Cai, Yibin Liu, Qiwei Liang, Zixuan Li, Xianliang Lin, Yiheng Ge, Zhenyu Gu, Weiliang Deng, Yubin Guo, Tian Nian, Xuanbing Xie, Qiangyu Chen, Kailun Su, Tianling Xu, Guodong Liu, Mengkang Hu, Huan-ang Gao, Kaixuan Wang, Zhixuan Liang, Yusen Qin, Xiaokang Yang, Ping Luo, Yao Mu*\
*SJTU ScaleLab, HKU MMLab‡, Shanghai AI Lab, 4D-Robotics, SZU, THU, TeleAI, FDU, USTC, SUSTech, SYSU, CSU, NEU, HKU-SH ICRC, NJU, Lumina EAI*\
arxiv2025. [Website](https://robotwin-platform.github.io/) | [Paper](https://arxiv.org/abs/2506.18088) | [Code](https://github.com/robotwin-Platform/RoboTwin)


**Follow-Your-Instruction: A Comprehensive MLLM Agent for World Data Synthesis**\
*Kunyu Feng, Yue Ma, Xinhua Zhang, Boshi Liu, Yikuang Yuluo, Yinhan Zhang, Runtao Liu, Hongyu Liu, Zhiyuan Qin, Shanhui Mo, Qifeng Chen, Zeyu Wang*\
*HKUST(GZ), HKUST, Tsinghua Univerisity, Peking University, Chongqing University, Beijing Innovation Center of Humanoid Robotics*\
arxiv 2025.  [Paper](https://arxiv.org/abs/2508.05580) 


**5.small2large**

**Dex1B: Learning with 1B Demonstrations for Dexterous Manipulation**\
*Jianglong Ye, Keyi Wang, Chengjing Yuan, Ruihan Yang, Yiquan Li, Jiyue Zhu, Yuzhe Qin, Xueyan Zou, Xiaolong Wang*\
*UC San Diego*\
RSS 2025. [Website](https://jianglongye.com/dex1b/) | [Paper](https://www.arxiv.org/abs/2506.17198)

**6.HSI**

**ZeroHSI: Zero-Shot 4D Human-Scene Interaction by Video Generation**\
*Hongjie Li, Hong-Xing Yu, Jiaman Li, Jiajun Wu*\
*Stanford University*\
arxiv 2024. [Website](https://awfuact.github.io/zerohsi/) | [Paper](https://arxiv.org/abs/2412.18600)


**7.HOI**

**InterMimic: Towards Universal Whole-Body Control for Physics-Based Human-Object Interactions**\
*Sirui Xu, Hung Yu Ling, Yu-Xiong Wang, Liang-Yan Gui*\
*University of Illinois Urbana-Champaign， Electronic Arts*\
CVPR 2025. [Website](https://sirui-xu.github.io/InterMimic/) | [Paper](https://arxiv.org/abs/2502.20390) | [Code](https://github.com/Sirui-Xu/InterMimic)

**8.new view**

**ArbiViewGen: Controllable Arbitrary Viewpoint Camera Data Generation for Autonomous Driving via Stable Diffusion Models**\
*Tsinghua University;School of Science, Minzu University;CMU;The Hong Kong University of Science and Technology*\
*Yatong Lan, Jingfeng Chen, Yiru Wang, Lei He*\
arxiv 2025. [Paper](https://arxiv.org/pdf/2508.05236) 


**9.anyedit**

*WorldForge: Unlocking Emergent 3D/4D Generation in Video Diffusion Model via Training-Free Guidance*\
*Chenxi Song, Yanming Yang, Tong Zhao, Ruibo Li, Chi Zhang*\
*AGILab,SchoolofEngineering,WestlakeUniversity,Hangzhou,China; TheCollegeofComputingandDataScience,NanyangTechnologicalUniversity,Singapore*\
arxiv 2025. [Website](https://worldforge-agi.github.io/)| [Paper](https://arxiv.org/abs/2509.15130) | [Code](https://github.com/Westlake-AGI-Lab/WorldForge)


I**10.human2robot**

*X-Humanoid: Robotize Human Videos to Generate Humanoid Videos at Scale*\
*Pei Yang, Hai Ci, Yiren Song, Mike Zheng Shou*\
*National University of Singapore*\
arXiv 2025. [Paper](https://arxiv.org/abs/2512.04537) | [Code](https://github.com/showlab/X-Humanoid)

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


**BEV-VAE: Multi-view Image Generation with Spatial Consistency for Autonomous Driving**\
*Zeming Chen, Hang Zhao*\
*Shanghai Qi Zhi Institute, IIIS, Tsinghua University*\
arxiv 2025. [Paper](https://arxiv.org/abs/2507.00707) | [code](https://github.com/Czm369/bev-vae)

**Controllable 3D Outdoor Scene Generation via Scene Graphs**\
*Yuheng Liu, Xinke Li, Yuning Zhang, Lu Qi, Xin Li, Wenping Wang, Chongshou Li, Xueting Li, Ming-Hsuan Yang*\
*Texas A&M University, UC Merced, City University of Hong Kong, Southwest Jiaotong University, Insta360 Research, NVIDIA*\
ICCV 2025. [Website](https://yuheng.ink/project-page/control-3d-scene/) | [Paper](https://arxiv.org/abs/2503.07152) | [Code](https://github.com/yuhengliu02/control-3d-scene)

## simulation paradigm

### classic

**VR-Robo: A Real-to-Sim-to-Real Framework for Visual Robot Navigation and Locomotion**\
*Shaoting Zhu, Linzhan Mou, Derun Li, Baijun Ye, Runhan Huang, Hang Zhao*\
*Tsinghua University, Shanghai Qi Zhi Institute, Galaxea AI, Shanghai Jiao Tong University*\
RA-L 2025. [Website](https://vr-robo.github.io/) | [Paper](https://arxiv.org/abs/2502.01536) | [Code](https://github.com/zst1406217/VR-Robo)

**MuJoCo Playground**\
*Kevin Zakka, Baruch Tabanpour, Qiayuan Liao, Mustafa Haiderbhai, Samuel Holt, Jing Yuan Luo, Arthur Allshire, Erik Frey, Koushil Sreenath, Lueder A. Kahrs, Carmelo Sferrazza, Yuval Tassa, Pieter Abbeel*\
*UC Berkeley, Google DeepMind, University of Toronto, University of Cambridge*\
RSS 2025. [Website](https://playground.mujoco.org/) | [Paper](https://arxiv.org/abs/2502.08844) | [Code](https://github.com/google-deepmind/mujoco_playground)

**LabUtopia: High-Fidelity Simulation and Hierarchical Benchmark for Scientific Embodied Agents**\
*Rui Li, Zixuan Hu, Wenxi Qu, Jinouwen Zhang, Zhenfei Yin, Sha Zhang, Xuantuo Huang, Hanqing Wang, Tai Wang, Jiangmiao Pang, Wanli Ouyang, Lei Bai, Wangmeng Zuo, Ling-Yu Duan, Dongzhan Zhou, Shixiang Tang*\
*Shanghai AI Laboratory, Peking University, Oxford, The Chinese University of Hong Kong, Harbin Institute of Technology*\
arxiv 2025. [Paper](https://arxiv.org/abs/2505.22634)



### new

**AdaManip: Adaptive Articulated Object Manipulation Environments and Policy Learning**\
*Yuanfei Wang, Xiaojie Zhang, Ruihai Wu, Yu Li, Yan Shen, Mingdong Wu, Zhaofeng He, Yizhou Wang, Hao Dong*\
*Peking University, Beijing University of Posts and Telecommunications*\
ICLR 2025. [Website](https://adamanip.github.io/) | [Paper](https://arxiv.org/abs/2502.11124) | [Code](https://github.com/yuanfei-Wang/AdaManip)

**Habitat 3.0: A Co-Habitat for Humans, Avatars and Robots**\
*Xavier Puig, Eric Undersander, Andrew Szot, Mikael Dallaire Cote, Tsung-Yen Yang, Ruslan Partsey, Ruta Desai, Alexander William Clegg, Michal Hlavac, So Yeon Min, Vladimír Vondruš, Theophile Gervet, Vincent-Pierre Berges, John M. Turner, Oleksandr Maksymets, Zsolt Kira, Mrinal Kalakrishnan, Jitendra Malik, Devendra Singh Chaplot, Unnat Jain, Dhruv Batra, Akshara Rai, Roozbeh Mottaghi*\
*Fair, Meta*\
arxiv 2023. [Website](https://aihabitat.org/habitat3/) | [Paper](https://arxiv.org/abs/2310.13724) | [Code](https://github.com/facebookresearch/habitat-lab)

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



**ReSim: Reliable World Simulation for Autonomous Driving**\
*Jiazhi Yang, Kashyap Chitta, Shenyuan Gao, Long Chen, Yuqian Shao, Xiaosong Jia, Hongyang Li, Andreas Geiger, Xiangyu Yue, Li Chen*\
*The Chinese University of Hong Kong, The University of Hong Kong, OpenDriveLab at Shanghai AI Lab, NVIDIA Research, Xiaomi EV, Shanghai Jiao Tong University, University of Tübingen, Tübingen AI Center, HKUST*\
arxiv2025. [Website](https://opendrivelab.com/ReSim) | [Paper](https://arxiv.org/abs/2506.09981) | [Code](https://github.com/OpenDriveLab/ReSim)

**EmbodieDreamer: Advancing Real2Sim2Real Transfer for Policy Training via Embodied World Modeling**\
*Boyuan Wang, Xinpan Meng, Xiaofeng Wang, Zheng Zhu, Angen Ye, Yang Wang, Zhiqin Yang, Chaojun Ni, Guan Huang, Xingang Wang*\
*GigaAI, Institute of Automation, Chinese Academy of Sciences, Peking University*\
arxiv 2025. [Website](https://embodiedreamer.github.io/) | [Paper](https://github.com/GigaAI-research/EmbodieDreamer) | [Code](https://github.com/GigaAI-research/EmbodieDreamer)


**Genie Envisioner: A Unified World Foundation Platform for Robotic Manipulation**\
*Yue Liao, Pengfei Zhou, Siyuan Huang, Donglin Yang, Shengcong Chen, Yuxin Jiang, Yue Hu, Jingbin Cai, Si Liu, Jianlan Luo, Liliang Chen, Shuicheng Yan, Maoqing Yao, Guanghui Ren*\
*AgiBot Genie Team NUSLV-Lab BUAA*\
arxiv 2025. [Website](https://genie-envisioner.github.io/) | [Paper](https://arxiv.org/abs/2508.05635v1) | [Code](https://github.com/AgibotTech/Genie-Envisioner)


