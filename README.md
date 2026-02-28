# Awesome-VLA-UAVs
A list of research papers and other related resources on Vision-Language-Action/Navigation (VLA/VLN) models for UAVs.

Contributions are welcome! 

## 2026

- APEX: A Decoupled Memory-based Explorer for Asynchronous Aerial Object Goal Navigation (**CVPR 2026**)[[paper](https://arxiv.org/abs/2602.00551)][[code](https://github.com/4amGodvzx/apex/)]
(Note: **Dual system; History info**)

- History-Enhanced Two-Stage Transformer for Aerial Vision-and-Language Navigation (**AAAI 2026**)[[paper](https://arxiv.org/pdf/2512.14222)][[code](https://github.com/crotonyl/HETT)]
(Note: **Two-stage:先看大概方位，再找具体细节；历史网格地图**)

- IndoorUAV: Benchmarking Vision-Language UAV Navigation in Continuous Indoor Environments (**AAAI 2026**)[[paper](https://arxiv.org/abs/2512.19024)][[code](https://www.modelscope.cn/datasets/valyentine/Indoor_UAV)]
(Note: **Datasets: IndoorUAV-VLN（长时导航任务）和IndoorUAV-VLA（短时规划任务）；IndoorUAV-Agent: 先利用 GPT-4o 对原始指令进行分段，再利用基于π0架构的VLA进行飞行控制；再进行视觉反馈以辅助下一轮推理**)

- AutoFly: Vision-Language-Action Model for UAV Autonomous Navigation in the Wild (**ICLR 2026**)[[paper](https://arxiv.org/pdf/2602.09657v1)][[code](https://xiaolousun.github.io/AutoFly/)]
(Note: **Dataset, Pseudo depth encoder**)

- AirHunt: Bridging VLM Semantics and Continuous Planning for Efficient Aerial Object Navigation (**arXiv 2026.1**)[[paper](https://arxiv.org/abs/2601.12742)][[code]]
(Note: **Dual system, Memory**)

- Fly0: Decoupling Semantic Grounding from Geometric Planning for Zero-Shot Aerial Navigation (**arXiv 2026.2**)[[paper](https://arxiv.org/abs/2602.15875v1)][[code](https://github.com/xuzhenxing1/Fly0)]
(Note: **Dual system, similar to SPF**)

- USS-Nav: Unified Spatio-Semantic Scene Graph for Lightweight UAV Zero-Shot Object Navigation (**arXiv 2026.2**)[[paper](https://arxiv.org/abs/2602.00708)][[code]]
(Note: **多面体三维空间图，语义选区域、算法走路径，高效Jetson orin nx**)

- AirNav: A Large-Scale Real-World UAV Vision-and-Language Navigation Dataset with Natural and Diverse Instructions (**arXiv 2026.1**)[[paper](https://arxiv.org/abs/2601.03707)][[code](https://littlelucifer1.github.io/AirNav/)]
(Note: **Dataset, AirVLN-R1, Tello**)

- AION: Aerial Indoor Object-Goal Navigation Using Dual-Policy Reinforcement Learning (**arXiv 2026.1**)[[paper](https://arxiv.org/abs/2601.15614)][[code]]
(Note: **Detection & Depth, Exploration & Exploitation, 探索+寻的**)

- Aerial World Model for Long-horizon Visual Generation and Navigation in 3D Space (**arXiv 2026.1**)[[paper](https://arxiv.org/abs/2512.21887)][[code]]
(Note: **Imaging before movement**)

- NavDreamer: Video Models as Zero-Shot 3D Navigators (**arXiv 2026.2**)[[paper](https://arxiv.org/pdf/2602.09765)][[code](https://xinjiu612.github.io/NavDreamer/)]
(Note: **语言指令→视频生成→航点提取→轨迹规划→实际飞行**)

- EzReal: Enhancing Zero-Shot Outdoor Robot Navigation toward Distant Targets under Varying Visibility (**ICRA  2026**)[[paper](https://arxiv.org/pdf/2509.13720)][[code](https://tianlezeng.github.io/EzReal/)]
(Note: **Robots, Object navigation, 看轮廓-辨方向-记方向-寻方向**)

## 2025

- **[Review]** UAVs Meet LLMs: Overviews and Perspectives Toward Agentic Low-Altitude Mobility (**Information Fusion 2025.3**)[[paper](https://doi.org/10.1016/j.inffus.2025.103158)][[code](https://github.com/Hub-Tian/UAVs_Meet_LLMs?tab=readme-ov-file)]

- See, Point, Fly: A Learning-Free VLM Framework for Universal Unmanned Aerial Navigation (**CoRL 2025**)[[paper](https://arxiv.org/pdf/2509.22653)][[code](https://spf-web.pages.dev/)]
(Note: **Dual system, SPF**)

- VLA-AN: An Efficient and Onboard Vision-Language-Action Framework for Aerial Navigation in Complex Environments (**arXiv 2025.12**)[[paper](https://arxiv.org/abs/2512.15258)][[code]]
(Note: **End-to-end, 3-stage training strategy, Onboard implementation**)

- NavRL: Learning Safe Flight in Dynamic Environments (**IEEE Robotics and Automation Letters, 2025.4**)[[paper](https://ieeexplore.ieee.org/document/10904341)][[code](https://github.com/Zhefan-Xu/NavRL)]
(Note: **Deep RL, Using depth info**)

- ASMA: An Adaptive Safety Margin Algorithm for Vision-Language Drone Navigation via Scene-Aware Control Barrier Functions (**IEEE Robotics and Automation Letters, 2025.9**)[[paper](https://ieeexplore.ieee.org/abstract/document/11091440/)][[code](https://github.com/souravsanyal06/ASMA)]
(Note: **VLN + MPC, Using depth info**)

- LongFly: Long-Horizon UAV Vision-and-Language Navigation with Spatiotemporal Context Integration (**arXiv 2025.12**)[[paper](https://arxiv.org/abs/2512.22010v1)][[code]]
(Note: **Using history info**)

- OpenFly: A Comprehensive Platform for Aerial Vision-Language Navigation (**arXiv 2025.7**)[[paper](https://arxiv.org/abs/2502.18041)][[code](https://github.com/SHAILAB-IPEC/OpenFly-Platform)](Note: **Dataset**)

- TypeFly: Low-Latency Drone Planning With Large Language Models (**IEEE Transactions on Mobile Computing 2025.9**) [[paper](https://ieeexplore.ieee.org/abstract/document/10970379)][[code](https://github.com/typefly/TypeFly)]

- Towards Realistic UAV Vision-Language Navigation: Platform, Benchmark, and Methodology (**OpenUAV**) (**ICLR 2025**)[[paper](https://openreview.net/forum?id=rUvCIvI4eB)][[code](https://github.com/prince687028/TravelUAV)]

- MonoSpheres: Large-Scale Monocular SLAM-Based UAV Exploration through Perception-Coupled Mapping and Planning (**arXiv 2025.11**)[[paper](https://arxiv.org/pdf/2511.17299v1)][[code](https://github.com/ctu-mrs/monospheres)](Note: **单目SLAM与感知建图与规划的融合**)

- OpenVLN: Open-world Aerial Vision-Language Navigation (**arXiv 2025.11**)[[paper](https://arxiv.org/pdf/2511.06182v2)][[code]](Note: **利用强化学习和值模型应对数据稀缺和长视域规划的双重挑战**)

- UAV-VLRR: Vision-Language Informed NMPC for Rapid Response in UAV Search and Rescue (**arXiv 2025.3**)[[paper](https://arxiv.org/pdf/2503.02465)][[code](https://github.com/ahsan-mustafa/uav-vlrr)](Note: **VLM + NMPC**)

- UAV-Flow Colosseo: A Real-World Benchmark for Flying-on-a-Word UAV Imitation Learning (**arXiv 2025.5**)[[paper](https://arxiv.org/abs/2505.15725)][[code](https://github.com/buaa-colalab/UAV-Flow)]

- UAV-ON: A Benchmark for Open-World Object Goal Navigation with Aerial Agents (**ACM MM Dataset Track 2025**)[[paper](https://arxiv.org/abs/2508.00288)][[code](https://github.com/Kyaren/UAV_ON)]

- AeroDuo: Aerial Duo for UAV-based Vision and Language Navigation (**ACM MM 2025**)[[paper](https://arxiv.org/abs/2508.15232)][[code]]

- Open3D-VQA: A Benchmark for Comprehensive Spatial Reasoning with Multimodal Large Language Model in Open Space (**ACM MM'25**)[[paper](https://arxiv.org/abs/2503.11094)][[code](https://github.com/EmbodiedCity/Open3D-VQA.code)](Note: **Dataset**)

- CityNav: A Large-Scale Dataset for Real-World Aerial Navigation (**ICCV 2025**)[[paper](https://arxiv.org/abs/2406.14240)][[code](https://water-cookie.github.io/city-nav-proj/)]

- CityNavAgent: Aerial Vision-and-Language Navigation with Hierarchical Semantic Planning and Global Memory (**ACL  2025**)[[paper](https://aclanthology.org/2025.acl-long.1511.pdf)][[code](https://github.com/EmbodiedCity/CityNavAgent.code)]

- VLM-Nav: Mapless UAV-Navigation Using Monocular Vision Driven by Vision-Language Model (**SSRN**)[[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5231854)][[code](https://gcsarker.github.io/vlmnav/)]

- Learning Fine-Grained Alignment for Aerial Vision-Dialog Navigation (**AAAI 2025**)[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/32758/34913)][[code](https://github.com/yifeisu/FELA)]

- UAV-VLA: Vision-Language-Action System for Large Scale Aerial Mission Generation (**Int. Conf. on Human Robot Interaction, HRI 2025**)[[paper](https://arxiv.org/abs/2501.05014)][[code](https://github.com/sautenich/uav-vla)]

- General-Purpose Aerial Intelligent Agents Empowered by Large Language Models (**arXiv 2025.5**)[[paper](https://arxiv.org/abs/2503.08302)][[code]]

- RAVEN: Resilient Aerial Navigation via Open-Set Semantic Memory and Behavior Adaptation (**arXiv 2025.9** "Best Paper Finalist at IROS 2025 Active Perception Workshop")[[paper](https://arxiv.org/pdf/2509.23563)][[project](https://raven-semantic.github.io/)]


## 2024

- **[Review]** Large Language Models for UAVs: Current State and Pathways to the Future (**IEEE Open Journal of Vehicular Technology 2024.8**) [[paper](https://ieeexplore.ieee.org/document/10643253)][[code]]

- AeroVerse: UAV-Agent Benchmark Suite for Simulating, Pre-training, Finetuning, and Evaluating Aerospace Embodied World Models (**arXiv 2024.8**)[[paper](https://arxiv.org/abs/2408.15511)][[code]]

- TPML: Task Planning for Multi-UAV System with Large Language Models (**2024 IEEE 18th International Conference on Control & Automation (ICCA)**)[[paper](https://ieeexplore.ieee.org/document/10591846)][[code](https://github.com/PengICS/eai_sim)]

- EAI-SIM: An Open-Source Embodied AI Simulation Framework with Large Language Models (**2024 IEEE 18th International Conference on Control & Automation (ICCA)**)[[paper](https://ieeexplore.ieee.org/document/10591865)][[code](https://github.com/PengICS/eai_sim)]

- Aerial Vision-and-Language Navigation via Semantic-Topo-Metric Representation Guided LLM Reasoning (**STMR**) (**Submitted to ICRA 2025**)[[paper](https://arxiv.org/abs/2410.08500v1)][[code]]


## 2023

- AerialVLN: Vision-and-Language Navigation for UAVs (**ICCV 2023**)[[paper](https://arxiv.org/abs/2308.06735)][[code](https://github.com/AirVLN/AirVLN)]


## System1 + System2 Thinking

- Visual Agents as Fast and Slow Thinkers (**ICLR 2025**)[[paper](https://arxiv.org/abs/2408.08862)][[code](https://github.com/GuangyanS/Sys2-LLaVA)]

- Dualformer: Controllable Fast and Slow Thinking by Learning with Randomized Reasoning Traces (**arXiv 2025**)[[paper](https://arxiv.org/abs/2410.09918v1)][[code]]

- Helix: A "System 1, System 2" VLA for Whole Upper Body Control (**figure.ai**) [[link](https://www.figure.ai/news/helix)]

- DriveVLM: The Convergence of Autonomous Driving and Large Vision-Language Models (**Conference on Robot Learning (CoRL) 2024**)[[paper](https://arxiv.org/abs/2402.12289v5)][[project](https://tsinghua-mars-lab.github.io/DriveVLM/)]

- Hi Robot: Open-Ended Instruction Following with Hierarchical Vision-Language-Action Models (**Physical Intelligence (π)**) (**ICML 2025**)[[paper](https://arxiv.org/abs/2502.19417)][[blog](https://www.pi.website/research/hirobot)]

- HiRT: Enhancing Robotic Control with Hierarchical Robot Transformers (**Conference on Robot Learning (CoRL) 2024**)[[paper](https://arxiv.org/abs/2410.05273v3)][[code]]

- GR00T N1: An Open Foundation Model for Generalist Humanoid Robots (**arXiv 2025.3**)[[paper](https://arxiv.org/abs/2503.14734)][[code](https://github.com/NVIDIA/Isaac-GR00T)][[tech](https://developer.nvidia.com/isaac/gr00t)]

- GR00T N1.5: An Improved Open Foundation Model for Generalist Humanoid Robots [[tech](https://research.nvidia.com/labs/gear/gr00t-n1_5/)][[code](https://github.com/NVIDIA/Isaac-GR00T)][[blog](https://learnopencv.com/gr00t-n1_5-explained/)]


## Related Awesome lists

- [Hub-Tian/UAVs_Meet_LLMs](https://github.com/Hub-Tian/UAVs_Meet_LLMs)

- [Jiaaqiliu/Awesome-VLA-Robotics](https://github.com/Jiaaqiliu/Awesome-VLA-Robotics)

- [Sautenich/Awesome-Aerial-Vision-Language-Navigation](https://github.com/Sautenich/Awesome-Aerial-Vision-Language-Navigation)


- [Thinklab-SJTU/Awesome-LLM4AD](https://github.com/Thinklab-SJTU/Awesome-LLM4AD)

- [jonyzhang2023/awesome-embodied-vla-va-vln](https://github.com/jonyzhang2023/awesome-embodied-vla-va-vln)
