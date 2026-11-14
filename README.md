<div align="center">

# Aryan Kumar Singh

**Physical AI and robotics researcher · Berlin**

I build robots and sensing systems that can be trusted around people.<br>
Perception and control on small hardware, tested in simulation first and then on the real robot.

[![Portfolio](https://img.shields.io/badge/Portfolio-aryankumarsingh.dev-1A73E8?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.aryankumarsingh.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aksingh06/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=IHw9I1cAAAAJ&hl=en)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0003-8791-1869)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aksingh5114@gmail.com)

</div>

---

## About

- **MSc Artificial Intelligence** at the Berlin School of Business and Innovation (BSBI), degree awarded by the University for the Creative Arts (UCA), UK. Expected Aug 2027.
- **Volunteer researcher, co-founder and technical lead at [Barycenter Lab](https://www.barycenterlab.de)**, Berlin, since Oct 2026. I lead a team of three building Kiko, a home companion robot.
- **Mentors:** [Dr. Fahmid Al Farid](https://scholar.google.com/citations?user=trrQoEYAAAAJ) (AI and computer vision) and [Dr. Syed Arslan Abbas Rizvi](https://scholar.google.com/citations?user=777mb4wAAAAJ) (robotics, mechatronics and control).
- **Three years in production ML and LLM systems** before the MSc: Founding AI Engineer at EMRA AI, and Product Manager and Technical Lead at Mioneer, where I led the retrieval work that raised accuracy on real user queries from 60% to 89%.
- **Publications:** two IEEE ICEECT 2024 papers (one as first author) and a paper under review at an IEEE Transactions journal.
- **Open to** research internships, working student and HiWi roles now, and full-time research engineering roles from February 2027.

---

## Core work

### Physical AI

**Kiko: home companion robot** · Barycenter Lab · in build, code private for now<br>
A small home robot that learns to recognize its owner and keeps recognizing them for weeks, using sight, voice and touch, all on the robot with no cloud. Vision, speech and memory run on an NVIDIA Jetson Orin Nano with ROS 2. An ESP32-S3 runs the body with a 300 ms safety watchdog. The body is designed in CadQuery (early parts in Fusion 360): 5 revisions, 207 screw joints, 14 PETG plates. Every behaviour is tested in Gazebo and NVIDIA Isaac Sim before it runs on the robot.

**[Apex](https://github.com/aksingh1608/Apex)** · PyBullet, ROS 2<br>
An interactive PyBullet world with object semantics and a goal-driven autonomous racing robot with live monitoring in ROS 2. 3 laps with zero contact events, 42 automated tests.

**[Beacon](https://github.com/aksingh1608/turtlebot3-beacon)** · ROS 2, Gazebo<br>
A vision-guided TurtleBot3 that finds a red marker with its camera, centres it, drives to it and stops. Ten scripted trials with occlusion, every run logged, misses included. 15 tests.

### Research and evaluation

**[Convex forecast combination via KKT boundaries](https://github.com/aksingh1608/kkt-forecast-combination)** · under review, IEEE Transactions<br>
23 forecasting models on 5 energy time series datasets under 2 protocols, checked with Diebold-Mariano, Friedman and Nemenyi tests and effect sizes. A KKT boundary explains when a convex ensemble collapses onto tree learners. 36 tests, Apache 2.0.

**[Glidepath](https://github.com/aksingh1608/glidepath)** · calibrated forecasting<br>
Forecasts aircraft landing times from open ADS-B tracks with calibrated 80% intervals, and measures when a forecast becomes trustworthy: a trust lead of 7.2 minutes against 1.4 for the baseline. 17 tests.

**NeuroPrism: explainable brain health AI** · in progress, code release planned<br>
A multimodal model that reads EEG, facial behaviour, speech and interview text to find markers of depression and ADHD across five public clinical datasets, and explains its findings in plain language. A companion app, NeuroPrism Diary, collects two minutes of consented data a day. Research project, not a medical device.

### Systems on the edge

**[SpotZero](https://github.com/aksingh1608/SpotZero)** · Jetson, TensorRT · MIT<br>
Few-shot visual defect inspection that learns a defect class from about 20 images and runs on site on a Jetson, so no image leaves the building. Three swappable backends: PatchCore-light, anomalib PatchCore and YOLOv8.

**[Purser](https://github.com/purser-sh/purser)** · sole author · Apache 2.0<br>
A local console that meters, caps and audits coding agents across 8 providers, with a hash-chained token ledger, a budget governor and a tamper-evident audit log you can verify from the CLI. 300+ tests.

More projects, including FieldLens, Dragoman and jobtrawl, are on my [portfolio](https://www.aryankumarsingh.dev/en/research).

---

## Publications

- **Under review:** A. K. Singh, F. Al Farid, et al. *Convex Forecast Combination and Sparsity via KKT Boundaries: Multi-Dataset Benchmarking in Energy Time Series.* Submitted to an IEEE Transactions journal, 2026.
- **First author:** [Continuous Health Monitoring for Early Stroke Prediction at Home](https://ieeexplore.ieee.org/document/10739284), IEEE ICEECT 2024.
- **Co-author:** [An Effective Approaches for Auto Bill Generator System](https://ieeexplore.ieee.org/document/10738927), IEEE ICEECT 2024.

---

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Robotics and simulation**

![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Isaac Sim](https://img.shields.io/badge/NVIDIA_Isaac_Sim-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Newton](https://img.shields.io/badge/NVIDIA_Newton-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Warp](https://img.shields.io/badge/NVIDIA_Warp-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-1A73E8?style=for-the-badge)
![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=for-the-badge)
![PyBullet](https://img.shields.io/badge/PyBullet-3B7DDD?style=for-the-badge)

**Hardware**

![Jetson](https://img.shields.io/badge/Jetson_Orin_Nano-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32--S3-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![CadQuery](https://img.shields.io/badge/CadQuery-2F4F4F?style=for-the-badge)
![Fusion 360](https://img.shields.io/badge/Fusion_360-FF6B00?style=for-the-badge&logo=autodesk&logoColor=white)

**Machine learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![PyG](https://img.shields.io/badge/PyTorch_Geometric_(GNNs)-3C2179?style=for-the-badge&logo=pyg&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**Systems**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Learning now:** CUDA

---

## Now

- Finishing Kiko v1 for its first public demo
- KKT forecast combination paper under review at an IEEE Transactions journal
- Building NeuroPrism and preparing its code release
- Secure RAG for Banking: threat modelling, guardrails and red-teaming for an LLM assistant

---

## Reach me

[aryankumarsingh.dev](https://www.aryankumarsingh.dev) · [LinkedIn](https://www.linkedin.com/in/aksingh06/) · aksingh5114@gmail.com
