<h1 align="center">
  🦾 努力，让世界听到RabbitRobot的声音 🤖
  <br />
  <img width="100%" src="./assets/images/hr.gif" alt="color divider" />
</h1>

<div align="center">
  <table width="68%">
    <tr>
      <td align="center" valign="middle">
        <img src="./assets/images/left.png" width="150" alt="left wing" />
      </td>
      <td align="center" valign="middle">
        <img src="./assets/images/RabbitRobot壁纸.jpg" width="200" alt="RabbitRobot logo" />
      </td>
      <td align="center" valign="middle">
        <img src="./assets/images/right.png" width="150" alt="right wing" />
      </td>
    </tr>
  </table>
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile-snake-contrib/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./profile-snake-contrib/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution snake animation" src="./profile-snake-contrib/github-contribution-grid-snake.svg" />
</picture>

---

<h1 align="center">lijinghai · RabbitRobot</h1>

<p align="center">
  <strong>控制工程 · 自动驾驶 · ROS 2 机器人系统 · 具身智能</strong>
</p>

<p align="center">
  <a href="https://lijinghai.github.io/RabbitRobot/" target="_blank">个人主页 / 项目文档</a> ·
  <a href="https://blog.csdn.net/Dorian15" target="_blank">CSDN 技术博客</a> ·
  <a href="https://space.bilibili.com/1339027047" target="_blank">B站视频记录</a> ·
  <a href="mailto:lijinghailjh@163.com">Email</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Research-%E8%87%AA%E5%8A%A8%E9%A9%BE%E9%A9%B6-2563EB?style=flat-square" alt="自动驾驶" />
  <img src="https://img.shields.io/badge/Robotics-ROS%202-111827?style=flat-square" alt="ROS 2" />
  <img src="https://img.shields.io/badge/Focus-%E5%A4%9A%E4%BC%A0%E6%84%9F%E5%99%A8%E8%9E%8D%E5%90%88-0F766E?style=flat-square" alt="多传感器融合" />
  <img src="https://img.shields.io/badge/Direction-VLN%20%2F%20Embodied%20AI-7C3AED?style=flat-square" alt="VLN and Embodied AI" />
</p>

<h1 align="center">RabbitRobot 全系列主页</h1>

<p align="center">
  这是我长期迭代的机器人项目公开入口：从 ROS 2 AMR 真车、多传感器融合 SLAM、Web 控制台，到 VLN / 具身智能导航探索。<br />
  项目路线、系统架构、实验图片、视频记录和技术文档都会持续整理在这里。
</p>

<p align="center">
  <a href="https://lijinghai.github.io/RabbitRobot/" target="_blank">
    <img src="https://img.shields.io/badge/%E8%BF%9B%E5%85%A5-RabbitRobot%20%E4%B8%BB%E9%A1%B5-0F766E?style=for-the-badge" alt="进入 RabbitRobot 主页" />
  </a>
  <br />
  <strong>访问地址：</strong>
  <a href="https://lijinghai.github.io/RabbitRobot/" target="_blank">https://lijinghai.github.io/RabbitRobot/</a>
</p>

## 关于我

你好，我是 **lijinghai**。我正在做 **RabbitRobot**：一个从 ROS 2 小车、多传感器融合到自动驾驶决策逐步长出来的开源机器人平台。

我是一名控制工程方向的硕士研究生，关注自动驾驶规划与决策、多传感器融合定位建图、VLN / 具身智能，以及真实机器人系统的工程闭环。相比只做一个 demo，我更希望把硬件、传感器、ROS 2、SLAM、导航、Web 控制和实验记录长期串起来，让项目能够持续迭代、复现和展示。

- **当前主线：** RabbitRobot AMR2 平台、Vision-Language Navigation、端到端局部规划与场景理解。
- **工程目标：** 从底盘和传感器接入开始，打通建图、导航、控制、部署和可视化记录。
- **公开入口：** 更完整的项目路线、图文资料和长期更新放在 [RabbitRobot 全系列主页](https://lijinghai.github.io/RabbitRobot/)。

## 研究方向

| 方向 | 关注问题 |
| :--- | :--- |
| 自动驾驶规划与决策 | 端到端局部规划、策略生成、轨迹优化、低附着场景鲁棒性 |
| VLN / 具身智能 | 语义目标理解、视觉/语言/动作链路、移动机器人任务执行 |
| SLAM 与定位建图 | Cartographer、FAST-LIO2、Point-LIO、RTAB-Map、多传感器融合建图 |
| 机器人系统工程 | ROS 2、Nav2、EKF、串口控制、Jetson 部署、Web 端机器人控制 |
| 边缘智能部署 | YOLO、BEV 感知、LeRobot、Docker / Nginx 服务化部署 |

## 项目经历

### RabbitRobot 全系列机器人项目

RabbitRobot 不是单一小车 demo，而是一条围绕真实机器人系统逐步展开的研发链路：AMR 承担运动平台，HandLiDAR 提供地图能力，SCFH 提供真实场景压力，Arm 扩展操作能力，Web 负责沉淀技术文档和公开展示。

| 子项目 | 定位 | 技术关键词 |
| :--- | :--- | :--- |
| **RabbitRobot_AMR2** | 轮毂伺服 AMR 真车与核心实验平台 | ROS 2, Nav2, MPPI, CAN, FAST-LIO, MID360 |
| **RabbitRobot_Coverage** | 扫地机覆盖路径规划算法 | Coverage Rect/Poly, A*, OccupancyGrid, RViz |
| **RabbitRobot_HandLiDAR** | 手持 4D LiDAR 建图工具 | Unitree L1, D435, RTAB-Map, 多传感器建图 |
| **RabbitRobot_SCFH** | 智慧鸡场净环机器人场景 | 窄通道导航, 复杂地面, 服务机器人落地 |
| **RabbitRobot_Arm** | 机械臂与具身智能实验 | LeRobot, ACT, SmolVLA, MoveIt2 |
| **RabbitRobot_ElderBuddy** | 室内陪伴机器人概念验证 | Indoor Service, HRI, companion robot |
| **RabbitRobot_Web** | 项目展示与技术文档入口 | 作品集, 技术记录, 图文资料 |

更详细的版本路线、系统架构图和实验记录请看：**[RabbitRobot 全系列主页](https://lijinghai.github.io/RabbitRobot/)**。

### RabbitRobot AMR2 / ROS 2 真车平台

目前最核心的工程平台，用于验证 ROS 2 导航、多传感器融合 SLAM、Web 控制和局部规划算法。

- **仓库：** [RabbitRobot-D435-L1lidar-RTABMap-ROS2](https://github.com/lijinghai/RabbitRobot-D435-L1lidar-RTABMap-ROS2), [ljh_robot_ros2_web](https://github.com/lijinghai/ljh_robot_ros2_web)
- **技术：** ROS 2, Nav2, LiDAR, RTAB-Map, Jetson, depth camera, Web console, autonomous navigation
- **经历：** 从机械结构、传感器接入、SLAM 建图到控制界面，尽量形成可运行、可调试、可复盘的完整闭环。
- **演示：** [RabbitRobot_V1.0 on Bilibili](https://www.bilibili.com/video/BV1zkYsziExS/?spm_id_from=333.1387.list.card_archive.click)

<div align="center">
  <a href="https://www.bilibili.com/video/BV1zkYsziExS/#reply115048936642785">
    <img src="./assets/images/RabbitRobot1.0.jpg" alt="RabbitRobot初代小车" width="78%" />
  </a>
  <br />
  <sub>RabbitRobot V1.0 · ROS 2 · multi-sensor fusion · SLAM · autonomous navigation</sub>
</div>

### VLN / 端到端局部规划探索

我希望把 RabbitRobot 从“能导航”继续推向“理解目标并完成任务”：让机器人能够结合语义目标、环境感知和运动控制，在真实场景中完成更接近任务级的导航决策。

- **数据链路：** scan、odom、tf、cmd_vel、goal_pose、local costmap、rosbag。
- **对比基线：** Nav2 / DWB / Pure Pursuit / MPC 与学习式局部规划模型。
- **评估指标：** 成功率、碰撞率、横向偏差、轨迹平滑度、恢复能力和低附着鲁棒性。
- **长期目标：** 把 VLN / 具身智能能力接入真实 AMR 平台，而不是停留在仿真或概念层。

### WarmSearch 校园失物招领系统

WarmSearch 是一个面向校园场景的失物招领系统，覆盖后端服务、Web 前端与 UniApp 移动端，是我早期完整应用系统实践之一。

- **仓库：** [WarmSearch](https://github.com/lijinghai/WarmSearch), [WarmSearch-uniapp](https://github.com/lijinghai/WarmSearch-uniapp)
- **技术：** Spring Boot, Vue, UniApp, MySQL
- **经历：** 从业务建模、接口设计到多端交互，完成一套面向真实校园使用场景的系统。

## 技术栈与能力

| 层级 | 技术 |
| :--- | :--- |
| 编程语言 | Python, C++, Java, JavaScript / TypeScript |
| 机器人系统 | ROS 2, Nav2, Autoware, UniAD, RTAB-Map, Cartographer, FAST-LIO2, Point-LIO |
| 传感器与硬件 | 3D/4D LiDAR, depth camera, IMU, UWB, Jetson, STM32 |
| AI 与感知 | YOLO, BEV perception, HuggingFace, LeRobot, VLA / VLN |
| 工程部署 | Linux, Docker, Nginx, MySQL, Vue, React, Spring Boot |

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,java,ros,docker,linux,nginx,mysql,vue,react,spring,git,qt,threejs" alt="technical stack" />
</p>

## GitHub 动态

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=lijinghai&theme=github-compact&hide_border=true" alt="GitHub activity graph" />
</p>

## Find Me

除了 GitHub，你也可以在这些平台找到 RabbitRobot 的公开更新和联系方式。

| 小红书 | 微信 | B站 |
| :---: | :---: | :---: |
| <img src="./assets/images/find-me-xiaohongshu.jpg" alt="小红书：理想主义的焊工日记" width="300" /> | <img src="./assets/images/find-me-wechat.png" alt="微信：理想主义的焊工日记" width="300" /> | <a href="https://space.bilibili.com/1339027047" target="_blank"><img src="./assets/images/find-me-bilibili.jpg" alt="B站：理想主义的焊工日记" width="300" /></a> |
| **理想主义的焊工日记**<br />小红书号：`RabbitRobot2025` | **理想主义的焊工日记**<br />扫码添加我为朋友 | **理想主义的焊工日记**<br /><a href="https://space.bilibili.com/1339027047" target="_blank">UID: 1339027047</a> |
