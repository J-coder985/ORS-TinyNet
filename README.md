# ORS-TinyNet: Tiny Object Detection in Optical Imagery with a Designed Multi-Dimensional Attention Network
Authors: Xiaozheng Jiang*, Wei Zhang*, Xuerui Mao** and Haifeng Tan**

*:  The authors contributed equally to this work.
**: Corresponding author

# Overview
Detecting tiny objects in optical remote sensing (ORS) imagery has been a long-standing challenge due to their extremely limited spatial information, weak feature representations, and dense distributions across complex backgrounds. Despite numerous efforts devoted, mainstream detectors still underperform in such scenarios. To bridge this gap, we introduce ORS-TinyNet, a novel detection framework explicitly tailored for tiny object detection in satellites or unmanned aerial vehicles (UAVs) optical imagery. The core design of ORS-TinyNet is a multi-dimensional collaborative attention (MDCA) mechanism, which jointly integrates channel-spatial dependencies and global-local contextual cues to enhance the saliency and discriminability of tiny objects and suppress background interference. Moreover, MDCA is lightweight and flexible, allowing seamless integration into different stages of the detection pipeline for progressive feature refinement. Comprehensive experiments on public dataset AI-TOD show that our ORS-TinyNet surpasses existing state-of-the-art (SOTA) detectors by 4.0\% AP and 6.5\% $\mathrm{AP_{75}}$. Evaluations on DIOR benchmark dataset further validate its superior detection performance in diverse optical scenarios. These results demonstrate that the proposed multi-dimensional attention network offers an effective and practical solution for tiny object detection in challenging environments.

# Result
![Visualization of detection results on the AI-TOD dataset.](Result/AI-TOD.jpg)
