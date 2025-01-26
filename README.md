# Core Innovations of OptiDeepSORT Algorithm

### 1. LiteShuffleNet Lightweight Feature Extraction Network  
- **Speed Optimization**: Designed a ShuffleNet-based lightweight backbone network
- **Precision Preservation**: Introduced channel shuffling mechanism to maintain ReID feature discriminability while reducing computation
- **Multi-Scale Fusion**: Enhanced small target feature representation through pyramid feature aggregation modules  

### 2. DAEKF-SCIoU Multi-Level Matching Mechanism  
- **Nonlinear Modeling**: Proposed Dual Attention Extended Kalman Filter (DAEKF) with motion/appearance dual-attention gating
- **Spatial-Constrained Metric**: Developed SCIoU similarity matrix combining IoU and center-distance constraints to resolve boundary ambiguity in dense scenes  

### 3. Group-Individual Dual Attention Motion Modeling  
- **Crowd Dynamics Modeling**: Captured collective motion patterns using graph attention networks to predict occluded trajectories  
- **Occlusion Compensation**: Reconstructed motion semantics via spatio-temporal attention mechanism
- **Multimodal Fusion**: Dynamically fused collective movement patterns with individual motion features to enhance trajectory recovery after long-term occlusion  
