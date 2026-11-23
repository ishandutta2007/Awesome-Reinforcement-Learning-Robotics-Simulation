# Awesome-Reinforcement-Learning-Robotics-Simulation

## Top Reinforcement Learning & Robotics Simulation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Physics Simulators, Robot Learning Environments, GPU-Parallel RL & Embodied AI Training*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Reinforcement Learning & Robotics Simulation**. These tools provide physics engines, sensor models, and environment APIs to train and evaluate robot policies before real-world deployment.



**Examples** include NVIDIA Isaac Gym / Isaac Sim, MuJoCo Cloud-style offerings, Webots, CoppeliaSim, AWS RoboMaker, Gazebo, Unity Robotics Hub, Project Chrono, Genesis, AI Habitat, and community Gym-compatible stacks such as openGym-style projects.



**Open-source emphasis**: Robotics simulation and RL tooling are strongly open. **MuJoCo**, **Gazebo**, **Webots**, **Genesis**, **Gymnasium**, **Isaac Lab** (open components), **Habitat**, and **PyBullet** power most research pipelines. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[NVIDIA Isaac / Omniverse-hosted workflows, AWS RoboMaker](https://developer.nvidia.com/isaac)**  

  Cloud and workstation platforms for large-scale robot simulation, synthetic data, and fleet testing.



- **[Unity Robotics / cloud build pipelines](https://unity.com/solutions/automotive-transportation-manufacturing)**  

  Game-engine-based robotics simulation with hosted CI and collaboration options.



- **[Managed MuJoCo / Webots / specialty sim clouds](https://mujoco.org/)**  

  Hosted or appliance-style access to popular simulators for teams that prefer not to operate GPU farms.



- **[Other commercial robotics simulation platforms](https://aws.amazon.com/robomaker/)**  

  Additional digital-twin and robot-training cloud services.



## Open-Source GitHub Projects



### Physics Simulators & Robot Platforms



- **[MuJoCo](https://github.com/google-deepmind/mujoco)**  

  Open high-performance physics engine (Apache-2.0)—standard for contact-rich RL and continuous control; MJX enables GPU-accelerated parallel simulation.



- **[Gazebo / Gazebo Sim (gz)](https://github.com/gazebosim/gz-sim)**  

  Open robot simulation platform tightly integrated with ROS 2—sensors, multi-robot worlds, and industry-standard tooling.



- **[Webots](https://github.com/cyberbotics/webots)**  

  Open robot simulator—education through research, multi-robot scenarios, and native ROS 2 support (Apache-2.0).



- **[Genesis](https://github.com/Genesis-Embodied-AI/Genesis)**  

  Open simulation platform for robotics and embodied AI—high-throughput, multi-physics, and GPU-oriented training workloads.



- **[PyBullet / Bullet](https://github.com/bulletphysics/bullet3)**  

  Open physics engine and Python robotics/RL environments—fast prototyping and teaching.



- **[Project Chrono](https://github.com/projectchrono/chrono)**  

  Open multi-physics dynamics engine—vehicles, granular media, and complex mechanical systems.



- **[CoppeliaSim (community / EDU paths)](https://github.com/CoppeliaRobotics)**  

  Widely used robot simulator with free/edu licensing tiers; check current terms for commercial use.



### NVIDIA & Photorealistic Stacks



- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)**  

  Open unified framework for robot learning on Isaac Sim—multi-physics/renderer workflows for RL and imitation learning.



- **[Isaac Sim (open application components)](https://github.com/isaac-sim/IsaacSim)**  

  NVIDIA’s robot simulation application on Omniverse—photorealistic sensors and domain randomization (license: NVIDIA terms; extensive open code/examples).



### Embodied AI & 3D Environments



- **[AI Habitat](https://github.com/facebookresearch/habitat-sim)**  

  Open embodied AI simulation platform—photorealistic indoor navigation and interaction research.



- **[iGibson / OmniGibson-style platforms](https://github.com/StanfordVL/iGibson)**  

  Open interactive household environments for mobile manipulation research.



### RL APIs & Algorithm Libraries



- **[Gymnasium](https://github.com/Farama-Foundation/Gymnasium)**  

  Standard open API for single-agent RL environments (successor to OpenAI Gym)—reference envs and wide third-party ecosystem.



- **[Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3)**  

  Reliable open implementations of RL algorithms—PPO, SAC, TD3, and more on top of Gymnasium.



- **[CleanRL / RLlib / other trainers](https://github.com/vwxyzjn/cleanrl)**  

  Open single-file and distributed RL training stacks used with MuJoCo, Isaac, and custom robots.



- **[openGym and community Gym forks](https://github.com/search?q=openGym+reinforcement+learning)**  

  Community Gym-compatible environment collections—verify maintenance and API compatibility with Gymnasium.



### Additional Strong Open-Source Options



- **Fast RL / manipulation research**: MuJoCo (+ MJX).

- **ROS 2 system integration**: Gazebo Sim or Webots.

- **Max parallel throughput / embodied AI**: Genesis or Isaac Lab.

- **Navigation / indoor embodied**: Habitat.

- **Standard env API**: Gymnasium + Stable-Baselines3.

- **Composable stacks**: MuJoCo/Genesis envs → Gymnasium API → SB3/CleanRL; or Isaac Lab for photoreal + domain randomization.

- Commercial clouds still lead for large managed GPU farms and enterprise digital-twin support.



**Frameworks for building custom systems**:  

**MuJoCo** or **Genesis** for high-speed policy learning; **Gazebo**/**Webots** for ROS-centric robots; **Isaac Lab** for photorealistic GPU pipelines; **Gymnasium** as the common env interface.  

Fully open RL and robotics simulation stacks are the research and industry default.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Simulation is not reality—validate policies on hardware with appropriate safety controls. Some platforms use free-of-charge licenses that are not OSI open source (e.g. certain NVIDIA terms); read licenses before redistribution or commercial embedding.

- Open-source simulators offer transparency and reproducibility. Hosted platforms shift GPU capacity and ops to the vendor. Neither replaces careful sim-to-real methodology.



---



**Made for robot learning researchers, embodied AI engineers, and teams bridging simulation to hardware.**  

Let's expand open reinforcement learning and robotics simulation while recognizing the scale and rendering depth that commercial and NVIDIA-centric platforms deliver.
