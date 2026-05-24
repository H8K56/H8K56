<div align="center">

<!-- ─── HEADER ─── -->

# `> hussein.khadra --status`

### 🚀 Software Engineer · AI/ML · Robotics · Backend Systems

*Computer Science engineer shipping production systems where drones, models, and microservices have to actually work — not just compile.*

<br>

**🇨🇾 Based in Nicosia, Cyprus** &nbsp;·&nbsp; **🎓 University of Nicosia (Jun 2026)** &nbsp;·&nbsp; **✉️ [khadrahussein4@gmail.com](mailto:khadrahussein4@gmail.com)** &nbsp;·&nbsp; **💼 [LinkedIn](https://www.linkedin.com/in/hussein-khadra-lm/)**

</div>

---

## 🧠 whoami

```yaml
name:        Hussein Khadra
role:        Software Engineer — AI/ML · Robotics · Backend
education:   B.S. Computer Science & Engineering @ University of Nicosia (Jun 2026)
location:    Nicosia, Cyprus
focus:       Production-grade systems that bridge research and reality
stack:       Linux + Docker + ROS 2 → TS/Node services → PyTorch models
currently:   Hunting graduate / new-grad roles in applied ML & robotics
```

I work at the seam between **applied ML** and **shipped infrastructure** — the layer where a paper-grade idea has to survive containers, networks, noisy data, and a real user on the other end. Recent ground covered: a Cypriot-dialect ASR dataset built from scratch, an OCR preprocessing pipeline that handled documents engineers tried to feed it sideways, and a 5-UAV reinforcement-learned swarm I'm genuinely proud of.

---

## 🚀 Featured Work

<br>

### 🛸 A.U.R.A — Autonomous Urban Reconnaissance Array
> **Multi-UAV disaster-relief swarm.** Five autonomous drones establish a self-healing WiFi mesh across collapsed infrastructure to restore connectivity for civilians and first responders.

**What it does** — Trained a PPO reinforcement-learning policy for swarm positioning against a log-distance path-loss network simulator, then dropped it into PX4 SITL + Gazebo Classic to see if the physics agreed with the math. They did.

**Results**

| Metric | Value |
|---|---|
| 🛰️ Mesh coverage on Baseline Controller | **96–99%** |
| 📡 Aggregate throughput | **114.7 Mbps** |
| ⚡ Latency | **6 ms** |
| 🚁 Swarm size | **5 UAVs** |

**Stack** — `ROS 2` · `PX4 SITL` · `Gazebo` · `PyTorch (PPO)` · `Docker` · `C++` · `Python`

🔗 [**github.com/H8K56/A.U.R.A**](https://github.com/H8K56/A.U.R.A)

<br>

### 🎙️ Cypriot Dialect ASR Dataset Pipeline · *@ Abasis.AI*
> End-to-end ETL producing a **novel Cypriot-dialect speech corpus** from broadcast TV, radio, and archival recordings — sourced, segmented, normalized, and formatted for ASR fine-tuning.

Designed reproducible audio preprocessing (format normalization, noise filtering, alignment) for dataset-scale model ingestion, and shipped the backend ingestion + storage for **voiceofcyprus.org**, the project's volunteer crowd-sourced annotation platform.

**Stack** — `Python` · `Audio Preprocessing` · `ETL` · `ASR` · `Backend`

🔗 (https://github.com/abasis-ltd)

<br>

### 🎭 Project Pavoculus — Real-Time 3D Face Overlay
> Real-time CV pipeline: **facial keypoint detection → 3D landmark projection → per-frame mask rendering**. Optimized for low-latency video streams with angle and occlusion handling. The backend (ChickenVision Server 🐔☁️) handles the heavy lifting — frame processing, pose estimation, and the brain behind the cluck.

**Stack** — `Python` · `OpenCV` · `Facial Keypoint Detection` · `pytorch-openpose`

🔗 [**github.com/projectPavoculus/chickenvision-server**](https://github.com/projectPavoculus/chickenvision-server) &nbsp;·&nbsp; 🔗 [**pytorch-openpose**](https://github.com/H8K56/pytorch-openpose)

<br>

### 📄 Document Edge Detection & OCR Pipeline · *@ Goldman Solutions*
> Production OCR preprocessing system using **contour detection + Hough transforms + perspective warping**. Engineered for the documents nobody wants — skewed, distorted, shadowed, photographed at 30° on a kitchen table.

Benchmarked third-party CV stacks, picked the winner, integrated into the production OCR path. Per-document processing overhead dropped, accuracy on the ugly inputs went up.

**Stack** — `OpenCV` · `scikit-image` · `PyTesseract` · `Python`

<br>

### 🗂️ Document Metadata Extractor · *@ University of Nicosia*
> Production TypeScript/Node.js microservice for metadata extraction from documents and video, backed by **Amazon S3** and consumed by the university student portal. Pluggable extractor architecture, Swagger UI'd, deployed at university scale.

**Stack** — `TypeScript` · `Node.js` · `AWS S3` · `Swagger` · `REST`

<br>

### 🌱 Zelara Plant — ML Microservice
> Microservice worker for the Zelara project — **plant species identification + care advice** from image inputs. ML-backed classification stitched into a microservice architecture.

**Stack** — `Python` · `ML Inference` · `Microservices`

🔗 [**github.com/zelara-ai/zelara-plant**](https://github.com/zelara-ai/zelara-plant)

---

## ⚡ Tech Stack

<table>
<tr>
<td valign="top" width="50%">

#### 💻 Languages

<p>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40" alt="Python" title="Python" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" height="40" alt="TypeScript" title="TypeScript" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" height="40" alt="JavaScript" title="JavaScript" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="40" height="40" alt="C++" title="C++" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" height="40" alt="Java" title="Java" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="40" height="40" alt="SQL" title="SQL" />
</p>

#### 🤖 AI / ML

<p>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" width="40" height="40" alt="PyTorch" title="PyTorch" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" width="40" height="40" alt="TensorFlow" title="TensorFlow" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" width="40" height="40" alt="OpenCV" title="OpenCV" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scikitlearn/scikitlearn-original.svg" width="40" height="40" alt="scikit-learn / scikit-image" title="scikit-learn / scikit-image" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" width="40" height="40" alt="NumPy" title="NumPy" />
</p>

🧠 Also: **PPO / Reinforcement Learning** · **ASR pipelines**

#### 🤖 Robotics

<p>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ros/ros-original.svg" width="40" height="40" alt="ROS 2" title="ROS 2" />
</p>

🛸 Also: **Gazebo Classic** · **PX4 SITL**

</td>
<td valign="top" width="50%">

#### 🌐 Backend

<p>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="40" height="40" alt="Node.js" title="Node.js" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" width="40" height="40" alt="Flask" title="Flask" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" width="40" height="40" alt="Express" title="Express" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swagger/swagger-original.svg" width="40" height="40" alt="Swagger" title="Swagger" />
</p>

🌐 Also: **REST APIs** · **Microservices**

#### ☁️ Cloud & Infra

<p>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" width="40" height="40" alt="AWS" title="AWS (S3, Lambda)" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40" height="40" alt="Docker" title="Docker" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40" height="40" alt="Linux" title="Linux" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="40" height="40" alt="Git" title="Git" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" width="40" height="40" alt="GitHub" title="GitHub" />
</p>

#### 🗄️ Data

<p>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="40" height="40" alt="PostgreSQL" title="PostgreSQL" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="40" height="40" alt="MySQL" title="MySQL" />
</p>

📊 Also: **ETL pipelines** · **Audio + image preprocessing**

</td>
</tr>
</table>

---

## 💼 Career Path

<table>
<tr><td>

<sub>**📍 MOST RECENT**</sub>

### 🎙️ Research & Backend Developer
**Abasis.AI** · Nicosia, Cyprus
<sub>`Jul 2025 — Aug 2025`</sub>

Built ETL pipelines producing a novel Cypriot-dialect speech corpus from broadcast TV, radio, and archival recordings. Designed reproducible audio preprocessing (format normalization, noise filtering, alignment) for dataset-scale ASR ingestion. Shipped the ingestion + storage backend for **voiceofcyprus.org**, the crowd-sourced annotation platform.

`Python` · `ETL` · `Audio Preprocessing` · `ASR` · `Backend`

</td></tr>

<tr><td>

### 📄 Backend / Computer Vision Intern
**Goldman Solutions & Services** · Nicosia, Cyprus
<sub>`Feb 2025 — Mar 2025`</sub>

Built a document edge-detection pipeline using contour detection, Hough transform, and perspective warping — measurably lifting OCR accuracy on skewed and distorted scans. Benchmarked third-party CV libraries and integrated the chosen stack into the production OCR path, reducing per-document overhead.

`OpenCV` · `scikit-image` · `PyTesseract` · `Python`

</td></tr>

<tr><td>

### 🎓 Student Assistant Developer
**University of Nicosia** · Nicosia, Cyprus
<sub>`Oct 2022 — Jun 2024`</sub>

Designed and deployed a TypeScript/Node.js microservice for metadata extraction from documents and video, backed by Amazon S3 and consumed by the university student portal. Delivered full-stack CRUD modules alongside senior engineers, integrated Swagger UI for live API documentation, and championed third-party libraries and AWS services adopted into production.

`TypeScript` · `Node.js` · `AWS S3` · `Swagger` · `Microservices`

</td></tr>
</table>

---

## 🎓 Education & Credentials

**B.S. Computer Science & Engineering** — University of Nicosia · Expected Jun 2026 · GPA **3.22 / 4.0**
Data Structures · Database Management · Networks & Data Communication · Software Development · Discrete Mathematics · Linear Algebra

**Certifications**
- 🪪 IBM AI Applications with Python and Flask — Coursera *(Nov 2024)*
- 🪪 IBM Software Engineering Essentials — Coursera *(Sep 2024)*

**Competitions & Hackathons**
- 🏆 Bank of Cyprus Fintech Hackathon **6.0** *(2025)* & **5.0** *(2024)*
- 🏆 AI for the Common Good — British Council × Hack Cyprus *(2023)*

---

## 🎯 Currently

```
🛸 Iterating on multi-agent RL coordination beyond A.U.R.A
🎙️ Thinking about low-resource ASR for under-represented dialects
🧪 Building things that survive contact with production
☕ Open to graduate / new-grad roles in applied ML, robotics, or backend
```

---

<div align="center">

### 💬 Let's talk

If your stack involves drones, models, pipelines, or just well-engineered backends — I'd love to hear about it.

**✉️ [khadrahussein4@gmail.com](mailto:khadrahussein4@gmail.com)** &nbsp;·&nbsp; **💼 [LinkedIn](https://www.linkedin.com/in/hussein-khadra-lm/)**

</div>
