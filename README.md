## Hi there 👋

<!--
**chan-yuu/chan-yuu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<div align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="300" height="auto"/>
  <h1>Hi there, I'm [Chen Yun] 👋</h1>
  <h3>🚀 Robotics Software Engineer | 🤖 RL Researcher</h3>
  
  <p>
    专注由于 <b>ROS 2</b>, <b>Sim2Real 强化学习</b>, 以及 <b>多传感器融合 SLAM</b>.
    <br>
    目前致力于解决非结构化环境下的复杂机器人操作与导航问题。
  </p>

  <p>
    <a href="mailto:your_email@example.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
    <a href="https://linkedin.com/in/your-profile">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="https://your-blog-website.com">
      <img src="https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=About.me&logoColor=white" />
    </a>
  </p>
</div>

---

### 🛠️ Tech Stack & Tools

<div align="center">

| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![Shell](https://img.shields.io/badge/shell_script-%23121011.svg?style=flat&logo=gnu-bash&logoColor=white) |
| **Robotics** | ![ROS](https://img.shields.io/badge/ROS-22314E?style=flat&logo=ros&logoColor=white) ![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white) ![Gazebo](https://img.shields.io/badge/Gazebo-orange?style=flat) ![PCL](https://img.shields.io/badge/PCL-Point_Cloud_Library-blue?style=flat) |
| **AI & RL** | ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white) ![Gymnasium](https://img.shields.io/badge/Gymnasium-black?style=flat) ![Stable Baselines3](https://img.shields.io/badge/Stable_Baselines3-32CD32?style=flat) |
| **Algorithms** | **SLAM (LIO-SAM, FAST-LIO)**, **Path Planning (A*, Hybrid A*)**, **Control (MPC, PID)** |
| **Tools** | ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=flat&logo=cmake&logoColor=white) |

</div>

---

### 🔭 Featured Projects

#### 1. Autonomous Forklift with Hierarchical RL (HRL)
> *基于分层强化学习的自主叉车导航与操作*
* **Description**: 针对长序列任务（导航 -> 叉取 -> 放置）开发的自主叉车系统。
* **Tech**: ROS 2 (Humble), Gazebo, PyTorch, PPO, Behavior Trees.
* **Highlights**:
    * 设计了基于 HRL 的分层决策架构，解决了稀疏奖励问题。
    * 在 Gazebo 中搭建了高保真仿真环境，实现了 Sim2Real 的无缝迁移。
    * 集成 `nav2` 进行全局路径规划，利用 RL 进行局部避障和精准操作。
* [🔗 View Code](#) *(这里放你的项目链接，如果是私有的可以放演示GIF)*

#### 2. Robust Lidar-Inertial SLAM System
> *基于 LIO-SAM 的多传感器融合建图系统适配*
* **Description**: 针对 Robosense (速腾) 雷达与 9轴 IMU 的紧耦合 SLAM 系统。
* **Tech**: C++, ROS, GTSAM, PCL, Ceres Solver.
* **Highlights**:
    * 解决了 Robosense 雷达时间戳同步与去畸变（Deskewing）问题。
    * 实现了基于 `FAST-LIO2` 的在线外参自动标定功能。
    * 优化了因子图结构，解决了剧烈运动下的重力对齐失效问题。
* [🔗 View Code](#)

#### 3. RL Training Environment for Mobile Manipulation
> *基于 Gymnasium 与 ROS 2 的强化学习训练环境*
* **Description**: 一个用于移动操作机器人（Mobile Manipulator）的标准化 RL 接口。
* **Tech**: Python, Gymnasium, ROS 2, MetaDrive.
* **Highlights**:
    * 封装了 ROS 2 的 Topic/Service 通信，提供标准的 `step()` 和 `reset()` 接口。
    * 支持多进程并行训练，大幅缩短训练时间。

---

### 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chan-yuu&show_icons=true&theme=radical" height="150" alt="stats graph" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chan-yuu&layout=compact&theme=radical" height="150" alt="languages graph" />
</div>

---

<div align="center">
  <p><i>"Simulation is the doom of AI, but also its only hope."</i></p>
</div>
