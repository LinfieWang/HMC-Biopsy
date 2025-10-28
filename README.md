# An Ultrasound-Guided Tumor Puncture Framework with Vascular Avoidance for Human-Machine Collaborative Biopsy

> 🔒 **Code will be released upon paper acceptance.**

---

## 📄 Abstract

Ultrasound (US) imaging has gained widespread application in guiding biopsy procedures. However, conventional manual US-guided biopsy remains limited by occupational exposure risks, limited accuracy in vessel and lesion identification, and strong dependence on operator proficiency. To address these challenges, we propose a tumor biopsy framework centered on a tele-assisted robotic system. The framework implements coordinated master–slave manipulation using a Kalman-filter-enhanced proportional–derivative (PD) control algorithm, and integrates a real-time segmentation–based vision module to localize tumors and avoid blood vessels with high precision. At the end effector, a two-degree-of-freedom (2-DOF) remote center-of-motion (RCM) mechanism enables concurrent operation of the US probe and biopsy needle within confined spaces. In addition, a geometric quantification strategy based on spatial calibration strategy is introduced to support millimeter-level error assessment. Performance was evaluated in silicone phantoms across three puncture modes. Compared with conventional manual puncture, the robotic system achieved a mean positioning error of 2.00±0.54 mm (a 47.8% improvement) and an angular error of 4.81°±1.10° (n 36.3% improvement), meeting clinical requirements for biopsy guidance. These results indicate that the proposed framework can substantially enhance procedural accuracy while reducing dependence on operator skill and clinical experience, thereby holding promise for safer and more reliable US-guided biopsy.

---

## 🎥 Video Demonstration

<!-- 直接嵌入视频，支持 mp4/webm -->
<video width="800" controls autoplay loop muted style="border: 1px solid #e1e4e8; border-radius: 8px; display: block; margin: 0 auto;">
  <source src="videos/demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<p align="center">
  <em>Video: Real-time vascular avoidance during ultrasound-guided tumor puncture. The system provides haptic and visual feedback to guide the surgeon.</em>
</p>

---

## 🖼️ Framework Overview

![HMC Biopsy Framework](fig1.png)

**Figure 1**: The proposed HMC biopsy framework consists of:  
(1) Real-time ultrasound guidance,  
(2) Vascular structure detection and risk zone estimation,  
(3) Dynamic path planning with obstacle avoidance,  
(4) Shared control interface with haptic and visual feedback,  
(5) Surgeon-in-the-loop decision making.

---

## 📁 Repository Structure
