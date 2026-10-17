<div align="center">

# Aryan Kumar Singh

**AI and machine learning researcher and engineer**

Multimodal health data, time series, deep learning, reinforcement learning, embodied AI.<br>
I develop models, test them with statistics, and ship them. Most of it is open source.

[![Portfolio](https://img.shields.io/badge/Portfolio-1A73E8?style=for-the-badge&logo=googlechrome&logoColor=white)](https://bewithaksingh.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aksingh06/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=IHw9I1cAAAAJ&hl=en)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0003-8791-1869)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aksingh5114@gmail.com)

</div>

---

## About

- MSc Artificial Intelligence, Berlin School of Business and Innovation. Thesis on reinforcement learning for robot motion and control in ROS 2 and MuJoCo, supervised by Dr. Fahmid Al Farid
- Three years in production machine learning and LLM systems before the MSc
- Two IEEE papers in 2024, one as first author on home health monitoring for early stroke prediction
- Founder of Barycenter Lab, a self funded lab for embodied AI. First product: Kiko, a companion robot
- Based in Berlin, Germany. Full time from February 2027

---

## Research

**NeuroPrism: Explainable Brain Health AI** · in progress, open source soon<br>
A multimodal framework that reads EEG, facial behaviour, speech and interview text to find markers of depression, ADHD and related conditions across five public clinical datasets. An EEG transformer pretrained on 26,000 plus clinical recordings and fine tuned on 1,274 subjects. A grounded language model turns feature attributions into plain language clinical reports.

**[kkt-forecast-combination](https://github.com/aksingh1608/kkt-forecast-combination)** · Apache 2.0<br>
Convex forecast combination and sparsity via KKT boundaries. 23 forecasting models, 5 energy time series datasets, 2 protocols, with Diebold-Mariano, Friedman and Nemenyi tests and effect sizes. The theory explains when the ensemble collapses onto tree learners. Code, results and figures for the paper in preparation with Dr. Fahmid Al Farid.

**Publications**<br>
First author, [Continuous Health Monitoring for Early Stroke Prediction at Home](https://ieeexplore.ieee.org/document/10739284), IEEE ICEECT 2024<br>
Co-author, [An Effective Approaches for Auto Bill Generator System](https://ieeexplore.ieee.org/document/10738927), IEEE ICEECT 2024

---

## Embodied AI and Barycenter Lab

Barycenter Lab is a self funded lab I started with two collaborators and two professors as mentors. No institution, no grant. We buy the parts, print the bodies and write the code ourselves. The long view: how people and robots can live and work together.

**Kiko** · hardware build in progress<br>
A companion robot that lives with its owner. It fuses camera, voice and touch input on an NVIDIA Jetson with ROS 2, follows its owner, talks, shows moods on an LCD face, and raises a camera mast to record reels. I lead the AI and computer vision side. We will record our own owner interaction dataset in home tests. Code in `kiki-v1`, team workspace in `kiko-hq`, site in `barycenterlab` (private while in build).

**[Apex](https://github.com/aksingh1608/Apex)**<br>
An interactive PyBullet environment with object semantics, and a goal oriented autonomous racing robot with monitoring in ROS 2.

**[turtlebot3-beacon](https://github.com/aksingh1608/turtlebot3-beacon)**<br>
ROS 2 work on the TurtleBot3 platform.

**[microduck](https://github.com/aksingh1608/microduck)**<br>
A tiny biped duck robot I am working through in Rust.

**[Robotics-Learning-](https://github.com/aksingh1608/Robotics-Learning-)**<br>
Teaching material for my live robotics course. Python fundamentals through OOP, NumPy, Pandas and plotting, with every example built on robots, sensors and lab workflows.

---

## Applied ML and Systems

**[floorline](https://github.com/aksingh1608/floorline)** · MIT<br>
Open source analytics and ML for warehouse and fulfilment centre operations. Takes data in, explores and cleans it, trains and explains models with XGBoost, SHAP and K-means. Connectors for PostgreSQL, Snowflake, Neo4j and TigerGraph. React, FastAPI, Google Cloud.

**[SpotZero](https://github.com/aksingh1608/SpotZero)** · MIT<br>
Few-shot visual defect inspection for factories. Learns a defect class from about 20 images with three swappable backends (PatchCore-light, anomalib PatchCore, YOLOv8). Runs on site on NVIDIA Jetson with ONNX and TensorRT, so no image leaves the building.

**[Dragoman](https://github.com/aksingh1608/Dragoman)**<br>
An offline bilingual speech translator, German and English, both ways. Built for a warehouse counter with no reliable internet. Runs on Termux on an aarch64 Android phone or a Linux laptop, with whisper.cpp for speech and a local llama server for translation, joined by a small FastAPI bridge. No cloud, no API keys.

**[AI-Interviewer](https://github.com/aksingh1608/AI-Interviewer)** · MIT<br>
A voice based technical interviewer. A candidate drops in a GitHub profile, has a live spoken conversation with an interviewer that already knows their background, and gets an instant score with feedback. TypeScript.

**[Purser](https://github.com/purser-sh/purser)** · Apache 2.0<br>
A local console that meters, caps and audits coding agents in one place. An append only hash chained token ledger, a budget governor with warn, prompt or hard stop, and a tamper evident audit log you can verify from the CLI. Works with Claude Code, Codex, Cursor CLI, Gemini CLI, Ollama and OpenAI compatible endpoints. Bound to loopback.

**[jobtrawl](https://github.com/aksingh1608/jobtrawl)** · MIT<br>
A job scraper that finds its own sources. Discovers research and student assistant postings across Germany and EU remote, scores them, and emails a ranked Excel sheet every morning. Python and Crawl4AI.

---

## Also on here

[PropertyAI](https://github.com/aksingh1608/PropertyAI), property price prediction and analytics · [credit card default modelling](https://github.com/aksingh1608/Predictive-Modelling-for-Credit-Card-Default-Using-Machine-Learning_IAI) · [fieldlens-sem2](https://github.com/aksingh1608/fieldlens-sem2)

---

## Stack

**Machine learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

**Robotics**

![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-1A73E8?style=for-the-badge)
![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=for-the-badge)
![Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)

**Languages and systems**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**MLOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## Stats

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=aksingh1608&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=aksingh1608&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## Now

- Building NeuroPrism and preparing the code release
- Printing and wiring Kiko at Barycenter Lab
- Finishing the KKT forecast combination paper
- Training RL policies for robot control in ROS 2 and MuJoCo for my thesis

---

## Reach me

- aksingh5114@gmail.com
- [bewithaksingh.com](https://bewithaksingh.com)
- [LinkedIn](https://www.linkedin.com/in/aksingh06/)
