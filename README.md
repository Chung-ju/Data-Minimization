<h1 align="center">
  <b>Least Sensing</b><br>
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
+ **Data quality minimization**:
+ **Performance-based data minimization**
  + Global data minimization: aims to minimize per-user data collection subject to meeting a target mean performance across users.
  + Per-user data minimization: aims to minimize per-user data collection subject to meeting a target performance for the minimum across all users.
+ **Breadth-based data minimization**: aims to minimize the number of features.
+ **Depth-based data minimization**: aims to minimize the overall amount of data collected for one data modality.

### Related papers

| Name        | Description | Type        | Link        |
| ----------- | ----------- | ----------- | ----------- |
| Operationalizing the Legal Principle of Data Minimization for Personalization. | Personalization, Recommender systems, Performance-based data minimization, Domain- and algorithm-specific heuristics | Conference | [SIGIR2020](https://dl.acm.org/doi/abs/10.1145/3397271.3401034) |
| Learning to Limit Data Collection via Scaling Laws: A Computational Interpretation for the Legal Principle of Data Minimization. | Performance-based data minimization, Depth-based data minimization, Data collection stopping criterion | Conference | [FAccT2022](https://dl.acm.org/doi/abs/10.1145/3531146.3533148) |
| Reviving Purpose Limitation and Data Minimisation in DataDriven Systems. | Performance-based data minimization | Journal | [TechReg2021](https://techreg.org/article/download/10986/version/10973/11960/20667) |
| Data Minimization for GDPR Compliance in Machine Learning Models. | Breadth-based data minimization,  | Journal | [AIEthics2022](https://link.springer.com/article/10.1007/s43681-021-00095-8) |
| Auditing Black-Box Prediction Models for Data Minimization Compliance. | Breadth-based data minimization, | Conference | [NIPS2021](https://proceedings.neurips.cc/paper/2021/file/ac6b3cce8c74b2e23688c3e45532e2a7-Paper.pdf) |

<!-- #### Data precision

#### Data sensitivity

#### Data predictability -->