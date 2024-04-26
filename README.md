<p align="center">
<img src="/docs/world_model.png" width="30%"/>
</p>

#### World Models are adept at representing an agent's spatio-temporal knowledge about its environment through the prediction of future changes. There are two main types of world models in autonomous driving aimed at reducing driving uncertainty, i.e., World Model as Neural Driving Simulator and World Model for End-to-end Driving. In the real environment, methods like GAIA-1 and Copilot4D involve utilizing generative models to construct neural simulators that produce 2D or 3D future scenes to enhance predictive capabilities. In the simulation environment, methods such as MILE and TrafficBots are based on reinforcement learning, enhancing their capacity for decision-making and future prediction, thereby paving the way to end-to-end autonomous driving.

### Neural Driving Simulator
#### 2D Scene Generation
+ (2023 Arxiv) (Wayve) Gaia-1: A generative world model for autonomous driving [[Paper](https://arxiv.org/abs/2309.17080)][[Blog](https://wayve.ai/thinking/scaling-gaia-1/)]
+ (2023 CVPR 2023 workshop) (Tesla) [[Video](https://www.youtube.com/watch?v=6x-Xb_uT7ts)]
+ (2023 Arxiv) (GigaAI) DriveDreamer: Towards Real-world-driven World Models for Autonomous Driving [[Paper](https://drivedreamer.github.io/)][[Code](https://github.com/JeffWang987/DriveDreamer)]
+ (2023 Arxiv) (MEGVII) ADriver-I: A General World Model for Autonomous Driving [[Paper](https://arxiv.org/abs/2311.13549)]
+ (2023 Arxiv) (Baidu) DrivingDiffusion: Layout-Guided multi-view driving scene video generation with latent diffusion model [[Paper](https://arxiv.org/abs/2310.07771)]
+ (2023 Arxiv) (MEGVII) Panacea: Panoramic and Controllable Video Generation for Autonomous Driving [[Paper](https://panacea-ad.github.io/)][[Code](https://github.com/wenyuqing/panacea)]
+ (2024 CVPR) (CASIA) Drive-WM: Driving into the Future: Multiview Visual Forecasting and Planning with World Model for Autonomous Driving [[Paper](https://drive-wm.github.io/)][[Code](https://github.com/BraveGroup/Drive-WM)]
+ (2023 Arxiv) (Fudan) WoVoGen: World Volume-aware Diffusion for Controllable Multi-camera Driving Scene Generation [[Paper](https://arxiv.org/abs/2312.02934)]
+ (2024 Arxiv) (GigaAI) DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video Generation [[Paper](https://drivedreamer2.github.io/)][[Code](https://github.com/f1yfisher/DriveDreamer2)]
+ (2024 CVPR) (Shanghai AI Lab) GenAD: Generalized Predictive Model for Autonomous Driving [[Paper](https://arxiv.org/abs/2403.09630)][[Code](https://github.com/OpenDriveLab/DriveAGI?tab=readme-ov-file)]
+ (2024 Arxiv) (MEGVII) SubjectDrive: Scaling Generative Data in Autonomous Driving via Subject Control [[Paper](https://subjectdrive.github.io/)]

#### 3D Scene Generation
+ (2023) Copilot4D
+ (2023) OccWorld
+ (2023) MUVO
+ (2024) LidarDM
+ (2023 arxiv) (PKU) UniWorld
+ (2023 CVPR) (Shanghai AI Lab) ViDAR
+ (2024 CVPR) (PKU) DriveWorld
  
### End-to-end Driving
+ Contrastive Learning of Structured World Models [[paper](https://arxiv.org/abs/1911.12247)]
+ Tesla CVPR 2023 workshop [[Video](https://www.youtube.com/watch?v=6x-Xb_uT7ts)]
+ Wayve GAIA-1 [[blog](https://wayve.ai/thinking/introducing-gaia1/)]

### Others
+ (1989) Using Occupancy Grids for Mobile Robot Perception and Navigation [[paper](http://www.sci.brooklyn.cuny.edu/~parsons/courses/3415-fall-2011/papers/elfes.pdf)]
