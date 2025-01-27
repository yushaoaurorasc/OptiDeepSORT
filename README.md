# Core Innovations of OptiDeepSORT Algorithm

### 1. LiteShuffleNet Lightweight Feature Extraction Network  
- **Speed Optimization**: Designed a ShuffleNet-based lightweight backbone network
- **Precision Preservation**: Introduced channel shuffling mechanism to maintain ReID feature discriminability while reducing computation
- **Multi-Scale Fusion**: Enhanced small target feature representation through pyramid feature aggregation modules  

### 2. DAEKF-SCIoU Multi-Level Matching Mechanism  
- **Nonlinear Modeling**: Proposed Dual Attention Extended Kalman Filter (DAEKF) with motion/appearance dual-attention gating
- **Spatial-Constrained Metric**: Developed SCIoU similarity matrix combining IoU and center-distance constraints to resolve boundary ambiguity in dense scenes  

### 3. Group-Individual Dual Attention Motion Modeling  
- **Individual and Group Interaction Modeling**: Introduced a dual attention mechanism within the Group and Individual Interaction Module (GIIM) to separately capture individual motion data and group interaction dynamics, enhancing trajectory prediction in crowded environments
- **Spatial State Mapping**: Established a spatial state map that integrates individual motion habits with spatial relative features, allowing for a comprehensive understanding of pedestrian navigation in complex scenes
- **Computational Efficiency**: Utilized Local Sensitive Hashing (LSH) to optimize attention calculations, balancing long-term temporal dependencies with reduced computational complexity in high-density scenarios.  

You can download the Airport-23 and Airport-24 datasets in full from https://huggingface.co/Jude30/OptiDeepSORT.
