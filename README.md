<div align="center">

# Aryan Kumar Singh

**Physical AI and robotics researcher**

I build robots and sensing systems that can be trusted around people.<br>
Physical AI is my field. Brain health at home is where I test it.

[![Portfolio](https://img.shields.io/badge/Portfolio-1A73E8?style=for-the-badge&logo=googlechrome&logoColor=white)](https://bewithaksingh.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aksingh06/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=IHw9I1cAAAAJ&hl=en)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0003-8791-1869)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aksingh5114@gmail.com)

</div>

---

## About

I research and build AI that works in the real world: robots that act safely around people, and models that read brain health signals at home.

- MSc Artificial Intelligence, Berlin School of Business and Innovation. Thesis on reinforcement learning for robot motion and control in ROS 2 and MuJoCo
- Supervised by Dr. Fahmid Al Farid on AI and computer vision, and by Dr. Syed Arslan Abbas Rizvi on robotics, mechatronics and control
- AI and Robotics Researcher at Barycenter Lab, Berlin, where I build Kiko, a home companion robot, end to end
- Lead of NeuroPrism, an explainable brain health model built on EEG, facial behaviour, speech and text, and of NeuroPrism Diary, the app that collects its data
- Three years in production machine learning and LLM systems before the MSc
- Two IEEE papers in 2024, one as first author on home health monitoring for early stroke prediction
- Based in Berlin, Germany. Open to research positions (PhD, research assistant) and research engineering roles. Part time now, full time from February 2027

---

## Physical AI

**Kiko** · Barycenter Lab · hardware build in progress<br>
A companion robot that lives with its owner. It knows who its owner is, follows them, talks, shows moods on an LCD face and reacts to touch. I build the whole robot: the body in Fusion 360 and 3D printing, the circuits, wiring and boards (ESP32-S3, BNO085 IMU, MPR121 touch, ST3215 servos), and the vision and behaviour stack in ROS 2 on an NVIDIA Jetson. Simulation first in Gazebo, then hardware. We record our own owner interaction dataset in home tests. Code in `kiko-v1` (private while in build). Site: [barycenterlab.de](https://www.barycenterlab.de).

**[Apex](https://github.com/aksingh1608/Apex)**<br>
An interactive PyBullet environment with object semantics, and a goal driven autonomous racing robot with live monitoring in ROS 2.

**[turtlebot3-beacon](https://github.com/aksingh1608/turtlebot3-beacon)**<br>
ROS 2 work on the TurtleBot3 platform.

---

## Brain health at home

**NeuroPrism: Explainable Brain Health AI** · in progress, open source soon<br>
A multimodal framework that reads EEG, facial behaviour, speech and interview text to find markers of depression, ADHD and related conditions across five public clinical datasets. An EEG transformer pretrained on 26,000 plus clinical recordings and fine tuned on 1,274 subjects. A grounded language model turns feature attributions into plain language clinical reports. Research project, not a medical device.

**NeuroPrism Diary** · Flutter · in build<br>
The data side of NeuroPrism. A privacy first app for two minutes a day: a voice note, a text check in and a mood score, with PHQ-9 and GAD-7 questionnaires and optional resting EEG from a Muse 2 headband (4 channels, 256 Hz, EDF). Voice is processed on the phone and only features leave the device. No name, no email, one tap deletion. Each person is compared with their own 14 day baseline, not with other people.

**Home stroke monitoring** · IEEE ICEECT 2024, first author<br>
A home system that flags early stroke risk from continuous body signals. [Paper](https://ieeexplore.ieee.org/document/10739284).

---

## Evaluation

**[kkt-forecast-combination](https://github.com/aksingh1608/kkt-forecast-combination)** · Apache 2.0<br>
Convex forecast combination and sparsity via KKT boundaries. 23 forecasting models, 5 energy time series datasets, 2 protocols, with Diebold-Mariano, Friedman and Nemenyi tests and effect sizes. The theory explains when the ensemble collapses onto tree learners. Code, results and figures for the paper in preparation with Dr. Fahmid Al Farid.

---

## Applied ML and systems

**[SpotZero](https://github.com/aksingh1608/SpotZero)** · MIT<br>
Few-shot visual defect inspection for factories. Learns a defect class from about 20 images with three swappable backends (PatchCore-light, anomalib PatchCore, YOLOv8). Runs on site on NVIDIA Jetson with ONNX and TensorRT, so no image leaves the building.

**[floorline](https://github.com/aksingh1608/floorline)** · MIT<br>
Open source analytics and ML for warehouse and fulfilment centre operations. Takes data in, explores and cleans it, trains and explains models with XGBoost, SHAP and K-means. Connectors for PostgreSQL, Snowflake, Neo4j and TigerGraph.

**[Purser](https://github.com/purser-sh/purser)** · Apache 2.0<br>
A local console that meters, caps and audits coding agents in one place. An append only hash chained token ledger, a budget governor with warn, prompt or hard stop, and a tamper evident audit log you can verify from the CLI. Works with Claude Code, Codex, Cursor CLI, Gemini CLI, Ollama and OpenAI compatible endpoints.

**[Dragoman](https://github.com/aksingh1608/Dragoman)**<br>
An offline German and English speech translator, both ways. Runs on Termux on an Android phone or a Linux laptop, with whisper.cpp for speech and a local llama server for translation. No cloud, no API keys.

**[AI-Interviewer](https://github.com/aksingh1608/AI-Interviewer)** · MIT<br>
A voice based technical interviewer. A candidate drops in a GitHub profile, has a live spoken conversation with an interviewer that already knows their background, and gets an instant score with feedback.

**[jobtrawl](https://github.com/aksingh1608/jobtrawl)** · MIT<br>
A job scraper that finds its own sources. Discovers research and student assistant postings across Germany and EU remote, scores them, and emails a ranked Excel sheet every morning.

---

## Teaching

**[Robotics-Learning-](https://github.com/aksingh1608/Robotics-Learning-)**<br>
Material for my live robotics course. Python fundamentals through OOP, NumPy, Pandas and plotting, with every example built on robots, sensors and lab workflows.

**[PropertyAI](https://github.com/aksingh1608/PropertyAI)**<br>
Student capstone I designed: property price prediction and analytics.

---

## Publications

First author, [Continuous Health Monitoring for Early Stroke Prediction at Home](https://ieeexplore.ieee.org/document/10739284), IEEE ICEECT 2024<br>
Co-author, [An Effective Approaches for Auto Bill Generator System](https://ieeexplore.ieee.org/document/10738927), IEEE ICEECT 2024<br>
In preparation, Convex Forecast Combination and Sparsity via KKT Boundaries, with Dr. Fahmid Al Farid, 2026

---

## Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Robotics**

![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-1A73E8?style=for-the-badge)
![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=for-the-badge)
![Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion_360-FF6B00?style=for-the-badge&logo=autodesk&logoColor=white)

**Machine learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

**Systems**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)

---

## Stats

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=aksingh1608&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

</div>

---

## Now

- Assembling Kiko version one: printed body, wiring, ROS 2 integration on the Jetson
- Building NeuroPrism and preparing the code release
- Finishing the KKT forecast combination paper
- Training RL policies for robot control in ROS 2 and MuJoCo for my thesis

---

## Reach me

- aksingh5114@gmail.com
- [bewithaksingh.com](https://bewithaksingh.com)
- [LinkedIn](https://www.linkedin.com/in/aksingh06/)
