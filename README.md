<!-- Profile Banner (optional) -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=100&text=Harshith%20Kumar%20Malkapuram%20Bheemesh%20Kumar&fontAlign=50&fontSize=28&desc=Robotics%20%7C%20Underwater%20AUVs%20%7C%20Aerial%20UAVs%20%7C%20RL%20%26%20Motion%20Planning&descAlign=50&color=0:0f172a,100:1f2937&fontColor=ffffff&descAlignY=70" alt="Banner"/>
</p>

<p align="center">
  <a href="https://YOUR_LINKEDIN"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white"></a>
  <a href="mailto:harshithkmr773@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-harshithkmr773%40gmail.com-8B5CF6"></a>
  <a href="https://YOUR_SCHOLAR"><img alt="Google Scholar" src="https://img.shields.io/badge/Google%20Scholar-4285F4?logo=googlescholar&logoColor=white"></a>
  <img alt="Visitors" src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&style=flat&color=orange">
</p>

---

# TL;DR

- **Robotics Engineer** focused on **AUV/UAV autonomy**, **RL motion planning**, **GPS-denied inspection**.  
- I ship **research → code → demos**: ROS2 stacks, planners (PPO/TD3/RRT/A*), perception (YOLOv8), control (PID/MPC).  
- Hunting for **PhD** (underwater robotics / planning) & **applied autonomy roles**.

<p align="center">
  <a href="#-featured-demos" target="_self"><img src="https://img.shields.io/badge/Skip_to_Demos-111827?style=for-the-badge"></a>
  <a href="#-projects" target="_self"><img src="https://img.shields.io/badge/Projects-111827?style=for-the-badge"></a>
  <a href="#-publications" target="_self"><img src="https://img.shields.io/badge/Publications-111827?style=for-the-badge"></a>
  <a href="#-contact" target="_self"><img src="https://img.shields.io/badge/Contact-111827?style=for-the-badge"></a>
</p>

---

## 🧭 Quick Navigation

- 🔎 **Portfolio site**: https://YOUR_GITHUB_USERNAME.github.io  
- 📂 **Pinned repos**: see bottom  
- 🧪 **Live notebooks / demos**: linked per project  
- 📰 **Scholar**: https://YOUR_SCHOLAR  

---

## ⚙️ Tech Stack (hover to scan, expand to detail)

<p align="left">
  <img title="ROS2 Humble" src="https://img.shields.io/badge/ROS2-Humble-22314E?logo=ros&logoColor=white"/>
  <img title="Gazebo" src="https://img.shields.io/badge/Gazebo-Sim-FF6B6B"/>
  <img title="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white"/>
  <img title="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"/>
  <img title="C/C++" src="https://img.shields.io/badge/C/C%2B%2B-00599C?logo=c%2B%2B&logoColor=white"/>
  <img title="YOLOv8" src="https://img.shields.io/badge/YOLOv8-000000"/>
  <img title="OpenCV" src="https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white"/>
  <img title="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white"/>
  <img title="Linux" src="https://img.shields.io/badge/Linux-000000?logo=linux&logoColor=white"/>
  <img title="MATLAB/Simulink" src="https://img.shields.io/badge/MATLAB/Simulink-FF8C00"/>
</p>

<details>
  <summary><b>🧩 Detailed competency map</b></summary>

**Planning:** PPO, TD3, GAIL, RRT/Smooth-RRT, A*, trajectory optimization, differential flatness  
**Control:** PID, cascaded loops, gain scheduling, MPC (tracking & constraints)  
**Perception:** YOLOv8 detection, point-cloud basics, stereo/mono pipelines  
**Systems:** ROS2 nodes, DDS configs, TF trees, bagging, Gazebo worlds, CI on robot code  
**Comms/IO:** UART, I²C, SPI, CAN, Ethernet  
**Tooling:** Git, Docker, LaTeX, VSCode devcontainers
</details>

---

## 🎥 Featured Demos

> Click to watch. If you show screenshots instead of motion, that’s on you.

<table>
<tr>
<td align="center">
  <a href="https://LINK_TO_AUV_VIDEO">
    <img src="https://PLACEHOLDER_AUV_GIF" width="420" alt="AUV RL Navigation Demo">
  </a>
  <br/><sub>AUV RL Navigation — PPO + GST with obstacle/wreckage awareness</sub>
</td>
<td align="center">
  <a href="https://LINK_TO_UAV_VIDEO">
    <img src="https://PLACEHOLDER_UAV_GIF" width="420" alt="UAV Inspection in GPS-denied Space">
  </a>
  <br/><sub>Asymmetric UAV for GPS-denied inspection — planning + control</sub>
</td>
</tr>
</table>

---

## 🚀 Projects

> Show, don’t tell. Each card links to code + a 30–90s demo.

### 1) RL-Based 3D AUV Navigation
**Stack:** ROS2, PyTorch, PPO, GST, Gazebo  
**Pitch:** Policy learns safe 3D navigation with wreckage detection.  
**Links:** [Repo](https://github.com/YOUR_GITHUB_USERNAME/auv-rl-3d) • [Demo](https://LINK_TO_AUV_VIDEO) • [Paper/Preprint](https://LINK_TO_PDF)
<details>
  <summary><b>What’s inside?</b></summary>
  - Observation fusion (range, IMU, detections) → policy  
  - Reward shaping for stability, collision slack, valve proximity  
  - Domain randomization for currents + noise  
  - Eval: success rate, path smoothness, intervention count
</details>

---

### 2) RL-Driven Valve Control for Oyster Cultivation
**Stack:** ROS2, PyTorch, TD3, Gazebo  
**Pitch:** Vision-conditioned manipulation policy for aquaculture valves.  
**Links:** [Repo](https://github.com/YOUR_GITHUB_USERNAME/oyster-valve-rl) • [Demo](https://LINK_TO_VALVE_VIDEO)

---

### 3) Asymmetric (“Distorted”) UAV for Inspection
**Stack:** C++/Python, ROS2, custom dynamics, MPC/PID  
**Pitch:** Intentional arm asymmetry; robustness vs. maneuverability tradeoff.  
**Links:** [Repo](https://github.com/YOUR_GITHUB_USERNAME/distorted-uav) • [Demo](https://LINK_TO_UAV_VIDEO)

<details>
  <summary><b>Highlights</b></summary>
  - Model-ID and controller tuning for asymmetric inertia  
  - GPS-denied stabilization; wall-proximity disturbance tests  
  - Safety monitors + failsafes
</details>

---

### 4) Reduced-View 3D Localization for X-Ray Guidance
**Stack:** Python, A*, custom metric selection  
**Pitch:** Optimize camera angles to cut shots + dose while preserving accuracy.  
**Links:** [Repo](https://github.com/YOUR_GITHUB_USERNAME/xray-angle-a-star) • [Preprint](https://LINK_TO_PDF)

---

### 5) Language-Commanded 2-DoF Arm
**Stack:** Python, IK, trajectory interpolation  
**Pitch:** Parse “left/right/ahead/back + distance” into safe trajectories.  
**Links:** [Repo](https://github.com/YOUR_GITHUB_USERNAME/lang-to-motion) • [Demo](https://LINK_TO_ARM_VIDEO)

---

## 📚 Publications

> Don’t hide citations. Link them.

- **ICARA 2025** — *Stable Wreckage Detection for AUVs Using YOLOv8 and Enhanced RRT Path Planning* — DOI: 10.1109/ICARA64554.2025.10977642  
- **IEEE CASE 2025 (oral)** — *Learning-based AUV & Marine Life Interaction*  
- **ICCUBEA 2023** — *AUR for Mapping & Oil Leakage Localization* — DOI: 10.1109/ICCUBEA58933.2023.10392140  
- **ICOEI 2022** — *Automated UAV to Survey Elevator Hoistway* — DOI: 10.1109/ICOEI53556.2022.9776670  
- **PE&D 2022 (Journal)** — *Autonomous UAV for Radiation Monitoring…* — https://doi.org/10.2478/pead-2022-0010  
- **arXiv** — *Autonomous UAV for Building Monitoring…* — https://arxiv.org/abs/2111.07166

<details>
  <summary><b>Show BibTeX</b></summary>

```bibtex
@inproceedings{yourkey2025icara,
  title={Stable Wreckage Detection for AUVs Using YOLOv8 and Enhanced RRT Path Planning},
  booktitle={ICARA},
  year={2025},
  doi={10.1109/ICARA64554.2025.10977642}
}
