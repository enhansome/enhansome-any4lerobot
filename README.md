# Awesome any4lerobot with stars

<h1 align="center">
    <p>Any4LeRobot: A tool collection for LeRobot</p>
</h1>

<div align="center">

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/Tavish9/any4lerobot)
[![Python versions](https://img.shields.io/pypi/pyversions/lerobot)](https://www.python.org/downloads/)
[![LeRobot Dataset](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/repos/tavish9/any4lerobot/commits?per_page=1\&query=$\[0\].commit.committer.date\&label=LeRobot\&color=blue)](https://github.com/huggingface/lerobot) ⭐ 27,005 | 🐛 833 | 🌐 Python | 📅 2026-08-28
[![LeRobot Dataset](https://img.shields.io/badge/LeRobot%20Dataset-v3.0-ff69b4.svg)](https://github.com/huggingface/lerobot/pull/1412) ⭐ 27,005 | 🐛 833 | 🌐 Python | 📅 2026-08-28
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

</div>

> \[!IMPORTANT]
>
> **Star and Contribute**, let's make community of robotics better and better! 🔥

A curated collection of utilities for [LeRobot Projects](https://github.com/huggingface/lerobot) ⭐ 27,005 | 🐛 833 | 🌐 Python | 📅 2026-08-28, including data conversion scripts, preprocessing tools, training workflow helpers and etc..

## 📣 What's New <a><img width="35" height="20" src="https://user-images.githubusercontent.com/12782558/212848161-5e783dd6-11e8-4fe0-bbba-39ffb77730be.png"></a>

* **\[2026.06.12]** We have provided an efficient and concise Generic Converter for building new dataset-to-LeRobot converters with minimal adapter code! 🔥🔥🔥
* **\[2026.03.20]** We have supported Data Conversion from RoboCasa to LeRobot! 🔥🔥🔥
* **\[2025.10.04]** We have collected and updated all Dataset Version Conversion Scripts for LeRobot! 🔥🔥🔥
* **\[2025.09.28]** We have upgraded LeRobotDataset from v2.1 to v3.0! 🔥🔥🔥
* **\[2025.06.27]** We have supported Data Conversion from LIBERO to LeRobot! 🔥🔥🔥

<details>
<summary>More News</summary>

* **\[2025.05.16]** We have supported Data Conversion from LeRobot to RLDS! 🔥🔥🔥
* **\[2025.05.12]** We have supported Data Conversion from RoboMIND to LeRobot! 🔥🔥🔥
* **\[2025.04.15]** We add Dataset Merging Tool for merging multi-source lerobot datasets! 🔥🔥🔥
* **\[2025.04.14]** We have supported Data Conversion from AgiBotWorld to LeRobot! 🔥🔥🔥
* **\[2025.04.11]** We change the repo from `openx2lerobot` to `any4lerobot`, making a ​​universal toolbox for LeRobot​​! 🔥🔥🔥
* **\[2025.02.19]** We have supported Data Conversion from Open X-Embodiment to LeRobot! 🔥🔥🔥

</details>

## ✨ Features

* **Dataset Tutorial**:

  * [ ] Dataset Loading
  * [ ] Dataset Editing
  * [ ] Dataset Filtering
  * [ ] Dataset Sampling
  * [ ] Dataset Merging

* ​**​Data Conversion​**​:

  * [x] [Generic Converter](./generic_converter/README.md)
  * [x] [Open X-Embodiment to LeRobot](./openx2lerobot/README.md)
  * [x] [AgiBot-World to LeRobot](./agibot2lerobot/README.md)
  * [x] [RoboMIND to LeRobot](./robomind2lerobot/README.md)
  * [x] [LeRobot to RLDS](./lerobot2rlds/README.md)
  * [x] [LIBERO to LeRobot](./libero2lerobot/README.md)
  * [x] [RoboCasa to LeRobot](./robocasa2lerobot/README.md)

* ​[**Version Conversion​**​](./ds_version_convert/README.md):

  * [x] [LeRobotv1.6 to LeRobotv2.0](./ds_version_convert/v16_to_v20/README.md)
  * [x] [LeRobotv2.0 to LeRobotv2.1](./ds_version_convert/v20_to_v21/README.md)
  * [x] [LeRobotv2.1 to LeRobotv2.0](./ds_version_convert/v21_to_v20/README.md)
  * [x] [LeRobotv2.1 to LeRobotv3.0](./ds_version_convert/v21_to_v30/README.md)
  * [x] [LeRobotv3.0 to LeRobotv2.1](./ds_version_convert/v30_to_v21/README.md)

* **Training**:

  * [ ] MultiLeRobotDataset

* [**Want more features?**](https://github.com/Tavish9/any4lerobot/issues/new?template=feature-request.yml) ⭐ 1,142 | 🐛 4 | 🌐 Python | 📅 2026-08-17

## 📚 Awesome LeRobot

### Model

* [SmolVLA](https://huggingface.co/blog/smolvla): Efficient Vision-Language-Action Model trained on Lerobot Community Data [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/huggingface/lerobot">](https://github.com/huggingface/lerobot) ⭐ 27,005 | 🐛 833 | 🌐 Python | 📅 2026-08-28
* [openpi](https://www.physicalintelligence.company/blog/pi0): the official implementation of $π\_0$: A Vision-Language-Action Flow Model for General Robot Control [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/Physical-Intelligence/openpi">](https://github.com/Physical-Intelligence/openpi) ⭐ 13,516 | 🐛 329 | 🌐 Python | 📅 2026-08-24
* [Isaac-GR00T](https://developer.nvidia.com/isaac/gr00t): NVIDIA Isaac GR00T N1 is the world's first open foundation model for generalized humanoid robot reasoning and skills [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/NVIDIA/Isaac-GR00T">](https://github.com/NVIDIA/Isaac-GR00T) ⭐ 7,944 | 🐛 322 | 🌐 Python | 📅 2026-08-20
* [SpatialVLA](https://spatialvla.github.io/): a spatial-enhanced vision-language-action model that is trained on 1.1 Million real robot episodes [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/SpatialVLA/SpatialVLA">](https://github.com/SpatialVLA/SpatialVLA) ⭐ 717 | 🐛 36 | 🌐 Python | 📅 2025-06-23
* [EO1](https://eo-robotics.ai/eo-1): An Open Unified Embodied Foundation Model for General Robot Control Trained on Interleaved Vision-Text-Action Data [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/EO-Robotics/EO1">](https://github.com/EO-Robotics/EO1) ⚠️ Archived
* [OneTwoVLA](https://one-two-vla.github.io/): A Unified Vision-Language-Action Model with Adaptive Reasoning [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/Fanqi-Lin/OneTwoVLA">](https://github.com/Fanqi-Lin/OneTwoVLA) ⭐ 238 | 🐛 14 | 🌐 Python | 📅 2025-05-30
* [Hume](https://hume-vla.github.io): A Dual-System VLA with System2 Thinking [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/hume-vla/hume">](https://github.com/hume-vla/hume) ⭐ 149 | 🐛 14 | 🌐 Python | 📅 2025-08-21

### Dataset

* [Official](https://huggingface.co/lerobot): State-of-the-art Machine Learning for real-world robotics.
* [IPEC-COMMUNITY/OpenX](https://huggingface.co/collections/IPEC-COMMUNITY/openx-lerobot-67c29b2ee5911f17dbea635e): Open X-Embodiment datasets in LeRobot format with standard transformation
* [IPEC-COMMUNITY/LIBERO](https://huggingface.co/collections/IPEC-COMMUNITY/libero-benchmark-dataset-684837af28d465aa8b043950): LIBERO datasets in LeRobot format with standard transformation and filtering
* [weijian-sun/agibotworld-lerobot](https://huggingface.co/datasets/weijian-sun/agibotworld-lerobot): AgibotWorld-LeRobot v2.0
* [GR00T-Dateset](https://huggingface.co/GR00T-Dateset): Isaac-GR00T training dataset
* [nvidia/PhysicalAI-Robotics-GR00T-X-Embodiment-Sim](https://huggingface.co/datasets/nvidia/PhysicalAI-Robotics-GR00T-X-Embodiment-Sim): Isaac-GR00T training dataset
* [RoboCOIN/robocoin](https://huggingface.co/collections/RoboCOIN/robocoin): An open-source bimanual robot manipulation dataset
* [behavior-1k/2025-challenge-demos](https://huggingface.co/datasets/behavior-1k/2025-challenge-demos): BEHAVIOR Challenge dataset

### Embodiment Extensions

* [unitree\_IL\_lerobot](https://github.com/unitreerobotics/unitree_IL_lerobot) ⭐ 755 | 🐛 28 | 🌐 Python | 📅 2026-05-25: a training framework enabling the training and testing of data collected using Unitree's G1 robot [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/unitreerobotics/unitree_IL_lerobot">](https://github.com/unitreerobotics/unitree_IL_lerobot) ⭐ 755 | 🐛 28 | 🌐 Python | 📅 2026-05-25
* [U-Arm](https://github.com/MINT-SJTU/LeRobot-Anything-U-Arm) ⭐ 316 | 🐛 4 | 🌐 Python | 📅 2026-07-15: Lerobot-Everything-Cross-Embodiment-Teleoperation [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/MINT-SJTU/LeRobot-Anything-U-Arm">](https://github.com/MINT-SJTU/LeRobot-Anything-U-Arm) ⭐ 316 | 🐛 4 | 🌐 Python | 📅 2026-07-15
* [LeFranX](https://github.com/wengmister/LeFranX) ⭐ 143 | 🐛 0 | 🌐 Python | 📅 2025-09-22: Franka and XHand Extension for LeRobot [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/wengmister/LeFranX">](https://github.com/wengmister/LeFranX) ⭐ 143 | 🐛 0 | 🌐 Python | 📅 2025-09-22
* [Dora-LeRobot](https://github.com/dora-rs/dora-lerobot) ⭐ 134 | 🐛 5 | 🌐 Python | 📅 2025-01-08: Lerobot boosted with dora [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/dora-rs/dora-lerobot">](https://github.com/dora-rs/dora-lerobot) ⭐ 134 | 🐛 5 | 🌐 Python | 📅 2025-01-08
* [Fourier-Lerobot](https://github.com/FFTAI/fourier-lerobot) ⭐ 85 | 🐛 7 | 🌐 Python | 📅 2026-02-12: A training pipeline with Fourier dataset [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/FFTAI/fourier-lerobot">](https://github.com/FFTAI/fourier-lerobot) ⭐ 85 | 🐛 7 | 🌐 Python | 📅 2026-02-12
* [lerobot-piper](https://github.com/lykycy123/lerobot-piper) ⭐ 55 | 🐛 2 | 🌐 Python | 📅 2025-09-10: About Use Lerobot to collect piper robot arm data, and perform training and reasoning [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/lykycy123/lerobot-piper">](https://github.com/lykycy123/lerobot-piper) ⭐ 55 | 🐛 2 | 🌐 Python | 📅 2025-09-10
* [BiLerobot](https://github.com/LiZhYun/BiLerobot) ⭐ 43 | 🐛 0 | 🌐 Python | 📅 2025-06-26: A bimanual robotics platform combining LeRobot and ManiSkill for advanced dual-arm manipulation tasks using the SO100 robot digital twin [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/LiZhYun/BiLerobot">](https://github.com/LiZhYun/BiLerobot) ⭐ 43 | 🐛 0 | 🌐 Python | 📅 2025-06-26
* [Lerobot-koch](https://github.com/LilyHuang-HZ/Lerobot-koch) ⭐ 30 | 🐛 0 | 📅 2025-05-16: LeRobot Training Notes for Koch Arm [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/LilyHuang-HZ/Lerobot-koch">](https://github.com/LilyHuang-HZ/Lerobot-koch) ⭐ 30 | 🐛 0 | 📅 2025-05-16
* [lerobot-robot-xarm](https://github.com/SpesRobotics/lerobot-robot-xarm) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2026-05-08: xArm integration for LeRobot [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/SpesRobotics/lerobot-robot-xarm">](https://github.com/SpesRobotics/lerobot-robot-xarm) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2026-05-08
* [Adora-LeRobot](https://github.com/Ryu-Yang/adora-lerobot) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2025-05-12: a modified version of lerobot, specifically adapted for the Adora robot [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/Ryu-Yang/adora-lerobot">](https://github.com/Ryu-Yang/adora-lerobot) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2025-05-12

### Hardware

* [XLeRobot](https://github.com/Vector-Wangel/XLeRobot) ⭐ 5,463 | 🐛 39 | 🌐 Python | 📅 2026-07-22: Fully Autonomous Household Dual-Arm Mobile Robot for $998 [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/Vector-Wangel/XLeRobot">](https://github.com/Vector-Wangel/XLeRobot) ⭐ 5,463 | 🐛 39 | 🌐 Python | 📅 2026-07-22
* [LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi) ⭐ 1,393 | 🐛 12 | 📅 2026-08-05: Low-Cost Mobile Manipulator [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/SIGRobotics-UIUC/LeKiwi">](https://github.com/SIGRobotics-UIUC/LeKiwi) ⭐ 1,393 | 🐛 12 | 📅 2026-08-05
* [lerobotdepot](https://github.com/maximilienroberti/lerobotdepot) ⭐ 237 | 🐛 18 | 📅 2026-04-09: a repo for hardware, components, and 3D-printable projects compatible with the LeRobot library [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/maximilienroberti/lerobotdepot">](https://github.com/maximilienroberti/lerobotdepot) ⭐ 237 | 🐛 18 | 📅 2026-04-09
* [LeRobot-Kinematics](https://github.com/box2ai-robotics/lerobot-kinematics) ⭐ 126 | 🐛 0 | 🌐 C++ | 📅 2025-08-16: Simple and Accurate Forward and Inverse Kinematics Examples for the Lerobot SO100 ARM [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/box2ai-robotics/lerobot-kinematics">](https://github.com/box2ai-robotics/lerobot-kinematics) ⭐ 126 | 🐛 0 | 🌐 C++ | 📅 2025-08-16
* [PingTi-Arm](https://github.com/nomorewzx/PingTi-Arm) ⭐ 54 | 🐛 4 | 📅 2025-12-08: A human-scale robotic arm compatible with Lerobot, based on SO100 [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/nomorewzx/PingTi-Arm">](https://github.com/nomorewzx/PingTi-Arm) ⭐ 54 | 🐛 4 | 📅 2025-12-08
* [LeDog](https://github.com/wuxiaoqiang12/LeDog) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-12-28: A mobile manipulator with a Weilan AlphaDog and a LeRobot-compatible SO-101 arm, with support for ROS 1/2 (Official: [ledog\_ros2](https://gitcode.com/openeuler/ledog_ros2)) [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/wuxiaoqiang12/LeDog">](https://github.com/wuxiaoqiang12/LeDog) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-12-28

### Tutorial / Utils

* [LeRobot Tutorial with MuJoCo](https://github.com/jeongeun980906/lerobot-mujoco-tutorial) ⭐ 610 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2025-09-28: Examples for collecting data and training with MuJoCo [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/jeongeun980906/lerobot-mujoco-tutorial">](https://github.com/jeongeun980906/lerobot-mujoco-tutorial) ⭐ 610 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2025-09-28
* [Robot Learning: A Tutorial](https://github.com/fracapuano/robot-learning-tutorial) ⭐ 571 | 🐛 16 | 🌐 TeX | 📅 2026-04-09: All the source code for "Robot Learning: A Tutorial". Get involved to be featured in the next iteration [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/fracapuano/robot-learning-tutorial">](https://github.com/fracapuano/robot-learning-tutorial) ⭐ 571 | 🐛 16 | 🌐 TeX | 📅 2026-04-09
* [LeRobot Sim2Real](https://github.com/StoneT2000/lerobot-sim2real) ⭐ 397 | 🐛 11 | 🌐 Python | 📅 2026-06-15: Train in fast simulation and deploy visual policies zero shot to the real world [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/StoneT2000/lerobot-sim2real">](https://github.com/StoneT2000/lerobot-sim2real) ⭐ 397 | 🐛 11 | 🌐 Python | 📅 2026-06-15
* [CRISP](https://utiasdsl.github.io/crisp_controllers/): Record datasets and deploy policies using LeRobot and ROS2-compatible manipulators (Franka Robotics FR3 and more supported) [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/utiasdsl/crisp_controllers">](https://github.com/utiasdsl/crisp_controllers) ⭐ 233 | 🐛 9 | 🌐 C++ | 📅 2026-08-16
* [lerobot\_ws](https://github.com/Pavankv92/lerobot_ws) ⭐ 170 | 🐛 4 | 🌐 Python | 📅 2025-07-09: ROS 2 Package for LeRobot SO-ARM101 [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/Pavankv92/lerobot_ws">](https://github.com/Pavankv92/lerobot_ws) ⭐ 170 | 🐛 4 | 🌐 Python | 📅 2025-07-09
* [LeRobotTutorial-CN](https://github.com/CSCSX/LeRobotTutorial-CN) ⭐ 151 | 🐛 1 | 📅 2025-01-17: a tutorial for LeRobot in Chinese [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/CSCSX/LeRobotTutorial-CN">](https://github.com/CSCSX/LeRobotTutorial-CN) ⭐ 151 | 🐛 1 | 📅 2025-01-17
* [Robotics Course](https://github.com/huggingface/robotics-course) ⭐ 149 | 🐛 24 | 🌐 MDX | 📅 2026-05-26: A course on robotics by Hugging Face using LeRobot [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/huggingface/robotics-course">](https://github.com/huggingface/robotics-course) ⭐ 149 | 🐛 24 | 🌐 MDX | 📅 2026-05-26
* [Physical AI Tools](https://github.com/ROBOTIS-GIT/physical_ai_tools) ⭐ 143 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-26: Physical AI Development Interface with LeRobot and ROS 2 [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/ROBOTIS-GIT/physical_ai_tools">](https://github.com/ROBOTIS-GIT/physical_ai_tools) ⭐ 143 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-26
* [LeRobot Dataset Visualizer](https://github.com/huggingface/lerobot-dataset-visualizer) ⭐ 124 | 🐛 11 | 🌐 TypeScript | 📅 2026-07-24: Web application for visualizing robotics datasets in LeRobot format [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/huggingface/lerobot-dataset-visualizer">](https://github.com/huggingface/lerobot-dataset-visualizer) ⭐ 124 | 🐛 11 | 🌐 TypeScript | 📅 2026-07-24
* [LeRobot Episode Scoring Toolkit](https://github.com/RoboticsData/score_lerobot_episodes) ⭐ 74 | 🐛 5 | 🌐 Python | 📅 2026-03-13: One-click tool to score, filter, and export higher-quality LeRobot datasets [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/RoboticsData/score_lerobot_episodes">](https://github.com/RoboticsData/score_lerobot_episodes) ⭐ 74 | 🐛 5 | 🌐 Python | 📅 2026-03-13
* [lerobot\_so101\_teleop](https://github.com/liorbenhorin/lerobot_so101_teleop) ⭐ 66 | 🐛 1 | 🌐 Python | 📅 2025-12-30: Sample Environment for the LeRobot SO-101 Robot in Isaac Lab to collect demonstrations in a simulation [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/liorbenhorin/lerobot_so101_teleop">](https://github.com/liorbenhorin/lerobot_so101_teleop) ⭐ 66 | 🐛 1 | 🌐 Python | 📅 2025-12-30
* [lerobot-hilserl-guide](https://github.com/michel-aractingi/lerobot-hilserl-guide) ⭐ 54 | 🐛 3 | 📅 2025-09-29: Guide and tutorial to run the HILSerl implementation of LeRobot [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/michel-aractingi/lerobot-hilserl-guide">](https://github.com/michel-aractingi/lerobot-hilserl-guide) ⭐ 54 | 🐛 3 | 📅 2025-09-29
* [LeRobot.js](https://github.com/TimPietrusky/lerobot.js) ⭐ 39 | 🐛 3 | 🌐 TypeScript | 📅 2025-11-14: interact with your robot in JS, inspired by LeRobot [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/TimPietrusky/lerobot.js">](https://github.com/TimPietrusky/lerobot.js) ⭐ 39 | 🐛 3 | 🌐 TypeScript | 📅 2025-11-14
* [lerobot-ros](https://github.com/astroyat/lerobot-ros) ⭐ 36 | 🐛 2 | 📅 2026-02-16: Running LeRobot and ROS 2 on custom LIDAR [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/astroyat/lerobot-ros">](https://github.com/astroyat/lerobot-ros) ⭐ 36 | 🐛 2 | 📅 2026-02-16
* [LeLab](https://github.com/nicolas-rabault/leLab) ⭐ 22 | 🐛 2 | 🌐 Python | 📅 2026-04-29: A web UI interface on top of lerobot [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/nicolas-rabault/leLab">](https://github.com/nicolas-rabault/leLab) ⭐ 22 | 🐛 2 | 🌐 Python | 📅 2026-04-29
* [LERO](https://github.com/masato-ka/lero) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2025-08-09: LeRobot dataset operations toolkit [<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/masato-ka/lero">](https://github.com/masato-ka/lero) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2025-08-09
* [Official Docs](https://huggingface.co/docs/lerobot/en/getting_started_real_world_robot): This tutorial will explain how to train a neural network to control a real robot autonomously.
* [YouTube: LeRobot Tutorials](https://www.youtube.com/playlist?list=PLo2EIpI_JMQu5zrDHe4NchRyumF2ynaUN)
* [PathOn.AI](https://learn-robotics.pathon.ai/): Learn Robotics at PathOn.AI is a platform for learning robotics and AI
* [NVIDIA Jetson Tutorials](https://www.jetson-ai-lab.com/lerobot.html)

## 👷‍♂️ Contributing

We appreciate all contributions to improving Any4LeRobot!

<a href="https://github.com/Tavish9/any4lerobot/graphs/contributors" target="_blank">
  <img src="https://contrib.rocks/image?repo=tavish9/any4lerobot">
</a>

## 📝 License

This project is released under the [MIT License](./LICENSE).

## 📖 Citation

If you find this repository helpful in your research or projects, please consider citing it:

```bibtex
@misc{any4lerobot,
  title        = {Any4LeRobot: A tool collection for LeRobot},
  author       = {Qizhi Chen, Dong Wang, Bin Zhao},
  license      = {MIT},
  url          = {https://github.com/Tavish9/any4lerobot},
  year         = {2025},
}

@article{eo1,
  title={EO-1: Interleaved Vision-Text-Action Pretraining for General Robot Control},
  author={Delin Qu and Haoming Song and Qizhi Chen and Zhaoqing Chen and Xianqiang Gao and Xinyi Ye and Qi Lv and Modi Shi and Guanghui Ren and Cheng Ruan and Maoqing Yao and Haoran Yang and Jiacheng Bao and Bin Zhao and Dong Wang},
  journal={arXiv preprint},
  year={2025},
  url={https://arxiv.org/abs/2508.21112}
}
```

## ⭐ Star History

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://star-history.dera.page/svg?repos=Tavish9/any4lerobot&type=Date&theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://star-history.dera.page/svg?repos=Tavish9/any4lerobot&type=Date" />
  <img alt="Star History Chart" src="https://star-history.dera.page/svg?repos=Tavish9/any4lerobot&type=Date" />
</picture>

<p align="right"><a href="#top">🔝 Back to top</a></p>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
