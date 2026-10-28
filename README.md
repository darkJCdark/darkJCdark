# Jorge Chamorro

**Computer Science Engineering student at PUCP · Machine Learning · Full-Stack Development · Founder of DSC PUCP**

I build machine learning systems and full-stack products, and I document how every one of them was made. 9th-semester student (expected graduation: 2027-1), Beca 18 scholar, and currently taking Master's-level Data Mining and Intelligent Systems at PUCP.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jorgechamorrocayetano-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jorgechamorrocayetano/)
[![Email](https://img.shields.io/badge/Email-jchamorro%40pucp.edu.pe-D14836?logo=gmail&logoColor=white)](mailto:jchamorro@pucp.edu.pe)

---

## Competitions & Leadership

- **#AgentsEverywhere Global Hackathon (Peru) — 2nd Place.** Team *Astra Exploit 3.0*. Built **P.L.U.T.O.N.**, an AI agent that analyzes source code for insecure cryptographic primitives, proposes NIST-aligned post-quantum remediations and validates them in isolated sandboxes, working directly inside IDEs and GitHub pull requests.
- **DataFest 2026 — Finalist.** Team *Data Squad* (DSC PUCP). Each member built an independent pipeline with different models; we compared them and chose the submission together. Final: November 13–14.
- **DSC PUCP — Founder & Vice President.** Grew the student developer community from 40 to 80 members; run its software project portfolio, KPI dashboards in Power BI and a 24h hackathon.

---

## Featured Projects

Each project has its own README with the full method, data and results.

### [Traffic Forecasting with Graph ML](https://github.com/darkJCdark/traffic-forecasting-graph-machine-learning) · team project
Rebuilt the PEMS-04 sensor network as a graph (307 nodes, 340 edges) and compared STGCN, LSTTN and STAEformer under one frozen evaluation protocol. STAEformer reproduced its published MAE within 0.06, LSTTN cut error by up to 38.5% vs. STGCN, and PDFormer's failure was traced to an attention mask discarding 92.6% of node pairs on a sparse graph.
**AI:** Codex helped me debug tensor shapes; the graph construction and evaluation protocol are my design.
`PyTorch` `PyTorch Geometric` `NetworkX` `NumPy` `Pandas`

### [Dengue Egg Counting with CNNs](https://github.com/darkJCdark/cnn-ordinal-classifier-egg-ovitrap) · team project
Compared ResNet-50, InceptionV3 and EfficientNet-B3 as count regressors on 247 ovitrap images, mapped to four risk categories. Two-phase fine-tuning with Huber loss, 5 runs per architecture: ResNet-50 reached MAE 14.12 and 80.8% category accuracy, with no errors between non-adjacent categories.
**AI:** Codex generated the base training script; I defined the two training phases and the evaluation metrics.
`PyTorch` `ResNet-50` `InceptionV3` `EfficientNet-B3`

### [Fraud Detection in Banking Transactions](https://github.com/darkJCdark/fraud-detection-bank-transactions-ml) · team project
Random Forest vs. Logistic Regression on 14,446 transactions, tuned with GridSearchCV to maximize recall: **95.3% recall** (precision 0.977) against 44.5% for the linear baseline.
**AI:** Claude Code reviewed my pipeline and flagged that I scaled the data before splitting train/test; I fixed the leak and retrained.
`Python` `scikit-learn` `Pandas` `NumPy`

### [CoreMen — E-commerce Platform](https://github.com/ta-ingenieria-software/core-men) · UX/UI + architecture + full stack
Designed the product end to end in Figma (design system and user flows), defined the software architecture and built it as a monorepo: role-based JWT auth in HttpOnly cookies (admin / merchant / client), an immutable audit log and Stripe payments.
**AI:** Claude Code generated the first version of the modules and Codex the tests; I rewrote authentication and the discount logic.
`Figma` `Next.js 16` `React 19` `Tailwind` `shadcn/ui` `NestJS` `Prisma` `PostgreSQL` `Stripe` `Docker`

### [SIRGEP — Public Space & Ticket Reservations](https://github.com/darkJCdark/sirgep-web) · full stack
Layered Java 21 SOAP backend and ASP.NET (C#) frontend on MySQL (AWS), with PDF receipts and reports (iTextSharp), Excel exports (Apache POI), a sales dashboard, email notifications (Jakarta Mail) and AES-protected credentials. 625 commits.
**AI:** Codex drafted the initial SOAP service skeletons; I adjusted the contracts and queries to my own tables.
`Java 21` `SOAP` `Maven` `ASP.NET` `C#` `MySQL` `Apache POI` `iTextSharp` `Jakarta Mail`

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C%23](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)

---

## Languages

Spanish (native) · English (B1)

## Contact

[LinkedIn](https://www.linkedin.com/in/jorgechamorrocayetano/) · [jchamorro@pucp.edu.pe](mailto:jchamorro@pucp.edu.pe)
