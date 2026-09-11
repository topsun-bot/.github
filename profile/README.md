<div align="center">

<img src="assets/logo.png" width="320" alt="TOPSUN BOT 中坚智能">

# 中坚智能 / TOPSUN-BOT

**中坚智能，让科技融入生活。**

近三十年深耕始于优化园林劳作。从植被养护到多维交互，中坚智能正把「解放双手」的命题，从地面延申至立体空间。不止是工具，更是未来生活的智能伙伴。

[TOPSUN-BOT](https://github.com/topsun-bot) 是中坚智能的开源与工程组织，沉淀世界模型与具身基础模型、智能体系统、感知定位、操作仿真与现场技能。现场工程覆盖 Unitree G1 / Go2W 二次开发、安防自主导航、机械臂集成、ROS 2 / SDK 联调与试点验收，公开入口见 [`skills`](https://github.com/topsun-bot/skills)。

<a href="https://github.com/topsun-bot">
  <img src="https://badges.strrl.dev/years/topsun-bot?style=flat-square&logo=github" alt="Years">
</a>
<a href="https://github.com/topsun-bot?tab=repositories">
  <img src="https://badges.strrl.dev/repos/topsun-bot?style=flat-square&logo=github" alt="Repos">
</a>
<a href="https://github.com/topsun-bot?tab=repositories&sort=stargazers">
  <img src="https://img.shields.io/github/stars/topsun-bot?style=flat-square&logo=github&label=TotalStars" alt="TotalStars">
</a>
<a href="https://topbot.topsunpower.cc/">
  <img src="https://img.shields.io/badge/%E5%AE%98%E7%BD%91-topbot.topsunpower.cc-d61518?style=flat-square" alt="官网">
</a>
<a href="mailto:hello@topsunpower.cc">
  <img src="https://img.shields.io/badge/%E9%82%AE%E7%AE%B1-hello%40topsunpower.cc-d61518?style=flat-square" alt="邮箱">
</a>

</div>

---

## 功能展示

官网产品画面（本地托管，避免 OSS 防盗链）。宣传片为静音循环，GitHub 无法稳定内嵌，请在 [中坚智能官网](https://topbot.topsunpower.cc/) 观看。

<table>
  <tr>
    <td align="center" width="33%" valign="top">
      <img src="assets/hero-lingrui-p1.jpg" alt="工业重载机器狗 灵睿P1" />
      <br />
      <strong>工业重载机器狗 · 灵睿 P1</strong>
      <br />
      <sub>工业巡检 · 安防协同 · 应急救援</sub>
    </td>
    <td align="center" width="33%" valign="top">
      <img src="assets/hero-goalker.jpg" alt="智能割草机器人 GOALKER H3 PRO" />
      <br />
      <strong>智能割草机器人 · GOALKER H3 PRO</strong>
      <br />
      <sub>园林智能养护 · 从地面解放双手</sub>
    </td>
    <td align="center" width="34%" valign="top">
      <img src="assets/hero-field.jpg" alt="灵睿智能机器狗现场作业" />
      <br />
      <strong>灵睿智能机器狗 · 现场作业</strong>
      <br />
      <sub>复杂环境巡检 · 立体空间延伸</sub>
    </td>
  </tr>
</table>

---

## 开源与工程仓库

公开仓库按方向归类。世界模型 / 具身基础模型置于表首。仓库名为英文代码链接，说明为中文一行。fork / 上游派生仓在说明下注明出处与致谢。

<table>
  <thead>
    <tr>
      <th align="center">方向</th>
      <th>仓库与说明</th>
      <th align="center">Stars</th>
      <th align="center">Forks</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="10" align="center"><strong>世界模型 / 具身基础模型</strong></td>
      <td>
        <a href="https://github.com/topsun-bot/wm-vla-vln-vlm-survey"><code>wm-vla-vln-vlm-survey</code></a>
        <br />
        世界模型 × VLA / VLN / VLM 综述：≥100 篇已核验论文与开源图谱（topsun-bot 自研）。
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/wm-vla-vln-vlm-survey?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/wm-vla-vln-vlm-survey?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/cosmos-predict1"><code>cosmos-predict1</code></a>
        <br />
        Cosmos-Predict1：面向 Physical AI 的通用世界基础模型集合，可微调为下游定制世界模型。
        <br />
        出处：[@nvidia-cosmos/cosmos-predict1](https://github.com/nvidia-cosmos/cosmos-predict1) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/cosmos-predict1?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/cosmos-predict1?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/dreamerv3"><code>dreamerv3</code></a>
        <br />
        DreamerV3：用世界模型掌握多样任务域。
        <br />
        出处：[@danijar/dreamerv3](https://github.com/danijar/dreamerv3) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/dreamerv3?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/dreamerv3?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/EmbodiedGen"><code>EmbodiedGen</code></a>
        <br />
        EmbodiedGen：面向具身智能的生成式三维世界引擎。
        <br />
        出处：[@HorizonRobotics/EmbodiedGen](https://github.com/HorizonRobotics/EmbodiedGen) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/EmbodiedGen?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/EmbodiedGen?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/Isaac-GR00T"><code>Isaac-GR00T</code></a>
        <br />
        NVIDIA Isaac GR00T N1.7：面向通才机器人的基础模型。
        <br />
        出处：[@NVIDIA/Isaac-GR00T](https://github.com/NVIDIA/Isaac-GR00T) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/Isaac-GR00T?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/Isaac-GR00T?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/openvla"><code>openvla</code></a>
        <br />
        OpenVLA：开源视觉-语言-动作模型，用于机器人操作。
        <br />
        出处：[@openvla/openvla](https://github.com/openvla/openvla) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/openvla?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/openvla?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/starVLA"><code>starVLA</code></a>
        <br />
        StarVLA：积木式视觉-语言-动作模型开发代码库。
        <br />
        出处：[@starVLA/starVLA](https://github.com/starVLA/starVLA) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/starVLA?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/starVLA?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/vjepa2"><code>vjepa2</code></a>
        <br />
        V-JEPA 2：从视频自监督学习的 PyTorch 代码与模型。
        <br />
        出处：[@facebookresearch/vjepa2](https://github.com/facebookresearch/vjepa2) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/vjepa2?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/vjepa2?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/NaVILA"><code>NaVILA</code></a>
        <br />
        NaVILA（RSS'25）：足式机器人视觉-语言-动作导航模型实现。
        <br />
        出处：[@AnjieCheng/NaVILA](https://github.com/AnjieCheng/NaVILA) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/NaVILA?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/NaVILA?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/diffusion_policy"><code>diffusion_policy</code></a>
        <br />
        Diffusion Policy（RSS 2023）：通过动作扩散学习视觉运动策略。
        <br />
        出处：[@real-stanford/diffusion_policy](https://github.com/real-stanford/diffusion_policy) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/diffusion_policy?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/diffusion_policy?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td rowspan="2" align="center"><strong>智能体与系统</strong></td>
      <td>
        <a href="https://github.com/topsun-bot/topsun_dimos"><code>topsun_dimos</code></a>
        <br />
        TOPSUN DimOS：面向物理空间的智能体操作系统，覆盖导航建图、感知、空间记忆与 MCP Skills；含 Unitree Go2 / G1 蓝图。
        <br />
        基于 [@dimensionalOS/dimos](https://github.com/dimensionalOS/dimos) 工作副本，致谢上游。
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/topsun_dimos?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/topsun_dimos?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/HoloAgent"><code>HoloAgent</code></a>
        <br />
        通用机器人具身智能体框架：闭环执行、三维空间记忆与可落地技能（Horizon Robotics HoloAgent 工作副本）。
        <br />
        出处：[@HorizonRobotics/HoloAgent](https://github.com/HorizonRobotics/HoloAgent) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/HoloAgent?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/HoloAgent?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td rowspan="5" align="center"><strong>感知与定位</strong></td>
      <td>
        <a href="https://github.com/topsun-bot/Elevator-LIO"><code>Elevator-LIO</code></a>
        <br />
        面向电梯非惯性运动与跨楼层定位的激光惯性里程计；可关闭电梯模式作为通用 LIO。
        <br />
        出处：[@xiaofan4122/Elevator-LIO](https://github.com/xiaofan4122/Elevator-LIO) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/Elevator-LIO?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/Elevator-LIO?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/Super-LIO"><code>Super-LIO</code></a>
        <br />
        紧凑建图策略的高效鲁棒激光惯性里程计（RA-L 2026）；本仓库跟踪 ROS 2 Humble / Iron / Jazzy。
        <br />
        出处：[@Liansheng-Wang/Super-LIO](https://github.com/Liansheng-Wang/Super-LIO) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/Super-LIO?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/Super-LIO?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/FAST-LIVO2"><code>FAST-LIVO2</code></a>
        <br />
        快速直接法激光-惯性-视觉里程计，用于退化环境实时三维重建与机载定位（T-RO 2024）。
        <br />
        出处：[@hku-mars/FAST-LIVO2](https://github.com/hku-mars/FAST-LIVO2) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/FAST-LIVO2?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/FAST-LIVO2?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/FASTLIO2_ROS2"><code>FASTLIO2_ROS2</code></a>
        <br />
        FAST-LIO2 的 ROS 2 Humble 实现，含回环位姿图优化、两阶段 ICP 重定位与一致性地图精修（BA / HBA）。
        <br />
        出处：[@liangheming/FASTLIO2_ROS2](https://github.com/liangheming/FASTLIO2_ROS2) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/FASTLIO2_ROS2?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/FASTLIO2_ROS2?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/livox_ros_driver2"><code>livox_ros_driver2</code></a>
        <br />
        Livox ROS / ROS 2 驱动（HAP、Mid-360），作为 LIO 栈的传感器前端。
        <br />
        出处：[@Livox-SDK/livox_ros_driver2](https://github.com/Livox-SDK/livox_ros_driver2) · 感谢原作者
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/livox_ros_driver2?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/livox_ros_driver2?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td rowspan="3" align="center"><strong>操作与仿真</strong></td>
      <td>
        <a href="https://github.com/topsun-bot/Panthera-HT"><code>Panthera-HT</code></a>
        <br />
        Panthera-HT 六自由度机械臂工作区：C++ / Python SDK、Host 数字孪生（Three.js + Flask）与实机控制笔记。
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/Panthera-HT?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/Panthera-HT?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/calibration"><code>calibration</code></a>
        <br />
        眼在手外自标定、YOLO 三维检测与 Unitree D1 抓取放置，支持 MuJoCo 与 RealSense。
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/calibration?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/calibration?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/topsun-bot/sim"><code>sim</code></a>
        <br />
        D1 主从臂 MCAP 物理回放（MuJoCo / Isaac Sim 5.1），用于闭环对比录制轨迹。
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/sim?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/sim?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
    <tr>
      <td align="center"><strong>现场技能</strong></td>
      <td>
        <a href="https://github.com/topsun-bot/skills"><code>skills</code></a>
        <br />
        自研机器人工程 Skills，亦为现场工程公开技术入口：宇树 G1 / Go2W 预检、安防巡检验收与相关现场流程。
      </td>
      <td align="center"><img alt="Stars" src="https://img.shields.io/github/stars/topsun-bot/skills?style=flat-square&cacheSeconds=86400" /></td>
      <td align="center"><img alt="Forks" src="https://img.shields.io/github/forks/topsun-bot/skills?style=flat-square&cacheSeconds=86400" /></td>
    </tr>
  </tbody>
</table>

**同方向公开仓**（表内为核心栈；下列为同方向跟踪仓，说明取自各仓 GitHub description）

- [`IsaacLab`](https://github.com/topsun-bot/IsaacLab) — 基于 NVIDIA Isaac Sim 的机器人学习统一框架。<br />出处：[@isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab) · 感谢原作者
- [`ijepa`](https://github.com/topsun-bot/ijepa) — I-JEPA：基于图像的联合嵌入预测架构官方代码（CVPR）。<br />出处：[@facebookresearch/ijepa](https://github.com/facebookresearch/ijepa) · 感谢原作者
- [`VLN-CE`](https://github.com/topsun-bot/VLN-CE) — 基于 Habitat 的连续环境视觉-语言导航。<br />出处：[@jacobkrantz/VLN-CE](https://github.com/jacobkrantz/VLN-CE) · 感谢原作者
- [`habitat-lab`](https://github.com/topsun-bot/habitat-lab) — 在多种任务与环境中训练具身智能体的模块化高层库。<br />出处：[@facebookresearch/habitat-lab](https://github.com/facebookresearch/habitat-lab) · 感谢原作者
- [`octo`](https://github.com/topsun-bot/octo) — 基于 Transformer 的机器人策略，在约 80 万条多样化机器人轨迹上训练。<br />出处：[@octo-models/octo](https://github.com/octo-models/octo) · 感谢原作者
- [`LIBERO`](https://github.com/topsun-bot/LIBERO) — 终身机器人学习中的知识迁移评测。<br />出处：[@Lifelong-Robot-Learning/LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO) · 感谢原作者
- [`SimplerEnv`](https://github.com/topsun-bot/SimplerEnv) — 在统一仿真设定下评测并复现真实世界机器人操作策略（如 RT-1、Octo）（CoRL 2024）。<br />出处：[@simpler-env/SimplerEnv](https://github.com/simpler-env/SimplerEnv) · 感谢原作者
- [`VILA`](https://github.com/topsun-bot/VILA) — 面向边缘、数据中心与云端多模态任务的视觉语言模型家族。<br />出处：[@NVlabs/VILA](https://github.com/NVlabs/VILA) · 感谢原作者
- [`prismatic-vlms`](https://github.com/topsun-bot/prismatic-vlms) — 训练视觉条件语言模型的灵活高效代码库。<br />出处：[@TRI-ML/prismatic-vlms](https://github.com/TRI-ML/prismatic-vlms) · 感谢原作者

未列入：空的 LeRobot 镜像（出处：[@Seeed-Projects/lerobot](https://github.com/Seeed-Projects/lerobot)），以及与具身产品无直接关系的工具仓。

---

## 内部 / 私有仓库

精选产品与工程仓（非全部内部仓）。组织成员可见；公开访客打开会 404，属预期行为。说明来自组织清单中的已有描述；无描述处仅按仓库名作一行标注，不杜撰指标或认证。

<table>
  <thead>
    <tr>
      <th align="center">方向</th>
      <th>仓库</th>
      <th align="center">可见性</th>
      <th>说明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="6" align="center"><strong>运控与本体</strong></td>
      <td><a href="https://github.com/topsun-bot/G1-LocoForge"><code>G1-LocoForge</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>G1 RL → 真机运控</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/unitreeg1_98"><code>unitreeg1_98</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>G1 训练</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/b2"><code>b2</code></a></td>
      <td align="center"><img alt="私有" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E7%A7%81%E6%9C%89-6b7280?style=flat-square" /></td>
      <td>B2 安全门控 SDK</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/robot-deploy"><code>robot-deploy</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>D1 推理与硬件栈</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/Robot-Brain"><code>Robot-Brain</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>机器人大脑相关内部仓</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/topsun-robot-service"><code>topsun-robot-service</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>机器人业务服务内部仓</td>
    </tr>
    <tr>
      <td rowspan="9" align="center"><strong>导航巡检</strong></td>
      <td><a href="https://github.com/topsun-bot/Navigation"><code>Navigation</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>导航工程内部仓</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/go2w-security-patrol"><code>go2w-security-patrol</code></a></td>
      <td align="center"><img alt="私有" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E7%A7%81%E6%9C%89-6b7280?style=flat-square" /></td>
      <td>Go2W 安防巡检</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/go2w-health-monitor"><code>go2w-health-monitor</code></a></td>
      <td align="center"><img alt="私有" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E7%A7%81%E6%9C%89-6b7280?style=flat-square" /></td>
      <td>Go2W 健康监测</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/go2w-mcap-recorder"><code>go2w-mcap-recorder</code></a></td>
      <td align="center"><img alt="私有" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E7%A7%81%E6%9C%89-6b7280?style=flat-square" /></td>
      <td>Go2W MCAP 录制</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/Unitree-go2-Navi"><code>Unitree-go2-Navi</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>Go2 导航</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/nav3d"><code>nav3d</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>三维导航</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/spatial-mind"><code>spatial-mind</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>空间理解 / 感知相关</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/s11_robot_perception"><code>s11_robot_perception</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>机器人感知</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/topsun_mower"><code>topsun_mower</code></a> · <a href="https://github.com/topsun-bot/Mower"><code>Mower</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>割草二次开发</td>
    </tr>
    <tr>
      <td rowspan="6" align="center"><strong>操作与遥操作</strong></td>
      <td><a href="https://github.com/topsun-bot/Sight2Act"><code>Sight2Act</code></a></td>
      <td align="center"><img alt="私有" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E7%A7%81%E6%9C%89-6b7280?style=flat-square" /></td>
      <td>看到执行·人形具身</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/rml63_ac2_grasp"><code>rml63_ac2_grasp</code></a></td>
      <td align="center"><img alt="私有" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E7%A7%81%E6%9C%89-6b7280?style=flat-square" /></td>
      <td>RML63 + AC2 + D455 安全门控抓取</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/dual-arm-workcell"><code>dual-arm-workcell</code></a></td>
      <td align="center"><img alt="私有" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E7%A7%81%E6%9C%89-6b7280?style=flat-square" /></td>
      <td>D1 双臂工作台</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/x-arm-teleop"><code>x-arm-teleop</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>机械臂遥操作</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/arcore-telepose"><code>arcore-telepose</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>ARCore 遥操作位姿</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/vr_controller"><code>vr_controller</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>VR 控制器遥操作</td>
    </tr>
    <tr>
      <td rowspan="5" align="center"><strong>Agent 与平台</strong></td>
      <td><a href="https://github.com/topsun-bot/NervAgent"><code>NervAgent</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>统一神经控制层</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/nervagent-adk-live"><code>nervagent-adk-live</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>NervAgent 在线 ADK</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/Autonomous-Lab"><code>Autonomous-Lab</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>多 Agent 研发编排</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/Agent_eval_paltform"><code>Agent_eval_paltform</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>Agent 评测平台</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/topsun_robot_eval_ws"><code>topsun_robot_eval_ws</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>机器人评测工作区</td>
    </tr>
    <tr>
      <td rowspan="6" align="center"><strong>数据与工具</strong></td>
      <td><a href="https://github.com/topsun-bot/ros2_hzj"><code>ros2_hzj</code></a></td>
      <td align="center"><img alt="私有" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E7%A7%81%E6%9C%89-6b7280?style=flat-square" /></td>
      <td>ROS 2 / DDS 工作流（桦之坚）</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/human_robotics"><code>human_robotics</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>人机 / 人形相关内部仓</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/robot-data-collector"><code>robot-data-collector</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>机器人数据采集</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/data_platform"><code>data_platform</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>数据平台</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/openpi"><code>openpi</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>OpenPI 相关内部仓</td>
    </tr>
    <tr>
      <td><a href="https://github.com/topsun-bot/magnetar-ax-deploy"><code>magnetar-ax-deploy</code></a></td>
      <td align="center"><img alt="内部" src="https://img.shields.io/badge/%E5%8F%AF%E8%A7%81%E6%80%A7-%E5%86%85%E9%83%A8-4b5563?style=flat-square" /></td>
      <td>Magnetar 部署相关</td>
    </tr>
  </tbody>
</table>

---

## 致谢 / 开源出处

引用、fork 他人项目时注明出处并致谢原作者。上表各 fork / 工作副本行已内联出处；上游链接如下（一次列出便于查阅）：

- [`topsun_dimos`](https://github.com/topsun-bot/topsun_dimos) ← [@dimensionalOS/dimos](https://github.com/dimensionalOS/dimos)
- [`HoloAgent`](https://github.com/topsun-bot/HoloAgent) ← [@HorizonRobotics/HoloAgent](https://github.com/HorizonRobotics/HoloAgent)
- [`Elevator-LIO`](https://github.com/topsun-bot/Elevator-LIO) ← [@xiaofan4122/Elevator-LIO](https://github.com/xiaofan4122/Elevator-LIO)
- [`Super-LIO`](https://github.com/topsun-bot/Super-LIO) ← [@Liansheng-Wang/Super-LIO](https://github.com/Liansheng-Wang/Super-LIO)
- [`FAST-LIVO2`](https://github.com/topsun-bot/FAST-LIVO2) ← [@hku-mars/FAST-LIVO2](https://github.com/hku-mars/FAST-LIVO2)
- [`FASTLIO2_ROS2`](https://github.com/topsun-bot/FASTLIO2_ROS2) ← [@liangheming/FASTLIO2_ROS2](https://github.com/liangheming/FASTLIO2_ROS2)
- [`livox_ros_driver2`](https://github.com/topsun-bot/livox_ros_driver2) ← [@Livox-SDK/livox_ros_driver2](https://github.com/Livox-SDK/livox_ros_driver2)
- [`cosmos-predict1`](https://github.com/topsun-bot/cosmos-predict1) ← [@nvidia-cosmos/cosmos-predict1](https://github.com/nvidia-cosmos/cosmos-predict1)
- [`dreamerv3`](https://github.com/topsun-bot/dreamerv3) ← [@danijar/dreamerv3](https://github.com/danijar/dreamerv3)
- [`EmbodiedGen`](https://github.com/topsun-bot/EmbodiedGen) ← [@HorizonRobotics/EmbodiedGen](https://github.com/HorizonRobotics/EmbodiedGen)
- [`Isaac-GR00T`](https://github.com/topsun-bot/Isaac-GR00T) ← [@NVIDIA/Isaac-GR00T](https://github.com/NVIDIA/Isaac-GR00T)
- [`IsaacLab`](https://github.com/topsun-bot/IsaacLab) ← [@isaac-sim/IsaacLab](https://github.com/isaac-sim/IsaacLab)
- [`openvla`](https://github.com/topsun-bot/openvla) ← [@openvla/openvla](https://github.com/openvla/openvla)
- [`starVLA`](https://github.com/topsun-bot/starVLA) ← [@starVLA/starVLA](https://github.com/starVLA/starVLA)
- [`vjepa2`](https://github.com/topsun-bot/vjepa2) ← [@facebookresearch/vjepa2](https://github.com/facebookresearch/vjepa2)
- [`ijepa`](https://github.com/topsun-bot/ijepa) ← [@facebookresearch/ijepa](https://github.com/facebookresearch/ijepa)
- [`NaVILA`](https://github.com/topsun-bot/NaVILA) ← [@AnjieCheng/NaVILA](https://github.com/AnjieCheng/NaVILA)
- [`VLN-CE`](https://github.com/topsun-bot/VLN-CE) ← [@jacobkrantz/VLN-CE](https://github.com/jacobkrantz/VLN-CE)
- [`habitat-lab`](https://github.com/topsun-bot/habitat-lab) ← [@facebookresearch/habitat-lab](https://github.com/facebookresearch/habitat-lab)
- [`diffusion_policy`](https://github.com/topsun-bot/diffusion_policy) ← [@real-stanford/diffusion_policy](https://github.com/real-stanford/diffusion_policy)
- [`octo`](https://github.com/topsun-bot/octo) ← [@octo-models/octo](https://github.com/octo-models/octo)
- [`LIBERO`](https://github.com/topsun-bot/LIBERO) ← [@Lifelong-Robot-Learning/LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)
- [`SimplerEnv`](https://github.com/topsun-bot/SimplerEnv) ← [@simpler-env/SimplerEnv](https://github.com/simpler-env/SimplerEnv)
- [`VILA`](https://github.com/topsun-bot/VILA) ← [@NVlabs/VILA](https://github.com/NVlabs/VILA)
- [`prismatic-vlms`](https://github.com/topsun-bot/prismatic-vlms) ← [@TRI-ML/prismatic-vlms](https://github.com/TRI-ML/prismatic-vlms)
- `lerobot` / `lerobot-1`（未列入上表）← [@Seeed-Projects/lerobot](https://github.com/Seeed-Projects/lerobot)

---

<div align="center">

[官网](https://topbot.topsunpower.cc/) · [邮箱 hello@topsunpower.cc](mailto:hello@topsunpower.cc) · [GitHub](https://github.com/topsun-bot)

现场 Skills 含独立集成、预检与验收方法，**不属于宇树 / Unitree 官方支持或官方认证**；演示、离线检查或文档证据不表述为量产、客户案例或真机验收。

</div>
