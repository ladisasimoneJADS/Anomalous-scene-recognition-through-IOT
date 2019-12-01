# Anomalous-scene-recognition-through-IOT: a data fusion approach
An automated surveillance system solution composed by multiple data sources is presented. Data sources does not necessarily mean expensive hardware, but common smartphone cameras. The data sources record people moving in a scene, the information about the people movement is analyzed in order to understand if anomalous behavior occurred during the recording. The automated surveillance system can trigger an alarm at the exact time an anomalous behavior is recognize.

The video cameras can have multiple fixed position. Video signal of each physical sensors are first
processed to extract moving image region. The information of the moving object in the screen are
then gathered, each video source from the fixed position will generate the geometrical information
needed to perform fusion deploying Unscented Kalman filter.
An unsupervised approach adopting dimensionality reduction technique UMAP and clustering
algorithm K-mean is proposed to extract common pattern in the data fused. These algorithms
automatically cluster trajectories that have common statistic behavior, and cluster pattern with
uncommon behavior, or anomalous behavior. 
