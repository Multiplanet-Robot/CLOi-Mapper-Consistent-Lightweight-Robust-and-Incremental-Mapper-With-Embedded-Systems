# CLOi-Mapper: Consistent, Lightweight, Robust, and Incremental Mapper With Embedded-Systems for Commercial Robot Services

# Organizations and participants
 ![](https://www.lge.co.kr/lgekor/asset/company/images/about/ci_img03.jpg)
* DongKi Noh, Advanced Robotics Lab. LG Electronics Inc. (E-mail: dongki.noh@lge.com)
* Jeongsik Choi, Advanced Robotics Lab. LG Electronics Inc. (E-mail: jeongs.choi@lge.com)
* Seungmin Baek, Advanced Robotics Lab. LG Electronics Inc. (E-mail: seungmin2.baek@lge.com)

# Goals
* This study focuses on extensible methods to fuse sensors complementarily in different combinations.
 
![Robots](https://github.com/Multiplanet-Robot/CLOi-Mapper-Consistent-Lightweight-Robust-and-Incremental-Mapper-With-Embedded-Systems/assets/93900066/2d6f8d98-ce17-4046-8a20-f3963219590c)



# Assignment
* Kalman-filter-like tracking method based on the Bayesian framework with a minimum number of nodes
* Efficient graph generation method with temporal node integration
* Node pruning to mitigate the degradation of measurements from low-cost sensors

# Citation

* BibTeX of CLOi-Mapper (RA-L) will be released after the publication of the paper.

# System configuration of CLOi guidbot named as Airstar
![image](https://github.com/Multiplanet-Robot/CLOi-Mapper-Consistent-Lightweight-Robust-and-Incremental-Mapper-With-Embedded-Systems/assets/93900066/5338fd65-868c-44d4-93fa-5d68668a95d2)

* There were too many repetitive patterns in the airport.
 
![image](https://github.com/Multiplanet-Robot/CLOi-Mapper-Consistent-Lightweight-Robust-and-Incremental-Mapper-With-Embedded-Systems/assets/93900066/a1816067-d759-4ecb-ae1b-a615acf7b549)
# How to use the dataset

* The dataset (R9-home) will be released after the publication of the paper.
* Blue dots represent nodes after pruning.
* Gray dots represent nodes before pruning.

![image](https://github.com/Multiplanet-Robot/CLOi-Mapper-Consistent-Lightweight-Robust-and-Incremental-Mapper-With-Embedded-Systems/assets/93900066/ca6cc753-71fb-4a94-a03c-6fcd6c70db2b)

# Incremental mapping
To demonstrate how our SLAM algorithm incrementally adds a visual or LiDAR map on a prebuilt map, two case studies were
conducted as follows in cases of D1 and D2: In D1, using a prebuilt CAD map with its associated poses, our SLAM algorithm builds a pose-graph only with visual keyframes
by tracking a robot’s position; In D2, using a map built from the D1 case, our SLAM algorithm incrementally associates a LiDAR keyframe to a frame node
on the backbone.

Incremental mapping results at Incheon International Airport: (a) A CAD map, (b) the mapping result of case D1, (c) the
mapping result of case D2. Gray regions are occupied spaces, and white-colored regions are free
spaces. Identical colored frame nodes means that they were generated at the same epoch.
![image](https://github.com/Multiplanet-Robot/CLOi-Mapper-Consistent-Lightweight-Robust-and-Incremental-Mapper-With-Embedded-Systems/assets/93900066/00ecac5c-ee82-49a3-aafb-18656e9be439)

