---
#layout: archive
title: "科研项目"
permalink: /projects/
author_profile: true
---

<h2>视觉伺服规划与控制</h2>

<h3>国家自然科学基金青年项目：不确定性环境下的机械臂约束视觉伺服控制研究，2023.01-2025.12</h3>

<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img src="https://jianliangmao.github.io/_pages/gif/青年基金_DRL避障.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div> 
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
   <b>&#8226; &emsp;基于深度强化学习的动态避障与跟踪</b><br>
    <span style="font-size: 0.9em;">随着机械臂在工业和服务业应用中的普及，会出现越来越多的非结构化任务场景，需要对运动中物体进行加工或避开随机出现的障碍物。这就要求控制算法要有更强的智能性，而对于传统控制算法来说，非结构化场景下环境地图无法预知，障碍物和目标随机变化，人为设计控制策略将无法保证最优性能。深度强化学习算法依托于神经网络强大的非线性拟合能力，且可以在环境中自主探索学习，无需根据环境模型人为设计策略。本方法利用深度强化学习和实时碰撞检测来构建动态场景下视觉跟踪控制的无模型和无碰撞框架，其中奖励函数考虑了跟踪误差、运动平滑性和避免碰撞，以确保机器人关节速度方面的轨迹平滑</span>
  </div>
</div>


<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img src="https://jianliangmao.github.io/_pages/gif/青年基金_SLMPC视觉伺服.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
   <b>&#8226;&emsp;基于逐次线性化的动态视觉伺服预测控制</b><br>
    <span style="font-size: 0.9em;">在基于视觉的机器人操作中，限制机械臂的运动学约束和预测是十分重要的，为了约束机器人的运动能见度和执行器饱和度，保证运动平滑，并保持目标在摄像机的视线内，提出一种新的模糊自适应模型预测控制。此外，在执行视觉伺服控制时，通常需要考虑系统采样周期与控制周期之间的周期不一致的双速率约束问题。首先引入卡尔曼滤波器估计系统状态为了进一步提高系统的控制频率，采用连续线性化的方法对原模型进行了优化，减少了控制器的计算时间，提出一种基于连续线性化的鲁棒模型预测控制方法的双速率约束动态视觉伺服。</span>
  </div>
</div>

<h3>企业横向课题：智能焊接机器人视觉伺服与运动控制系统研发，2022.11-2023.12</h3>

<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img  src="https://jianliangmao.github.io/_pages/gif/企业横向_焊接机器人系统.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
  <b>&#8226; &emsp;多层多道的焊缝识别及路径规划</b><br>
    <span style="font-size: 0.9em;">在盾构机刀盘的焊接过程中，面对巨大的刀盘、繁多的焊道数量以及多层多道的焊接任务，传统手工焊接方法耗时且人力成本高，容易导致质量问题和安全隐患。引入移动焊接机器人能够提高焊接精度、效率，并且保障工人安全性。基于此分析，设计和优化了机器人的机械结构、控制系统和焊接工具。还开发了用于焊缝识别、路径规划、运动控制和焊接参数优化的专用算法。通过使用精确的视觉识别、路径规划以及运动控制算法，机器人能够准确定位并在刀盘焊缝接口处进行一致的焊接任务。根据自主开发的上位机软件可以实时监控焊接过程参数、视觉识别结果以及焊缝质量分析，大大提高了焊接过程的可靠性与安全性。</span>
  </div>
</div>

<h2>机器人轨迹跟随控制</h2>

<h3>教育部重点实验室开放课题：基于复合抗干扰的机器人动力学控制方法研究，2022.05~2024.04</h3>

<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img  src="https://jianliangmao.github.io/_pages/gif/重实课题_非光滑轨迹跟随.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
  <b>&#8226; &emsp;基于非光滑控制的机械臂轨迹跟随</b><br>
    <span style="font-size: 0.9em;">由于对高性能的需求，连续轨迹跟踪控制在机械臂应用中是至关重要的。本方法建立了一个系统的跟踪控制框架，包括建模、干扰估计和补偿、以及非光滑反馈控制策略。首先采用参数辨识方法来重建动力学模型。随后，设置一个非光滑观测器来估计未知干扰。在这种情况下，动态建模和估计的干扰都可以通过前馈方法有效地补偿。此外，非光滑反馈控制设计的实施是用来减轻未建模的动态和不可估计的干扰的影响。所提出的方法的有效性进行了验证，通过严格的理论分析和6自由度的机械臂实验进行轨迹跟踪任务。</span>
  </div>
</div>

<h3>企业横向课题：管道爬壁机器人控制技术研究，2022.03-2022.12</h3>

<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img  src="https://jianliangmao.github.io/_pages/gif/企业横向_爬壁机器人系统.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
  <b>&#8226; &emsp;三维管道空间中的轨迹规划和跟踪</b><br>
    <span style="font-size: 0.9em;">管道爬壁机器人通常运行在密闭的三维管道壁面上，这给爬行机器人实现自主作业能力带来了挑战。针对管道受限条件下爬壁机器人传统手动遥控方式效率不高的问题，提出一种爬壁机器人在管道运维中的轨迹规划和跟踪方法，包括爬行机器人在管道圆柱面内壁上运动学模型的建立、三维空间目标轨迹到二维规划坐标系的映射转换、基于横截函数方法的轨迹跟踪控制器设计与结合轮壁作用几何关系得到的更准确的轮速分解计算公式。通过建立实际管道测试场景，利用惯性传感器和编码器实现轨迹反馈，在三维可视化空间中进行了相关验证。</span>
  </div>
</div>
  
<h2> 人机交互与柔顺控制</h2>

<h3> 教育部春晖计划合作科研项目：面向电力机器人的智能控制技术研究与应用，2023.05-2025.05</h3>

<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img  src="https://jianliangmao.github.io/_pages/gif/春晖计划_安全主动柔顺.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
 <b>&#8226; &emsp;基于强化学习的自适应安全柔顺控制</b><br>
     <span style="font-size: 0.9em;">在机器人与环境的交互任务中，如装配、打磨、抛光等作业，仅仅采用轨迹跟踪控制是不够的，需要机械臂具有对环境的主动柔顺性。同时，如何在不同动态环境下实现自适应的力交互，并且保证严格的安全性，是一项具有挑战性的任务。在机器人有力传感器的情况下，基于力传感器对机器人设计阻抗控制器，结合强化学习算法通过训练实现不同自适应阻抗以获得良好的力接触响应，并且结合控制障碍函数实现力接触过程中的安全性保障，实现严格力约束，达到了机器人在装配场景下的安全性保障以及高质量的力控效果。</span>
  </div>
</div>


<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img  src="https://jianliangmao.github.io/_pages/gif/春晖计划_融合物理数据外力估计.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
  <b>&#8226; &emsp;融合物理信息和神经网络的外力矩估计</b><br>
     <span style="font-size: 0.9em;">在工业自动化生产中，很多生产任务要求机器人能够感知到自身与环境之间产生的交互力，比如打磨抛光作业。虽然基于力/力矩传感器的力感知方案具有感知灵敏、感知精度高等优点，但这些传感器的使用也带来了成本增加和系统复杂度提高等问题。通过融合神经网络和传统物理建模机制提高力估计精度，以及融合机理模型和误差神经网络模型的混合模型，设计观测器进行外力矩估计，所获得的结果可以用于机器人碰撞检测以及柔顺控制，实现高精度、高灵敏度的碰撞检测功能。最后，在基于倍福控制器的六轴机械臂平台上进行了外力矩估计实验。</span>
  </div>
</div>

<h2>遥操作与共享控制</h2>

<h3>企业横向课题：远程协作智能运维机器人交互控制算法研究，2022.03-2023.08</h3>

<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img  src="https://jianliangmao.github.io/_pages/gif/企业横向_遥操作共享控制.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
  <b>&#8226; &emsp;基于局部自主避障和人机协同的共享控制</b><br>
    <span style="font-size: 0.9em;">在遥操作机器人过程中，为了避免视觉信息的局限性、通信延时以及人类操作者出现操作失误而导致机械臂与周围障碍物发生碰撞的问题，采用局部自主避障和人机协同的遥操作共享控制策略。通过人工势场法来提供吸引力和排斥力引导操作者完成避障任务，主端控制策略采用模型预测控制、控制障碍函数和模糊共享控制器结合，模糊共享控制器根据机械臂与障碍物之间的距离，动态选择控制输入，模型预测控制重新进行轨迹规划与跟踪，从而起到局部自主避障效果，再利用控制障碍函数对机械臂进行安全状态约束，从而保证机械臂的安全。</span>
  </div>
</div>

<h2>新能源电驱调速控制</h2>

<h3>上海市外国专家项目：基于抗干扰预测控制的新能源汽车永磁同步电机宽速域调节策略研究，2023.01-2023.12.31</h3>

<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img  src="https://jianliangmao.github.io/_pages/gif/上海市外专_新能源伺服驱动.jpg" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
  <b>&#8226;&emsp;基于时域自调节的速度预测控制</b><br>
    <span style="font-size: 0.9em;">新能源电动汽车的电驱调速系统在面对复杂多变的工况时，例如快速起停、大范围速度切换以及低速爬坡等，对电机驱动系统的动态性能和抗干扰能力提出了相当苛刻的要求。为了确保电驱系统在这些恶劣的工况下展现出良好的调速性能，在非级联结构下，基于扰动观测技术和模型预测控制方法设计了一种抗干扰的复合预测速度控制策略。该策略实现了系统在受扰情况下的高精度和快速动态速度控制。同时，引入了一种动态时域更新机制，赋予系统根据实际工况进行动态性能自优化的能力，提高了电驱系统在宽速域工况下的控制性能。。</span>
  </div>
</div>

<h3>江苏省产学研合作项目：高性能低压无刷直流电机驱控一体关键技术研发，2021.05-2023.05</h3>

<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img  src="https://jianliangmao.github.io/_pages/gif/省产学研_驱动一体无刷.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
  <b>&#8226;&emsp;基于低压直流无刷电机的力控模组</b><br>
    <span style="font-size: 0.9em;">机器人在装配领域对精密力控有着高度要求，同时夹持结构的设计也受到体积的限制。本项目的首要任务是设计并整合低压无刷直流驱动控制电路，以确保整个系统具备严格的稳定性和可靠性。在控制算法方面，采用基于FOC（磁场定向控制）的矢量控制算法，并引入扰动观测器对干扰进行估计与补偿，旨在提升伺服电机的工作效率和运动精度。同时，引入基于S型曲线的速度规划算法，以确保电机运动更加平稳。这些算法的整合有力地支持了机器人在装配领域执行复杂任务时的高要求。</span>
  </div>
</div>

<h2>其他项目</h2>

<h3>企业横向课题：全自主球团压力分析工作站系统研发，2022.12-2023.11</h3>
  
<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img  src="https://jianliangmao.github.io/_pages/gif/企业横向_球团压力自主检测.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
  <b>&#8226;&emsp;基于球团识别和多末端切换的机器人系统</b><br>
    <span style="font-size: 0.9em;">球团的成型质量对钢铁锻造起着至关重要的作用，为了实现对球团成型质量的监控，传统的方式采用人工线上取料、线下分析的手段。人工取料分析存在耗时耗力、效率低、球团压力检测的结果不确定性高的问题。本项目系统由机械臂作业系统、机器视觉检测系统、PLC压力检测系统、微机测控系统组成。采用全自主智能流水线作业，具备机器人自主取样与筛选、球团抗压检测、自动记录数据、自动清扫残渣、云端数据自动上传等功能。用户设定相关参数后，系统即可自主完成整个循环测试过程，摆脱了以往常规压力检测设备人工操作的繁琐，极大提高了测试效率。</span>
  </div>
</div>

<h3>企业横向课题：电力智能仓库信息化管理系统技术开发，2022.07-2023.11</h3>

<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img  src="https://jianliangmao.github.io/_pages/gif/企业横向_智能仓库信息化.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
  <b>&#8226;&emsp;基于IoT和RFID的智能仓储管理系统</b><br>
    <span style="font-size: 0.9em;">电力物资仓储物流属于电力行业中的重要环节，对电力企业的经营管理具有重要影响。本项目设计一种电力智能仓库信息化管理系统，通过运用先进成熟的计算机和通信技术，按照协同、实用、共享、安全的原则，构建一站式、一体化、高质量、高效率、智能化的仓储信息管理系统。采用RFID技术进行实时校对和处理，避免了人为因素造成的一系列问题，确保系统信息的真实性、准确性和实时性；标准化当前产品的入库和出库业务流程，提高工作人员的工作效率；同时通过实时数据信息采集，可以实时了解到仓库货物和环境情况。</span>
  </div>
</div>

<h3>企业横向课题：食品机械智能装备控制系统研发，2022.03-2025.02</h3>

<div style="display: flex; align-items: center;">
  <!-- 左侧图 -->
  <div style="flex-basis: 30%;">
    <img  src="https://jianliangmao.github.io/_pages/gif/企业横向_食品机械松丝设备.gif" alt="" width="300" height="200" object-fit="cover">
  </div>
  <!-- 中间空隙 -->
  <div style="flex-basis: 5%;"></div>
  <!-- 右侧介绍 -->
  <div style="flex-basis: 65%;">
  <b>&#8226;&emsp;基于STM32的多轴运动控制系统</b><br>
    <span style="font-size: 0.9em;">智能化食品机械加工设备是一种先进的制造设备，不仅整合了运动控制闭环技术、传感测量技术、液晶显示技术和故障诊断技术，而且通过这些技术的有机结合，实现了设备的一键化智能操作。为了确保设备的高效运行和稳定性，智能化食品机械加工设备采用了基于STM32F4的主控芯片和ucosII嵌入式实时操作系统。这种先进的主控芯片不仅提供了强大的计算和控制能力，而且结合了ucosII嵌入式实时操作系统，使得设备能够快速响应各种指令，实现高度智能化的控制。</span>
  </div>
</div>
