# CLOi-Mapper: Consistent, Lightweight, Robust, and Incremental Mapper With Embedded-Systems for Commercial Robot Services

# Organizations and participants
 ![](https://www.lge.co.kr/lgekor/asset/company/images/about/ci_img03.jpg)
* DongKi Noh, Advanced Robotics Lab. LG Electronics Inc. (E-mail: dongki.noh@lge.com)
* Jeongsik Choi, Advanced Robotics Lab. LG Electronics Inc. (E-mail: jeongs.choi@lge.com)
* Seungmin Baek, Advanced Robotics Lab. LG Electronics Inc. (E-mail: seungmin2.baek@lge.com)

# Goals
* This study focuses on extensible methods to fuse sensors complementarily in different combinations.

# Assignment
* Kalman-filter-like tracking method based on the Bayesian framework with a minimum number of nodes
* Efficient graph generation method with temporal node integration
* Node pruning to mitigate the degradation of measurements from low-cost sensors

# Citation

* BibTeX CLOi-Mapper (RA-L)

# How to use the dataset

* The dataset will be released after the publication of the paper.
* SLAM poses data

	int nKeyFrameIx;		// keyframe index
	int nMapIx;			// local map index
	int nSceneIx;			// local scene index
	XYThetaFloat32_t stSLAMPose;	// slam pose
 	FILE* pFile = fopen("Log\\SLAM_pose.co", "rb");
 	while(!feof(pFile)){
		fread(&nKeyFrameIx, sizeof(int), 1, pFile);
		fread(&nMapIx, sizeof(int), 1, pFile);
		fread(&nSceneIx, sizeof(int), 1, pFile);
		fread(&stSLAMPose, sizeof(XYThetaFloat32_t), 1, pFile);
 	}
 	fclose(pFile);
