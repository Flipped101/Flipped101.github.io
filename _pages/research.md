---
layout: archive
title: "研究动态"
permalink: /research/
author_profile: true
toc: true
---


<!-- {% include toc %} -->

<!-- # Research Keywords -->

<!-- <br />
<img align="center" width="800" src="{{ site.url }}/images/WordCloudResearch.png" alt="...">
<br />
 -->




&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;智能机器人在制造和医疗领域的理论、算法和应用，包括机器人运动学/动力学，机器人-机器人/人协作及多模态感知等，寻找先进算法与最终质量之间的内在联系，使机器人系统得到高效、精确控制，并实现机器人高灵活性。
<div style="text-align: center;">
<img align="" width="60%" style="" src="{{ site.url }}/images/research/研究方向01.png" alt="...">
</div>

## 主要研究进展如下:

### （1）机器人加工轨迹生成

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;提出了基于NC代码的机器人铣削控制指令的转换方法，并开发了机器人铣削加工仿真软件RobMach。该方法包括NC代码中数据的分析与提取，刀位点到机器人基坐标系的位姿转换和铣刀位姿的转换的三个过程。在此基础上，通过解析G-Code和机器人控制命令及其转换机制，开发了机器人铣削加工软件RobMach，首先需要将加工零件导入UG，利用UG的CAM模块得到刀位文件（G代码）。RobMach则将刀位文件转换成RAPID指令文件（.mod文件），软件可以根据转换的指令仿真出机器人的完整动作，并将指令直接传输给机器人，实现机器人的离线编程功能。本软件主要由输入输出区、代码转换可视区、仿真运动可视区、铣削轨迹生成区、仿真执行控制区构成。其功能主要是将导入的G Code转换为机器人的RAPID指令（.mod文件），并进行仿真验证。
<div style="text-align: center;">
<img align="" width="50%" style="" src="{{ site.url }}/images/research/研究进展1.png" alt="...">
<br>
<br>
<video controls width="50%">
     <source src="{{ site.url }}/images/research/研究进展1.mp4" type="video/MP4">
</video>

<br>
<br>
<video controls width="50%">
     <source src="{{ site.url }}/images/research/研究进展2.mp4" type="video/MP4">
</video>
<br>
</div>

### （2）软体手设计

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;设计的智能多指软体手IntMSHand，配备了多指手（手）、视-触觉系统（眼、触）等，实现“手眼触”一体化的智能软体手抓取操作。核心技术：1）多个软体手指与反馈调节装置，实现各种不同尺寸与外形物体的自适应抓取；2）3D视觉结合机器学习，实现待抓取物体的识别与位姿估计、以及抓取任务规划；3）基于视-触觉传感器的被抓取物体的力位精准控制。技术优势：对被抓取物体的适用性强，特别针对精密零部件，能够保证抓取的准确性与鲁棒性，可应用到智能制造，食品业、3C行业等领域。
<div style="text-align: center;">

<img align="" width="50%" style="" src="{{ site.url }}/images/research/研究进展2.jpg" alt="...">
<br>
<br>
<video controls width="50%">
     <source src="{{ site.url }}/images/research/研究进展3.mp4" type="video/MP4">
</video>
<br>
</div>

### （3）双臂与遥操作机器人
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;双臂协作机器人主要包括工作台、控制柜、两台六自由度机械臂、双臂支架、两个二指夹爪、头部3D相机、两个手部2D相机、工控机及ROS机器人操作系统等，可以实现抓取、装配等任务。
<div style="text-align: center;">

<img align="" width="50%" style="" src="{{ site.url }}/images/research/研究进展3.png" alt="...">
<br>
<br>
<video controls width="50%">
     <source src="{{ site.url }}/images/research/研究进展4.mp4" type="video/MP4">
</video>
<br>
<br>
<video controls width="50%">
     <source src="{{ site.url }}/images/research/研究进展5.mp4" type="video/MP4">
</video>
<br>
</div>


### （4）移动检测机器人
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;由MK ROBOT-01室外智能移动平台、AUBO I7协作机械臂、机械臂升降装置、热成像光双谱云台、高性能工作站、ROS操控软件等组成，智能移动复合机器人搭载有ROS操控软件的高性能移动工作站，通过激光雷达、IMU、RTK等传感器实现机器人的定位导航、自主避障、自主路径规划、远程控制以及不同高度范围内的检测等功能。
<div style="text-align: center;">

<img align="" width="50%" style="" src="{{ site.url }}/images/research/研究进展4.png" alt="...">
<br>
<br>
<video controls width="55%">
     <source src="{{ site.url }}/images/research/研究进展6.mp4" type="video/MP4">
</video>
<br>

</div>






<!-- 
<img align="left" width="200" style="" src="{{ site.url }}/images/research/GelTip.jpeg" alt="...">
GelTip: A Finger-shaped Optical Tactile Sensor for Robotic Manipulation <br />
D.F. Gomes, Z. Lin, **S. Luo**. IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2020. <br />
[[paper]](https://arxiv.org/abs/2008.05404) [[website]](https://danfergo.github.io/geltip/) [[STL files]](https://danfergo.github.io/geltip/geltip2020_parts.zip)

<br />
<br />
<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/exp_world_blocks.gif" alt="...">
Blocks World of Touch: Exploiting the Advantages of All-around Finger Sensing in Robot Grasping <br />
D.F. Gomes, Z. Lin, **S. Luo**. Frontiers in Robotics and AI 7, 541661, 2020. <br />
[[paper]](https://www.frontiersin.org/articles/10.3389/frobt.2020.541661/full) [[website]](https://danfergo.github.io/geltip/)

<br />
# Simulation of optical tactile sensors
<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/simulation_GelSight.gif" alt="...">
Generation of gelsight tactile images for sim2real learning <br />
D.F. Gomes, P. Paoletti, **S. Luo**. IEEE Robotics and Automation Letters, 6(2), pp.4177-4184. & The International Conference on Robotics and Automation (ICRA) 2021. <br />
[[paper]](https://arxiv.org/abs/2101.07169) [[website]](https://danfergo.github.io/gelsight-simulation/) [[code]](https://github.com/danfergo/gelsight_simulation)
<br />
<br />
<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/ICRA2022_Tudor.png" alt="...">
Reducing Tactile Sim2Real Domain Gaps via Deep Texture Generation Networks <br />
T. Jianu, D.F. Gomes, P. Paoletti, **S. Luo**. IEEE International Conference on Robotics and Automation (ICRA) 2022. <br />
[[paper]](https://arxiv.org/abs/2112.01807) [[website]](https://danfergo.github.io/gelsight-simulation/)
<br />
<br />
<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/Tacchi.gif" alt="...">
Tacchi: A Pluggable and Low Computational Cost Elastomer Deformation Simulator for Optical Tactile Sensors <br />
Z. Chen, S. Zhang, **S. Luo**, F. Sun, B. Fang IEEE Robotics and Automation Letters, 2023. <br />
[[paper]](https://arxiv.org/pdf/2301.05043.pdf) [[website]](https://github.com/zixichen007115/Tacchi)

<br />
<br />
<br />
<br />
# Robot Perception of Flexible Materials with Vision and Tactile Sensing

<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/LeszekIROS2022.gif" alt="...">
Visual-Tactile Multimodality for Following Deformable Linear Objects Using Reinforcement Learning <br />
L. Pecyna, S. Dong, **S. Luo**. IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2022. <br />
[[paper]](https://arxiv.org/abs/2204.00117) [[code]](https://github.com/lpecyna/SoftSlidingGym)
<br />
<br />
<br />
<br />
<br />
<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/TactileAttention.png" alt="...">
Spatio-temporal attention model for tactile texture recognition <br />
G. Cao, Y. Zhou, D. Bollegala, **S. Luo**. IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2020. [[paper]](https://arxiv.org/abs/2008.04442)
<br />
<br />
<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/T2S_S2T.png" alt="...">
"Touching to See" and "Seeing to Feel": Robotic Cross-modal SensoryData Generation for Visual-Tactile Perception <br />
J.-T. Lee, D. Bollegala, **S. Luo**. IEEE International Conference on Robotics and Automation (ICRA) 2019. <br />
[[paper]](https://arxiv.org/abs/1902.06273)
<br />
<br />
<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/iCLAP.png" alt="...">
iCLAP: Shape Recognition by Combining Proprioception and Touch Sensing <br />
**S. Luo**, W. Mou, K. Althoefer and H. Liu. Autonomous Robots 2019. <br />
[[paper]](https://arxiv.org/pdf/1806.07507.pdf) <br />
Iterative closest labeled point for tactile object shape recognition
**S. Luo**, W. Mou, K. Althoefer and H. Liu. IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2016.
[[paper]](https://arxiv.org/abs/1708.04436)

<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/ViTac_ICRA2018.png" alt="...">
ViTac: Feature Sharing between Vision and Tactile Sensing for Cloth Texture Recognition <br />
**S. Luo**, W. Yuan, E. Adelson, A. G. Cohn and R. Fuentes. IEEE International Conference on Robotics and Automation (ICRA) 2018. [[paper]](https://arxiv.org/pdf/1802.07490.pdf) [[dataset]](https://drive.google.com/drive/folders/1uwPDUm7cDtBGJUQRe4H1KeQwcJQrnMJF?usp=share_link) <br />

<br />
<br />
# Robot Perception of Transparent Objects with Vision and Tactile Sensing

<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/A4T.gif" alt="...">
A4T: Hierarchical Affordance Detection for Transparent Objects Depth Reconstruction and Manipulation  <br />
J. Jiang, G. Cao, T.-T. Do, **S. Luo**. IEEE Robotics and Automation Letters & IEEE 18th International Conference on Automation Science and Engineering (CASE) 2022 - **Best Student Paper Award Finalist**. [[paper]](https://arxiv.org/abs/2008.04442) [[website]](https://sites.google.com/view/affordance4trans) [[dataset]](https://sites.google.com/view/affordance4trans) <br />
<br />
<br />
<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/Where2Touch.gif" alt="...">
Where shall I touch? Vision-Guided Tactile Poking for Transparent Object Grasping <br />
J. Jiang, G. Cao, A. Butterworth, T.-T. Do, **S. Luo**. IEEE/ASME Transactions on Mechatronics 2022. <br />
[[paper]](https://arxiv.org/abs/2208.09743) [[website]](https://sites.google.com/view/tactilepoking) [[code]](https://github.com/3PTelephant/TransparentObjectRender) [[dataset]](https://drive.google.com/drive/folders/1ReuoAuIm4R3VkUpiQhKKpIL4wGo1TQWj) <br />

<br />
<br />
# Minorities Matter: Long-tailed Object Recogntion
<img align="left" width="200" style="margin-right: 10px" src="{{ site.url }}/images/research/Gumbel.jpg" alt="...">
Long-tailed Instance Segmentation using Gumbel Optimized Loss <br />
K. P. Alexandridis, J. Deng, A. Nguyen, **S. Luo**. European Conference on Computer Vision (ECCV) 2022. <br />
[[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136700349.pdf) [[code]](https://github.com/kostas1515/GOL) <br /> -->
