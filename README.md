# 👨‍💻 Jorge Chamorro — Software Developer & ML/DL

Computer Engineering student at PUCP, building full-stack products and training deep learning models. Currently taking Advanced Data Mining and Intelligent Systems as part of the Master's in Computer Science at PUCP, alongside my undergraduate coursework.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jorgechamorrocayetano-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jorgechamorrocayetano/)
[![Email](https://img.shields.io/badge/Email-jchamorro%40pucp.edu.pe-D14836?logo=gmail&logoColor=white)](mailto:jchamorro@pucp.edu.pe)

---

## 🌎 About Me

- 🎓 8th-semester Computer Engineering student at PUCP, currently taking Master's-level coursework in Data Mining and Intelligent Systems.
- 📚 *Beca 18 – Pronabec* scholar.
- 🚀 Founder & VP of Strategic Planning at **DSC PUCP**, a student developer community I grew from 40 to 80 members — I run its software project portfolio and direct its hackathons.
- 🌐 Languages: Spanish (native), English (elementary).
- 🇵🇪 Based in Lima, Peru.

I build software end-to-end — data model to UI — and apply the same rigor to training and evaluating deep learning models, with an emphasis on modular architecture, reproducibility, and documentation good enough for someone else to pick up the project.

---

## 🚀 Technologies & Tools

**Languages:** Python · TypeScript · JavaScript · Java · C# · C · C++ · Go · R

**Machine Learning / Deep Learning:** PyTorch · Scikit-learn · Pandas · NumPy · CNNs (ResNet, InceptionV3, EfficientNet) · Graph Neural Networks · torchvision · torch-geometric

**Web Development:** Next.js · React · Tailwind CSS · NestJS · Express · ASP.NET Web Forms · REST & SOAP APIs

**Databases:** PostgreSQL (Prisma ORM) · MySQL · SQL Server · Oracle

**Infrastructure:** Docker · Git & GitHub · AWS Academy (EC2, VPN, security, AD DS) · Ubuntu · Linux Mint

**Dev & Design Tools:** VS Code, Visual Studio Community, NetBeans, RStudio, Google Colab, Figma, Draw.io, Miro

**Management & Productivity:** Jira, ClickUp, Freedcamp, Google Workspace

---

## 📖 Key Knowledge

- **Machine Learning & Deep Learning:** end-to-end pipelines — preprocessing, class imbalance, dimensionality reduction, model evaluation, CNNs, GNNs, fine-tuning strategies.
- **Software Architecture & Documentation:** C4 model, UML, layered/modular design, REST & SOAP.
- **Requirements Engineering:** use cases, user stories, prototyping, validation of functional/non-functional requirements.
- **Information Security:** ISO/IEC 27001:2022 risk management, ISO/IEC 27002 controls, business continuity (RPO/RTO).
- **Software Testing:** TDD/BDD principles, API testing (REST/SOAP).
- **IT Service Management (ITSM):** service lifecycle, incident and change management, IT asset management.

---

## 📂 Featured Projects

### 🔗 [Dengue Vector Egg Density Classifier](https://github.com/darkJCdark/cnn-ordinal-classifier-egg-ovitrap)
*Comparative CNN study for entomological surveillance*

Modular PyTorch pipeline comparing ResNet-50, InceptionV3, and EfficientNet-B3 to count *Aedes aegypti* eggs from ovitrap images and map them to MINSA's epidemiological risk categories (Low/Medium/High/Very High).

- Two-phase fine-tuning (frozen encoder warm-up → targeted unfreezing) with Huber loss to handle extreme count skew.
- 5 independent cross-validation runs per architecture for stability testing.
- **Results:** ResNet-50 reached a 14-egg MAE; EfficientNet-B3 was the strongest on extreme-density samples, with errors limited to adjacent risk categories — no dangerous false negatives.
- Team project (5 authors).

---

### 🔗 Hannah — AI Companion *(backend repo link pending — organization: [github.com/Hannah-AI-companion](https://github.com/Hannah-AI-companion))*
*Backend & RAG orchestration*

Built the backend and orchestration layer for a local, low-latency AI companion: a FastAPI gateway routing between a fast and a slow model, hybrid retrieval over ChromaDB (vector) and Neo4j (knowledge graph), and a background pipeline that extracts and stores facts from conversation in real time. Published model card on Hugging Face (`HannahTeam/Hannah-AI-Companion`).

---

### 🔗 CoreMen — B2B/B2C E-commerce Platform *(repo link pending)*
*E-commerce for a Gamarra textile manufacturer*

Designed the PostgreSQL data model with Prisma and versioned migrations, documented the architecture with the C4 model, and built the NestJS API with a JWT-secured, role-based backoffice and an immutable audit log. Built the Next.js/React storefront with garment customization and volume-discount quoting for wholesale buyers.

---

### 🔗 [SIRGEP — Public Space & Ticket Reservations](https://github.com/darkJCdark/sirgep-web)
*Integrated system for municipal space reservations and event ticketing*

- **Backend:** Java 21, Maven, SOAP web services on Ubuntu — modular architecture (domain, data access, business logic, services).
- **Frontend:** ASP.NET Web Forms (C#, Bootstrap) on Windows — user, sales, and reporting modules.
- **Database:** MySQL on AWS Academy, AES/MD5/ChaCha20-encrypted credentials.
- **Features:** online reservations, ticket purchases (card, Yape, Plin), automatic notifications, sales dashboard, PDF/Excel exports.

---

### 🔗 [Fraud Detection in Banking Transactions](https://github.com/darkJCdark/fraud-detection-bank-transactions-ml)
*Predictive fraud model for financial institutions*

Compared Logistic Regression and Random Forest (with `GridSearchCV` hyperparameter tuning) on transaction data. **Random Forest reached 95% recall**, catching almost all fraud cases. Documented ethical implications: privacy, bias, and robustness to adversarial attacks.

---

### 🔗 Traffic Forecasting with Graph Machine Learning *(repo link pending)*
*Coursework in Graph Machine Learning*

Built a Graph Neural Network pipeline (PyTorch Geometric) to forecast traffic patterns, applying node/edge representation learning to a real transportation network.

---

<details>
<summary><b>Other academic projects</b></summary>

**[Pre-learned Chunks in Visual Working Memory](https://github.com/darkJCdark/prelearned-chunks-working-memory-psychopy)** — Replication of Experiment 2 from Allen, DeStefano & Brady (2021): a PsychoPy task testing whether familiar letter chunks preserve perceptual detail (font) alongside identity, contrasting content-free vs. distributed/hierarchical memory models.

**Four-Wheeled Mobile Robot (ROS2 + Gazebo)** — Group project modeling and simulating a four-wheeled robot: URDF description, collision/inertial properties, and a Gazebo/RViz launch pipeline.

</details>

---

## 💡 Soft Skills

Commitment · Teamwork · Effective communication · Adaptability · Working under pressure · Empathy · Tenacity

## 🎵 Hobbies

Programming personal projects · Music · Video games · Cinema

## 🎯 Goals

- Ship production-grade software with the same rigor I apply to model evaluation.
- Keep every project reproducible: clear setup, versioned data/config, documented results.
- Combine technical depth in ML/DL with product-level full-stack ownership.

---

## 📫 Contact

- **LinkedIn:** [Jorge Chamorro](https://www.linkedin.com/in/jorgechamorrocayetano/)
- **Email:** jchamorro@pucp.edu.pe

> "Engineering not only solves problems, it also builds futures."
