# CSLAM-Paper-Lists

- [1] Jacopo Panerati, Marco Minelli, Cinara Ghedini, Lucas Meyer, Marcel Kaufmann, Lorenzo Sabattini, Giovanni Beltrame: Robust connectivity maintenance for fallible robots. Auton. Robots 43(3): 769-787 (2019)
多机器人连接维护

- [2] 	Nikolay Atanasov, Jerome Le Ny, Kostas Daniilidis, George J. Pappas: Decentralized active information acquisition: Theory and application to multi-robot SLAM. ICRA 2015: 4775-4782
分布式信息获取

- [3] Graeme Best, Michael Forrai, Ramgopal R. Mettu, Robert Fitch: Planning-Aware Communication for Decentralised Multi-Robot Coordination. ICRA 2018: 1050-1057
传输规划，将通信问题抽象为求解DAG子图，DP求解

- [4] 	Saurav Agarwal, Srinivas Akella: Simultaneous Optimization of Assignments and Goal Formations for Multiple Robots. ICRA 2018: 6708-6715
队形规划，未考虑通信问题，匈牙利算法

- [5] James Paulos, Steven W. Chen, Daigo Shishika, Vijay Kumar: Decentralization of Multiagent Policies by Learning What to Communicate. ICRA 2019: 7990-7996
任务规划，分布式，CNN求解

- [6] Maria Teresa Lazaro, Lina María Paz, Pedro Pinies, José A. Castellanos, Giorgio Grisetti:
Multi-robot SLAM using condensed measurements. IROS 2013: 1069-1076
2D SLAM

- [7] 	Sajad Saeedi G., Michael Trentini, Mae L. Seto, Howard Li: Multiple-Robot Simultaneous Localization and Mapping: A Review. J. Field Robotics 33(1): 3-46 (2016)
综述，认为Data sharing是问题之一，分为传输传感器数据和处理后的数据

- [8] Mathieu Labbé, François Michaud: RTAB-Map as an open-source lidar and visual simultaneous localization and mapping library for large-scale and long-term online operation. J. Field Robotics 36(2): 416-446 (2019)
IntroLab组对RTAB-Map的总结性工作

- [9] Siyan Dong, Kai Xu, Qiang Zhou, Andrea Tagliasacchi, Shiqing Xin, Matthias Nießner, Baoquan Chen: Multi-robot collaborative dense scene reconstruction. ACM Trans. Graph. 38(4): 84:1-84:16 (2019)
稠密重建，激光SLAM定位，传输RGBD和定位

- [10] Keith Yu Kit Leung, Tim D. Barfoot, Hugh H. T. Liu: Decentralized Localization of Sparsely-Communicating Robot Networks: A Centralized-Equivalent Approach. IEEE Trans. Robotics 26(1): 62-77 (2010)
理论工作

- **[11] Stuart Golodetz, Tommaso Cavallari, Nicholas A. Lord, Victor Adrian Prisacariu, David William Murray, Philip H. S. Torr: Collaborative Large-Scale Dense 3D Reconstruction with Online Inter-Agent Pose Optimisation. IEEE Trans. Vis. Comput. Graph. 24(11): 2895-2905 (2018)
稠密重建，传输RGBD，给出了详细的实现细节，包括4种缓冲区管理策略**

- [12] Luis Riazuelo, Javier Civera, J. M. M. Montiel: C2TAM: A Cloud framework for cooperative tracking and mapping. Robotics Auton. Syst. 62(4): 401-413 (2014)
传输RGBD关键帧

- [13] Cesar Cadena, Luca Carlone, Henry Carrillo, Yasir Latif, Davide Scaramuzza, José Neira, Ian Reid, John J. Leonard: Past, Present, and Future of Simultaneous Localization and Mapping: Toward the Robust-Perception Age. IEEE Trans. Robotics 32(6): 1309-1332 (2016)
综述

- **[14] Matthew Giamou, Kasra Khosoussi, Jonathan P. How: Talk Resource-Efficiently to Me: Optimal Communication Planning for Distributed Loop Closure Detection. ICRA 2018: 1-9
多机器人传输带宽优化**

- [15] Christian Forster, Simon Lynen, Laurent Kneip, Davide Scaramuzza: Collaborative monocular SLAM with multiple Micro Aerial Vehicles. IROS 2013: 3962-3970
稀疏重建，传输关键帧、与上一关键帧的相对位置

- [16] Jing Dong, Erik Nelson, Vadim Indelman, Nathan Michael, Frank Dellaert: Distributed real-time cooperative localization and mapping using an uncertainty-aware expectation maximization approach. ICRA 2015: 5807-5814
2D SLAM

- [17] Titus Cieslewski, Davide Scaramuzza: Efficient Decentralized Visual Place Recognition Using a Distributed Inverted Index. IEEE Robotics Autom. Lett. 2(2): 640-647 (2017)
分布式，能够通信时传输部分bag of words

- **[18] Dominik Van Opdenbosch, Martin Oelsch, Adrian Garcea, Tamay Aykut, Eckehard G. Steinbach: Selection and Compression of Local Binary Features for Remote Visual SLAM. ICRA 2018: 7270-7277
基于ORB-SLAM2，传输压缩ORB特征**

- [19] Xiaqing Ding, Yue Wang, Li Tang, Huan Yin, Rong Xiong: Communication constrained cloud-based long-term visual localization in real time. IROS 2019: 2159-2166
传输关键帧、点云

- [20] Ryan J. Marcotte, Xipeng Wang, Dhanvin Mehta, Edwin Olson: Optimizing multi-robot communication under bandwidth constraints. Auton. Robots 44(1): 43-55 (2020)
理论分析

- [21] Yoonchang Sung, Ashish Kumar Budhiraja, Ryan K. Williams, Pratap Tokekar: Distributed assignment with limited communication for multi-robot multi-target tracking. Auton. Robots 44(1): 57-73 (2020)
分布式通信

- [22] Ramanarayan Vasudevan, Gregorij Kurillo, Edgar J. Lobaton, Tony Bernardin, Oliver Kreylos, Ruzena Bajcsy, Klara Nahrstedt: High-Quality Visualization for Geographically Distributed 3-D Teleimmersive Applications. IEEE Trans. Multimedia 13(3): 573-584 (2011)
传输三维模型（Internet 2）

- **[23] Patrick Stotko, Stefan Krumpen, Matthias B. Hullin, Michael Weinmann, Reinhard Klein: SLAMCast: Large-Scale, Real-Time 3D Reconstruction and Streaming for Immersive Multi-Client Live Telepresence. IEEE Trans. Vis. Comput. Graph. 25(5): 2102-2112 (2019)
传输压缩体数据，线程安全的哈希表**


