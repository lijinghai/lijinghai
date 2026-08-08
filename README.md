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

RabbitRobot 不是单一小车 demo，而是一条围绕真实机器人系统逐步展开的研发链路：我把底盘、传感器、地图、覆盖算法、Web 控制台和 VLN 研究主线放在同一个工程闭环里做，让每个子项目都能为下一轮真车实验提供数据、工具或执行能力。

<p align="center">
  <a href="https://lijinghai.github.io/RabbitRobot/" target="_blank">
    <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/RabbitRobot_architecture.png" alt="RabbitRobot 系统架构图" width="92%" />
  </a>
  <br />
  <sub>RabbitRobot 全系列主页：真实 AMR 平台、覆盖路径、建图工具、Web 控制台和 VLN 研究闭环。</sub>
</p>

| 子项目 | 公开入口 | 难点与创新点 |
| :--- | :--- | :--- |
| **RabbitRobot_AMR2** | [真车平台](https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-amr2.html) | 轮毂伺服差速底盘、MID360、Fast-LIO、ICP、Nav2 MPPI、DS20270C CAN 和安全链路的一体化真车系统 |
| **RabbitRobot_CoveragePath** | [覆盖算法](https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-coverage.html) | 在真实 PCD 地图上做 map-aware 覆盖规划，处理 footprint 膨胀、unknown/off-map 裁剪、holes、连通分块与 A* 过渡 |
| **RabbitRobot_ROS2_Web** | [Web 控制台](https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-ros2-web.html) | 把 ROS/ROS2 地图、导航、状态监控、3D 机器人模型和覆盖地图调试搬进浏览器 |
| **RabbitRobot_HandLiDAR / D435_L1_RTABMap** | [建图工具](https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-handlidar.html) | 用 Unitree L1、D435、MPU6050、RTAB-Map / FAST-LIO2 做多传感器地图生产与导航验证 |
| **RabbitRobot_Sweeper / SCFH** | [扫地机原型](https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-sweeper-v1.html) | 把覆盖算法放进清扫/消毒任务语境，面向窄通道、复杂地面和真实服务机器人落地 |
| **RabbitRobot_VLN / Arm / ElderBuddy** | [VLN 主线](https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-vln.html) | 把语言目标、视觉/地图 grounding、waypoint 规划、移动执行和后续操作能力连成长期研究路线 |

#### RabbitRobot_AMR2：轮毂伺服 AMR 真车执行平台

<table>
  <tr>
    <td width="46%">
      <a href="https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-amr2.html" target="_blank">
        <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/amr2_coverage_web_console.gif" alt="AMR2 Web 3D coverage console" width="100%" />
      </a>
      <br />
      <sub>AMR2 Web 3D 覆盖控制台：真车模型、地图、路径和状态集中展示。</sub>
    </td>
    <td width="54%">
      <strong>项目定位：</strong> 当前 RabbitRobot 最核心的真车底座，用来承接 SLAM、Nav2、覆盖路径和 VLN waypoint 的真实执行。<br /><br />
      <strong>工程难度：</strong>
      <ul>
        <li>把 MID360 激光/IMU、Fast-LIO 里程计、ICP 地图对齐、Nav2 MPPI、速度平滑、碰撞监控和 DS20270C CAN 底盘驱动串成同一条闭环。</li>
        <li>轮毂伺服差速底盘不是玩具车接口，需要处理真实车体 footprint、速度限制、加减速约束、急停和传感器异常。</li>
        <li>系统不是只跑一帧截图，而是面向 rosbag 回放、调参、复现实验和后续真实任务执行。</li>
      </ul>
      <strong>创新点：</strong> 把 VLN / VLM 生成的语义 waypoint 下沉到真实 AMR 的导航安全链路，让语言任务不只停在仿真层，而是能进入可验证的真车执行层。
    </td>
  </tr>
</table>

#### RabbitRobot_CoveragePath：真实地图约束下的覆盖路径算法

<table>
  <tr>
    <td width="46%">
      <a href="https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-coverage.html" target="_blank">
        <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/coverage_step_generated_path.png" alt="Coverage path generated on PCD 2D map" width="100%" />
      </a>
      <br />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/coverage_step_known_free_clip.png" alt="Coverage path clipped to known free cells" width="49%" />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/coverage_step_following_path.png" alt="RViz fake car follows coverage path" width="49%" />
      <br />
      <sub>RViz 区域输入、known-free 裁剪、覆盖路径生成和仿真跟随验证。</sub>
    </td>
    <td width="54%">
      <strong>项目定位：</strong> 为扫地机、鸡舍净环机器人和 AMR 区域作业准备的覆盖规划能力。<br /><br />
      <strong>工程难度：</strong>
      <ul>
        <li>不是几何蛇形线：算法订阅 <code>/map</code>，只在真实 PCD 转出的 known-free OccupancyGrid 中规划。</li>
        <li>按 AMR2 <code>0.486 m × 0.450 m</code> footprint 和 safety margin 膨胀障碍，unknown、off-map、occupied cells 会被扣除。</li>
        <li>支持 RViz <code>Coverage Rect</code> 拖矩形、<code>Coverage Poly</code> 点多边形、polygon holes、连通分块和 A* 过渡连接。</li>
      </ul>
      <strong>创新点：</strong> 把“鼠标圈一个要清扫的区域”变成可复用的 ROS2 覆盖路径服务，输出 <code>/coverage_path</code>，后续可接 Nav2 执行器，同时保留真车安全链路。
    </td>
  </tr>
</table>

#### RabbitRobot_ROS2_Web：浏览器里的机器人操作台

<table>
  <tr>
    <td width="46%">
      <a href="https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-ros2-web.html" target="_blank">
        <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/ros2_web_home.png" alt="RabbitRobot ROS2 Web console" width="100%" />
      </a>
      <br />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/amr2_coverage_3d_panel.png" alt="AMR2 3D coverage panel" width="49%" />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/ros2_web_single_nav.png" alt="ROS2 Web single goal navigation" width="49%" />
      <br />
      <sub>Web 控制台把地图、导航、3D 状态、覆盖区域和系统日志放在一个界面里。</sub>
    </td>
    <td width="54%">
      <strong>项目定位：</strong> RabbitRobot 的 Web cockpit，用于降低 ROS 调试门槛，也用于项目展示和远程演示。<br /><br />
      <strong>工程难度：</strong>
      <ul>
        <li>前端要同时处理地图图层、导航目标、机器人状态、日志、覆盖区域编辑和 3D STL 模型显示。</li>
        <li>后端需要和 rosbridge、WSL、Vite、ROS2 topic/service 协同，解决连接失败、端口代理、启动恢复等真实环境问题。</li>
        <li>界面不是静态网页，而是服务于真车调试、覆盖地图验证和工程复盘的操作台。</li>
      </ul>
      <strong>创新点：</strong> 把传统 RViz/命令行调试经验迁移到浏览器，让非 ROS 背景的人也能看懂机器人正在看什么、准备去哪、为什么停下。
    </td>
  </tr>
</table>

#### RabbitRobot_HandLiDAR / D435_L1_RTABMap：多传感器地图生产链路

<table>
  <tr>
    <td width="46%">
      <a href="https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-d435-l1-rtabmap.html" target="_blank">
        <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/rtabmap_overview.png" alt="D435 L1 RTABMap overview" width="100%" />
      </a>
      <br />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/hand_lidar_prototype.jpg" alt="HandLiDAR prototype" width="49%" />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/rtabmap_rviz_pointcloud.png" alt="RTAB-Map RViz pointcloud" width="49%" />
      <br />
      <sub>手持建图仪与 D435 + Unitree L1 + RTAB-Map / FAST-LIO2 多传感器建图链路。</sub>
    </td>
    <td width="54%">
      <strong>项目定位：</strong> 为 AMR 导航、覆盖规划和场景实验提供地图与传感器数据来源。<br /><br />
      <strong>工程难度：</strong>
      <ul>
        <li>D435、Unitree L1、MPU6050 和 Jetson/ROS2 需要在时间戳、坐标系、驱动、启动顺序和 RViz 可视化上保持一致。</li>
        <li>D435 非 D435i，没有内置 IMU，因此额外接入 MPU6050 来补足姿态约束，服务于视觉/惯性/激光融合建图。</li>
        <li>手持建图不是固定底盘采集，运动扰动更大，对传感器安装、轨迹稳定性和后处理更敏感。</li>
      </ul>
      <strong>创新点：</strong> 把“先有高质量地图”作为机器人系统能力的一部分单独做出来，让 AMR 不依赖单一场地或单一传感器配置。
    </td>
  </tr>
</table>

#### RabbitRobot_Sweeper / SCFH：面向真实清扫场景的机器人原型

<table>
  <tr>
    <td width="46%">
      <a href="https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-sweeper-v1.html" target="_blank">
        <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/sweeper_v1.jpg" alt="RabbitRobot Sweeper V1.0" width="100%" />
      </a>
      <br />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/coverage_step_poly_path.png" alt="Coverage Poly path for cleaning area" width="49%" />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/coverage_manual_follow_trace.png" alt="Coverage path follow trace" width="49%" />
      <br />
      <sub>扫地机原型、区域覆盖路径和 RViz-only 跟随轨迹，为后续真实清扫任务做准备。</sub>
    </td>
    <td width="54%">
      <strong>项目定位：</strong> 把 AMR 能力落到清扫/消毒这种有明确作业面积和覆盖率要求的服务任务。<br /><br />
      <strong>工程难度：</strong>
      <ul>
        <li>清扫机器人不仅要能导航，还要考虑作业宽度、边界安全距离、遗漏区域、障碍孔洞和低速稳定执行。</li>
        <li>鸡舍/窄通道场景对地面、障碍、通道宽度和维护成本更敏感，不能只用办公室导航 demo 的标准来判断。</li>
        <li>硬件原型涉及底盘结构、供电、清扫机构、传感器安装和后续 ROS2 接入，机械和软件要一起迭代。</li>
      </ul>
      <strong>创新点：</strong> 用真实服务场景倒逼覆盖规划、地图生产和 Web 调试工具，让算法不是孤立存在，而是服务于实际机器人作业闭环。
    </td>
  </tr>
</table>

#### RabbitRobot_VLN：从“能导航”走向“听懂任务”

<table>
  <tr>
    <td width="46%">
      <a href="https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-vln.html" target="_blank">
        <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/amr2_web_navigation.jpg" alt="AMR2 Web navigation for VLN" width="100%" />
      </a>
      <br />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/amr2_single_goal.jpg" alt="AMR2 single goal navigation" width="49%" />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/RabbitRobot_architecture.png" alt="RabbitRobot architecture for VLN" width="49%" />
      <br />
      <sub>以 AMR2 为执行层，把语言任务、地图区域、视觉观测和 waypoint 评估接到真实机器人上。</sub>
    </td>
    <td width="54%">
      <strong>项目定位：</strong> 当前长期研究主线，让 RabbitRobot 从“能跑导航”升级到“能理解语义目标并完成任务”。<br /><br />
      <strong>工程难度：</strong>
      <ul>
        <li>VLN 不只是模型调用，需要把语言目标 grounding 到地图、视觉观测、局部目标、导航状态和失败恢复策略。</li>
        <li>真车评估要记录 scan、odom、tf、cmd_vel、goal_pose、local costmap 和 rosbag，才能比较成功率、碰撞率、轨迹效率和恢复能力。</li>
        <li>需要先跑稳 Nav2 baseline，再比较学习式策略，否则很难判断模型到底带来了什么提升。</li>
      </ul>
      <strong>创新点：</strong> 用真实 AMR 系统给 VLN 提供落地接口和评价闭环，把“语言理解”变成可以被路径、轨迹和安全指标检验的机器人能力。
    </td>
  </tr>
</table>

#### 扩展方向：AMR 底盘、机械臂与室内服务机器人

<table>
  <tr>
    <td width="46%">
      <a href="https://lijinghai.github.io/RabbitRobot/projects/rabbitrobot-amr.html" target="_blank">
        <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/omni_car_lab_pair.jpg" alt="RabbitRobot AMR prototypes" width="100%" />
      </a>
      <br />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/aloha_act.gif" alt="RabbitRobot Arm LeRobot ACT demo" width="49%" />
      <img src="https://lijinghai.github.io/RabbitRobot/images/rabbitrobot/omni_car_compact.jpg" alt="RabbitRobot ElderBuddy compact AMR concept" width="49%" />
      <br />
      <sub>移动底盘、机械臂学习式控制和室内服务机器人，是 RabbitRobot 后续从移动到移动操作的扩展方向。</sub>
    </td>
    <td width="54%">
      <strong>项目定位：</strong> 这些项目用于拓展 RabbitRobot 的形态边界：从差速/全向移动平台，到机械臂操作，再到室内陪伴与服务概念。<br /><br />
      <strong>工程难度：</strong>
      <ul>
        <li>底盘侧要验证不同轮系、载荷、传感器安装和控制接口对 ROS2/Nav2 的影响。</li>
        <li>机械臂侧关注 LeRobot、ACT、SmolVLA、MoveIt2 等学习式操作与传统运动规划如何对接。</li>
        <li>室内服务机器人需要把导航、交互、任务提醒和安全边界组合成面向人的产品体验。</li>
      </ul>
      <strong>创新点：</strong> RabbitRobot 不是只做一台车，而是在搭一组可复用的机器人能力库：移动、建图、覆盖、Web 可视化、语义导航和操作能力可以逐步组合。
    </td>
  </tr>
</table>

更详细的版本路线、系统架构图和实验记录请看：**[RabbitRobot 全系列主页](https://lijinghai.github.io/RabbitRobot/)**。
演示视频：**[RabbitRobot_V1.0 on Bilibili](https://www.bilibili.com/video/BV1zkYsziExS/?spm_id_from=333.1387.list.card_archive.click)**。
相关仓库：[RabbitRobot-D435-L1lidar-RTABMap-ROS2](https://github.com/lijinghai/RabbitRobot-D435-L1lidar-RTABMap-ROS2) · [RabbitRobot-JetsonOrinSuper_MPU6050-ROS2](https://github.com/lijinghai/RabbitRobot-JetsonOrinSuper_MPU6050-ROS2) · [ljh_robot_ros2_web](https://github.com/lijinghai/ljh_robot_ros2_web)

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
