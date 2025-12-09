<div align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="600" height="auto"/>
  
  <h1>Hi there, I'm Chen Yun 👋</h1>
  
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=4000&pause=1000&color=36BCF7&center=true&vCenter=true&width=500&lines=Robotics+Software+Engineer;Lidar-Inertial+SLAM+Specialist;Reinforcement+Learning+(HRL)+Researcher;ROS+2+%26+Gazebo+Simulation+Expert" alt="Typing SVG" />
  </a>

  <p>
    🚀 <b>SLAM & RL 开发者</b> | 专注于非结构化环境下的移动机器人导航与操作。<br>
    擅长解决 <b>Sim2Real</b> 迁移问题及 <b>多传感器（Lidar/IMU/GNSS）</b> 时空同步与融合难题。
  </p>

  <p>
    <img src="https://komarev.com/ghpvc/?username=chan-yuu&label=Profile%20Views&color=0e75b6&style=flat" alt="chan-yuu" />
  </p>

  <p>
    <a href="mailto:your_email@example.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
    <a href="https://linkedin.com/in/your-profile">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
  </p>
</div>

---

### 🛠️ Technical Arsenal

<div align="center">

| Core | Technologies |
| :--- | :--- |
| **SLAM & Perception** | ![ROS](https://img.shields.io/badge/ROS-Noetic-22314E?logo=ros&logoColor=white) ![GTSAM](https://img.shields.io/badge/GTSAM-Factor_Graph-blue) ![PCL](https://img.shields.io/badge/PCL-Point_Cloud-blue) ![Ceres](https://img.shields.io/badge/Ceres-Solver-red) **LIO-SAM**, **FAST-LIO2** |
| **RL & AI** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![Gymnasium](https://img.shields.io/badge/Gymnasium-RL-black) ![SB3](https://img.shields.io/badge/Stable_Baselines3-PPO-brightgreen) **Hierarchical RL** |
| **Simulation & Dev** | ![Gazebo](https://img.shields.io/badge/Gazebo-Classic%2FIgnition-orange) ![ROS2](https://img.shields.io/badge/ROS2-Humble-22314E?logo=ros&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-Container-2496ED?logo=docker&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-Build-064F8C?logo=cmake&logoColor=white) |

</div>

---

### 🔭 Featured Projects (核心项目展示)

#### 1. 🤖 Autonomous Forklift Navigation & Manipulation (HRL)
> *基于分层强化学习（Hierarchical RL）的复杂长序列任务实现*
* **Core Tech**: ROS 2 Humble, Gazebo, PyTorch, PPO, Behavior Trees.
* **Key Contributions**:
    * 设计了 **Navigation -> Pick -> Place** 的分层决策架构，解决了稀疏奖励下的训练收敛难题。
    * 搭建了高保真 Gazebo 仿真环境，实现了叉车动力学模型与货物交互物理引擎的精确模拟。
    * 实现了 Sim2Real 部署，结合 `nav2` 处理全局路径规划，利用 RL 处理局部精细操作。
* [🔗 View Repository](https://github.com/chan-yuu/forklift_rl_sim) *(请确认你的仓库名是否为 forklift_rl_sim 或替换链接)*

#### 2. 📡 LIO-SAM-Robosense-Adapter
> *适配 Robosense (速腾) 雷达的紧耦合激光惯性里程计系统*
* **Core Tech**: C++, GTSAM, PCL, Robot_Localization.
* **Key Contributions**:
    * **驱动层适配**: 重写 `imageProjection.cpp`，解决了 `rslidar_sdk` 绝对时间戳 (`timestamp`) 与 LIO-SAM 相对时间 (`time`) 的转换问题。
    * **鲁棒性增强**: 增加了对 `NaN` 点云的过滤和 `Ring` 通道缺失的自动计算回退机制。
    * **外参校准**: 修正了 `extrinsicRot` 与 `extrinsicRPY` 的坐标系定义冲突，实现了重力向量的精确对齐。
* [🔗 View Repository](https://github.com/chan-yuu/LIO-SAM) *(指向你修改过的 LIO-SAM 仓库)*

#### 3. 🎯 Multi-Sensor Calibration Toolkit
> *基于运动激励的 LiDAR-IMU 在线/离线标定方案*
* **Core Tech**: FAST-LIO2, Ceres Solver.
* **Key Contributions**:
    * 利用 **FAST-LIO2** 的卡尔曼滤波状态估计特性，实现了手持晃动下的外参在线自标定。
    * 解决了 LiDAR 与 IMU 坐标系 90度/180度 旋转的数学歧义问题。
    * 提供了从 `lidar_imu_calib` 到 LIO-SAM 配置文件的参数转换脚本。
* [🔗 View Repository](https://github.com/chan-yuu/sensor_calibration_tools) *(如果有相关标定代码仓库)*

---

### 📊 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chan-yuu&show_icons=true&theme=radical&count_private=true" height="150" alt="stats graph" />
  
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chan-yuu&layout=compact&theme=radical&hide=html,css,jupyter%20notebook" height="150" alt="languages graph" />
</div>

<div align="center">
  <br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chan-yuu&theme=radical&hide_border=true" alt="GitHub Streak" />
</div>

---

<div align="center">
  <p><i>"Translating Sensor Data into Intelligent Action."</i></p>
</div>
