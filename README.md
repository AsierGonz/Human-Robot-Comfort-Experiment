# Human–Robot Comfort-Based Interaction Experiment (UR3e)

**Coming Soon — Resources for Reproducing the Experimental Study**

This repository contains the materials, code, and documentation related to the study:  
**"Adaptive Robot Motion Planning via Human Physiological Clustering and Comfort-Based Reinforcement Learning"**  
by **Asier Gonzalez-Santocildes** (Universidad de Deusto)

---

## 🎯 Purpose

This project provides a complete experimental protocol to evaluate how different robot trajectories, generated via reinforcement learning, impact human comfort. Using a UR3e collaborative robot, synchronized sensors, and subjective questionnaires, this experiment quantifies physiological and psychological reactions to robot behavior.

This repository **complements the Comfort-RL simulation platform**, available here:  
🔗 [github.com/AsierGonz/Comfort-RL](https://github.com/AsierGonz/Comfort-RL)  
> Use that repo to train agents; use this one to test their effects on real humans.

---

## 🧪 What Will Be Included

### 🔧 Experiment Infrastructure

- `ros_launch/` — ROS launch files for UR3e robot trajectory execution  
- `sensors/` — Scripts for synchronizing Polar Verity Sense heart-rate sensors and HD cameras  
- `camera_calibration/` — Calibration tools and layout diagrams  
- `data_logging/` — Modules to capture, timestamp, and log physiological, kinematic, and subjective data

### 📊 Data & Analysis

- `data_samples/` — Anonymized example data (∆HR vectors, WMI, questionnaires)
- `analysis/` — Python notebooks for:
  - ∆HR feature extraction
  - K-means clustering
  - Weighted Movement Index (WMI) computation
  - Distance-to-centroid classification
- `questionnaires/` — Editable PDF and LaTeX versions of subjective rating forms

### 👤 Participant Flow

- Consent form templates (ES/EN)
- Trial scheduling and counterbalancing strategy
- Rest-baseline → trajectory exposure → post-trial rating pipeline

---

## 📦 Intended Audience

Researchers and practitioners working on:

- Human–robot interaction (HRI)
- Physiological computing
- Human-centered reinforcement learning
- Affective robotics and ergonomics

---

## 📅 Roadmap

| Task                                | Status       |
|-------------------------------------|--------------|
| ROS + sensor synchronization code   | ✅ Complete  |
| Data analysis notebooks             | ✅ Complete  |
| Documentation and calibration guide | 🔄 In Progress |
| Public anonymized dataset           | 🔒 Pending ethics review |
| Full release                        | ⏳ Expected Q3 2025 |

---

## 📄 License

To be released under an open-source license (MIT/Apache 2.0). All human-subject data will follow GDPR-compliant anonymization.

---

## 📬 Contact

For updates or collaboration opportunities, contact:  
**gonzalez.asier@deusto.es**

---

> _"Robots that move with awareness of your heart rate — one step closer to truly human-centered automation."_
