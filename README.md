<h1 align="center">
  <b>Data Minimization</b><br>
</h1>

**Original paper**: [The Principle of Least Sensing: A Privacy-Friendly Sensing Paradigm for Urban Big Data Analytics.](https://dl.acm.org/doi/abs/10.1145/3522696)

<details>
<summary><strong>What is least sensing?</strong></summary>
<em>When conducting urban big data analysis involving personal data, a data processing entity must sense and collect only the minimum information necessary for the specified analysis purpose.</em>
</details>

<details>
<summary><strong>How to interpret "minimum"?</strong></summary>
The first and perhaps most intuitive explanation of minimum is on the <em>data quantity</em>, i.e., sensing the smallest amount of data required for the purpose. Actually, other interpretations exist, such as <em>data precision</em>, <em>data sensitivity</em>, and <em>data predictability</em>.
</details>

### Terminology explanation
+ **Data quantity minimization**
  + Data retention heuristics focusing on performance-related properties of data.
  + Retain the most recent data while discarding old data.
+ **Data quality minimization**: aims to reduce the quality of data without reducing its overall quantity.
+ **Performance-based data minimization**
  + Global data minimization: aims to minimize per-user data collection subject to meeting a target mean performance across users.
  + Per-user data minimization: aims to minimize per-user data collection subject to meeting a target performance for the minimum across all users.
+ **Breadth-based data minimization**: aims to minimize the number of features.
+ **Depth-based data minimization**: aims to minimize the overall amount of data collected for one data modality.
+ **Runtime data minimization**: aims to minimize newly collected data for analysis or prediction.
+ **Personalized data minimization**: aims to allow different users to reveal more or less about different aspects of their lives based on their own personal preference.
+ **Query-Driven Data Minimization**:

### Related papers

| Name        | Description | Type        | Link        |
| ----------- | ----------- | ----------- | ----------- |
| Operationalizing the Legal Principle of Data Minimization for Personalization. | Personalization, Recommender systems, Performance-based data minimization, Domain- and algorithm-specific heuristics | Conference | [SIGIR2020](https://dl.acm.org/doi/abs/10.1145/3397271.3401034) |
| Learning to Limit Data Collection via Scaling Laws: A Computational Interpretation for the Legal Principle of Data Minimization. | Performance-based data minimization, Depth-based data minimization, Data collection stopping criterion | Conference | [FAccT2022](https://dl.acm.org/doi/abs/10.1145/3531146.3533148) |
| Reviving Purpose Limitation and Data Minimisation in DataDriven Systems. | Performance-based data minimization, Data-driven systems | Journal | [TechReg2021](https://techreg.org/article/download/10986/version/10973/11960/20667) |
| Data Minimization for GDPR Compliance in Machine Learning Models. | Breadth-based data minimization, Runtime data minimization, Personalized data minimization, Knowledge distillation | Journal | [AIEthics2022](https://link.springer.com/article/10.1007/s43681-021-00095-8) |
| Auditing Black-Box Prediction Models for Data Minimization Compliance. | Breadth-based data minimization, | Conference | [NIPS2021](https://proceedings.neurips.cc/paper/2021/file/ac6b3cce8c74b2e23688c3e45532e2a7-Paper.pdf) |
| A Data Minimization Model for Embedding Privacy into Software Systems. | | Journal | [ComSec2019](https://www.sciencedirect.com/science/article/pii/S0167404818309106) |
| A Lightweight Scheme Exploiting Social Networks for Data Minimization According to the GDPR. | | Journal | [TCSS2021](https://ieeexplore.ieee.org/abstract/document/9330798) |
| Detecting Conflicts Between Data-Minimization and Security Requirements in Business Process Models. | | Conference | [ECMFA2018](https://link.springer.com/chapter/10.1007/978-3-319-92997-2_12) |
| A semi-automated BPMN-based framework for detecting conflicts between security, data-minimization, and fairness requirements. | Reusable domain-specific detection (conflict between needs and specifications), Fairness-related conflict,  | Journal | [SSM2020](https://link.springer.com/article/10.1007/s10270-020-00781-x) |
| A Siamese Adversarial Anonymizer for Data Minimization in Biometric Applications. | | Conference | [EuroS&P](https://ieeexplore.ieee.org/abstract/document/9229760) |
| Query-Driven Data Minimization with the DataEconomist. | | Conference | [EDBT2019](https://openproceedings.org/2019/conf/edbt/EDBT19_paper_365.pdf) |
| Towards Query-Driven Data Minimization. | | Conference | [LWDA2018](https://ceur-ws.org/Vol-2191/paper39.pdf) |

<!-- #### Data precision

#### Data sensitivity

#### Data predictability -->