# Apurv Kushwaha

Robotics graduate student at the University of Minnesota, working on robot manipulation, teleoperation, perception, and robot learning, with a background in embedded systems and product development.

As a Graduate Research Assistant in [Prof. Zhu-Tian Chen](https://chenzhutian.org/)'s lab, I build human-in-the-loop systems for collecting robot-manipulation data: Meta Quest 3 teleoperation of two Trossen WidowX AI arms, and CAD/RGB-D tracking of a 3D-printed leader arm. The stack covers task-frame calibration, inverse kinematics, safety-gated MuJoCo validation, and about 90 Hz bimanual hardware control.

- M.S. Robotics, University of Minnesota Twin Cities, GPA 3.83/4.00, expected May 2027
- B.Tech Engineering Physics, Indian Institute of Technology Guwahati
- Open to robotics, perception, embedded-systems, and product-development roles

[Website](https://apurvkushwaha.com) · [Google Scholar](https://scholar.google.com/citations?user=1XwQNOMAAAAJ) · [LinkedIn](https://www.linkedin.com/in/kushwahaapurv/) · [Resume](https://apurvkushwaha.com/resume/Apurv_Kushwaha_Resume.pdf)

## Research

**Probabilistic Physics Digital Twin for Human-Robot Interaction**<br>
Y. Hu, H. Chandirasekar, **A. Kushwaha**, J. King, Z.-T. Chen<br>
Under review at IEEE ICRA 2027 · [arXiv:2610.19336](https://arxiv.org/abs/2610.19336)

Models uncertainty in object mass, friction, and center of mass to predict action outcomes and guide human-robot manipulation. My part: dual-camera point-cloud synchronization and arm-trajectory planning.

## Selected work

| MIRA: real arm, cubes moved mid-task (2×) | humanoid-vla: fine-tuned VLA, unseen layouts | π-WBC: PPO walking policy in MuJoCo |
| :---: | :---: | :---: |
| <a href="https://github.com/ApurvK032/mira-manipulation"><img src="https://github.com/ApurvK032/mira-manipulation/raw/main/docs/media/full_cycle.gif" height="130" alt="WidowX AI arm following and stacking cubes while a hand moves them"></a> | <a href="https://github.com/ApurvK032/humanoid-vla"><img src="https://github.com/ApurvK032/humanoid-vla/raw/main/docs/media/m3_policy_pair.gif" height="130" alt="Fine-tuned SmolVLA policy sorting blocks on a simulated Unitree G1 under two instructions"></a> | <a href="https://github.com/ApurvK032/pi-wbc"><img src="https://github.com/ApurvK032/pi-wbc/raw/main/results/stage1/gait_v3_s1_walk_1.0.gif" height="130" alt="Unitree G1 walking at 1 m/s in MuJoCo with a policy trained in Isaac Lab"></a> |

| Project | What it does |
| --- | --- |
| [dex-coder](https://github.com/ApurvK032/dex-coder) | An LLM coding agent writes the camera-only controller for a Unitree G1 + Dex3 hand in MuJoCo. 92-100% success on unseen layouts, about $2.60 per controller. |
| [humanoid-vla](https://github.com/ApurvK032/humanoid-vla) | Fine-tunes the SmolVLA vision-language-action model for language-conditioned block sorting on a simulated Unitree G1, judged in closed loop on unseen layouts. MuJoCo, LeRobot, PyTorch. |
| [MIRA](https://github.com/ApurvK032/mira-manipulation) | Markerless 6D object pose tracking from RGB-D and CAD models drives a WidowX AI arm that stacks cubes while a person keeps moving them. Sim-to-real RL in progress. |
| [π-WBC](https://github.com/ApurvK032/pi-wbc) | PPO whole-body control for a simulated Unitree G1, trained in Isaac Lab and tested in plain MuJoCo. The walking policy had no falls in 360 MuJoCo episodes across 3 training runs; body-pose and arm commands are in progress. |
| [visual-teleop](https://github.com/ApurvK032/visual-teleop) · [demo](https://www.youtube.com/watch?v=pCG0TpFCu6Q) | Camera-only teleoperation: a 3D-printed, electronics-free leader arm tracked from RGB-D with DLR M3T drives a WidowX AI follower. Research prototype. |
| [aria-teleop](https://github.com/ApurvK032/aria-teleop) | Teleoperates a WidowX AI arm with Meta Aria Gen 2 glasses: on-device hand tracking steers the gripper and a wink engages control. |
| [ROS LLM Ops](https://github.com/ApurvK032/ros-llm-ops) | Plain-English missions for a ROS 2 warehouse robot. A local Qwen model proposes typed commands; the supervisor sequences pickups and drives a TurtleBot3 through Nav2 in Gazebo. |
| [Quest 3 Bowling Ball Tracking](https://github.com/ApurvK032/quest3-bowling-ball-tracking) | Course team project: Meta Quest 3 video capture, YOLO and SAM2 ball tracking, lane-space trajectory reconstruction, and mixed-reality shot replay. |

**More:** [print-in-place arm](https://github.com/ApurvK032/print-in-place-arm) · [Microduck WebXR](https://github.com/ApurvK032/microduck-webxr) · [Image retargeting](https://github.com/ApurvK032/cv5561-f25-team-asa) (course team project) · [Autonomous parking bot](https://github.com/ApurvK032/Autonomous-Car-Parking-Bot)

## Toolbox

- Robotics: ROS 2, Nav2, Gazebo, MuJoCo, Isaac Lab, inverse kinematics, path planning
- Robot learning: LeRobot, SmolVLA, imitation learning, reinforcement learning (PPO), PyTorch, LLM agents
- Perception: OpenCV, Intel RealSense, DLR M3T pose tracking, YOLO, SAM2
- XR and teleoperation: Meta Quest 3, WebXR, Meta Aria Gen 2, Unity, C#
- Embedded and mechatronics: ESP32, Arduino, Embedded C, PCB design, CAD, 3D printing
- Engineering: Python, C++, MATLAB, Linux, Git, Docker, CMake
