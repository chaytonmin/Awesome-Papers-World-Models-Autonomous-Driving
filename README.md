<p align="center">
<img src="/docs/world_model_ad.png" width="30%"/>
</p>

#### World Models are adept at representing an agent's spatio-temporal knowledge about its environment through the prediction of future changes. There are two main types of world models in autonomous driving aimed at reducing driving uncertainty, i.e., World Model as Neural Driving Simulator and World Model for End-to-end Driving. In the real environment, methods like GAIA-1 and Copilot4D involve utilizing generative models to construct neural simulators that produce 2D or 3D future scenes to enhance predictive capabilities. In the simulation environment, methods such as MILE and TrafficBots are based on reinforcement learning, enhancing their capacity for decision-making and future prediction, thereby paving the way to end-to-end autonomous driving.

### Neural Driving Simulator based on World Models
#### 2D Scene Generation
+ (2023 Arxiv) Gaia-1: A generative world model for autonomous driving [[Paper](https://arxiv.org/abs/2309.17080)][[Blog](https://wayve.ai/thinking/scaling-gaia-1/)] (Wayve)
+ (2023 CVPR 2023 workshop) [[Video](https://www.youtube.com/watch?v=6x-Xb_uT7ts)] (Tesla)
+ (2023 Arxiv) DriveDreamer: Towards Real-world-driven World Models for Autonomous Driving [[Paper](https://drivedreamer.github.io/)][[Code](https://github.com/JeffWang987/DriveDreamer)] (GigaAI)
+ (2023 Arxiv) ADriver-I: A General World Model for Autonomous Driving [[Paper](https://arxiv.org/abs/2311.13549)] (MEGVII)
+ (2023 Arxiv) DrivingDiffusion: Layout-Guided multi-view driving scene video generation with latent diffusion model [[Paper](https://arxiv.org/abs/2310.07771)] (Baidu)
+ (2023 Arxiv) Panacea: Panoramic and Controllable Video Generation for Autonomous Driving [[Paper](https://panacea-ad.github.io/)][[Code](https://github.com/wenyuqing/panacea)] (MEGVII)
+ (2024 CVPR) Drive-WM: Driving into the Future: Multiview Visual Forecasting and Planning with World Model for Autonomous Driving [[Paper](https://drive-wm.github.io/)][[Code](https://github.com/BraveGroup/Drive-WM)] (CASIA)
+ (2023 Arxiv) WoVoGen: World Volume-aware Diffusion for Controllable Multi-camera Driving Scene Generation [[Paper](https://arxiv.org/abs/2312.02934)] (Fudan)
+ (2024 Arxiv) DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video Generation [[Paper](https://drivedreamer2.github.io/)][[Code](https://github.com/f1yfisher/DriveDreamer2)] (GigaAI)
+ (2024 CVPR) GenAD: Generalized Predictive Model for Autonomous Driving [[Paper](https://arxiv.org/abs/2403.09630)][[Code](https://github.com/OpenDriveLab/DriveAGI?tab=readme-ov-file)] (Shanghai AI Lab)
+ (2024 Arxiv) SubjectDrive: Scaling Generative Data in Autonomous Driving via Subject Control [[Paper](https://subjectdrive.github.io/)] (MEGVII)

#### 3D Scene Generation
+ (2024 ICLR) Copilot4D:Learning unsupervised world models for autonomous driving via discrete diffusion [[Paper](https://arxiv.org/abs/2311.01017)] (Waabi)
+ (2023 Arxiv) OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving [[Paper](https://arxiv.org/abs/2311.16038)][[Code](https://github.com/wzzheng/OccWorld)] (THU)
+ (2023 Arxiv) MUVO: A Multimodal Generative World Model for Autonomous Driving with Geometric Representations [[Paper](https://arxiv.org/abs/2311.11762)] (KIT)
+ (2024 Arxiv) LidarDM: Generative LiDAR Simulation in a Generated World [[Paper](https://www.zyrianov.org/lidardm/)][[Code](https://github.com/vzyrianov/lidardm)] (MIT)
  
#### Pre-training for Autonomous Driving
+ (2023 Arxiv) UniWorld: Autonomous Driving Pre-training via World Models [[Paper](https://arxiv.org/abs/2308.07234)] (PKU) 
+ (2024 CVPR) ViDAR: Visual Point Cloud Forecasting enables Scalable Autonomous Driving [[Paper](https://arxiv.org/abs/2312.17655)][[Code](https://github.com/OpenDriveLab/ViDAR)] (Shanghai AI Lab)
+ (2024 CVPR) DriveWorld: 4D Pre-trained Scene Understanding via World Models for Autonomous Driving [[Paper](XXX)] (PKU)
  
### End-to-end Driving based on World Models
+ (2022 NeurIPS) Iso-Dream: Isolating and Leveraging Noncontrollable Visual Dynamics in World Models [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/9316769afaaeeaad42a9e3633b14e801-Abstract-Conference.html)] (SJTU)
+ (2022 NeurIPS) MILE: Model-Based Imitation Learning for Urban Driving [[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/827cb489449ea216e4a257c47e407d18-Abstract-Conference.html)][[Code](https://github.com/wayveai/mile)] (Wayve)
+ (2022 NeurIPS Deep RL Workshop) SEM2: Enhance Sample Efficiency and Robustness of End-to-end Urban Autonomous Driving via Semantic Masked World Model [[Paper](https://arxiv.org/abs/2210.04017)] (HIT & THU)
+ (2023 ICRA) TrafficBots: Towards World Models for Autonomous Driving Simulation and Motion Prediction [[Paper](https://ieeexplore.ieee.org/abstract/document/10161243)] (ETH Zurich)
+ (2024 Arxiv) Think2Drive: Efficient Reinforcement Learning by Thinking in Latent World Model for Quasi-Realistic Autonomous Driving (in CARLA-v2) [[Paper](https://arxiv.org/abs/2402.16720)] (SJTU)

### Others
+ (1989) Using Occupancy Grids for Mobile Robot Perception and Navigation [[paper](http://www.sci.brooklyn.cuny.edu/~parsons/courses/3415-fall-2011/papers/elfes.pdf)]

## Contact
If you find our survey is useful in your research or applications, please consider giving us a star 🌟 and citing it by the following BibTeX entry.

```
@article{generalworldmodelsurvey,
  title={Is Sora a World Simulator? A Comprehensive Survey on General World Models and Beyond},
  author={Zheng Zhu and Xiaofeng Wang and Wangbo Zhao and Chen Min and Nianchen Deng and Min Dou and Yuqi Wang and Botian Shi and Kai Wang and Chi Zhang and Yang You and Zhaoxiang Zhang and Dawei Zhao and Liang Xiao and Jian Zhao and Jiwen Lu and Guan Huang}, 
  journal={arXiv preprint arXiv:TODO},
  year={2024}
}
```
