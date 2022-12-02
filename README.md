<h1 align="center">
  <b>Data Minimization</b><br>
</h1>

### 1. Introduction

xxx

### 2. Different stage

#### Stage 1: data collection

**Original paper**: [The Principle of Least Sensing: A Privacy-Friendly Sensing Paradigm for Urban Big Data Analytics.](https://dl.acm.org/doi/abs/10.1145/3522696)

<details>
<summary><strong>What is least sensing?</strong></summary>
<em>When conducting urban big data analysis involving personal data, a data processing entity must sense and collect only the minimum information necessary for the specified analysis purpose.</em>
</details>

<details>
<summary><strong>How to interpret "minimum"?</strong></summary>
The first and perhaps most intuitive explanation of minimum is on the <em>data quantity</em>, i.e., sensing the smallest amount of data required for the purpose. Actually, other interpretations exist, such as <em>data precision</em>, <em>data sensitivity</em>, and <em>data predictability</em>.
</details>

#### Stage 2: data inference

#### Stage 3: data autit

### 3. Terminology explanation
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

### 4. Related papers
<table>
  <tbody>
    <tr>
      <th>Name</th>
      <th align="center">Description</th>
      <th align="center">Stage</th>
      <th align="center">Type</th>
      <th align="center">Link</th>
    </tr>
    <tr>
      <td align="left">Operationalizing the Legal Principle of Data Minimization for Personalization.</td>
      <td align="left">
        <ul>
          <li>Personalization</li>
          <li>Recommender systems</li>
          <li>Performance-based data minimization</li>
          <li>Domain- and algorithm-specific heuristics</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Conference</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/abs/10.1145/3397271.3401034">
          SIGIR2020
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Learning to Limit Data Collection via Scaling Laws: A Computational Interpretation for the Legal Principle of Data Minimization.</td>
      <td align="left">
        <ul>
          <li>Performance-based data minimization</li>
          <li>Depth-based data minimization</li>
          <li>Data collection stopping criterion</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Conference</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/abs/10.1145/3531146.3533148">
          FAccT2022
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Reviving Purpose Limitation and Data Minimisation in DataDriven Systems.</td>
      <td align="left">
        <ul>
          <li>Performance-based data minimization</li>
          <li>Data-driven systems</li>
          <li>Data collection stopping criterion</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Journal</td>
      <td align="center">
        <a href="https://techreg.org/article/download/10986/version/10973/11960/20667">
          TechReg2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Data Minimization for GDPR Compliance in Machine Learning Models.</td>
      <td align="left">
        <ul>
          <li>Breadth-based data minimization</li>
          <li>Runtime data minimization</li>
          <li>Personalized data minimization</li>
          <li>Knowledge distillation</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Journal</td>
      <td align="center">
        <a href="https://link.springer.com/article/10.1007/s43681-021-00095-8">
          AIEthics2022
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Auditing Black-Box Prediction Models for Data Minimization Compliance.</td>
      <td align="left">
        <ul>
          <li>Breadth-based data minimization</li>
          <li>Feature replacement</li>
          <li>Operational definition of the data minimization</li>
        </ul>
      </td>
      <td align="center">Data audit</td>
      <td align="center">Conference</td>
      <td align="center">
        <a href="https://proceedings.neurips.cc/paper/2021/file/ac6b3cce8c74b2e23688c3e45532e2a7-Paper.pdf">
          NIPS2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Auditing Algorithms: On Lessons Learned and the Risks of Data Minimization.</td>
      <td align="left">
        <ul>
          <li>xx</li>
        </ul>
      </td>
      <td align="center">Data audit</td>
      <td align="center">Conference</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/abs/10.1145/3375627.3375852">
          AIES2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">A Data Minimization Model for Embedding Privacy into Software Systems.</td>
      <td align="left">
        <ul>
          <li>Understand and minimize the use of data in the decision of collection, storing and sharing</li>
          <li>Data sensitivity</li>
          <li>Software system design</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Journal</td>
      <td align="center">
        <a href="https://www.sciencedirect.com/science/article/pii/S0167404818309106">
          ComSec2019
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">A Lightweight Scheme Exploiting Social Networks for Data Minimization According to the GDPR.</td>
      <td align="left">
        <ul>
          <li>xx</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Journal</td>
      <td align="center">
        <a href="https://ieeexplore.ieee.org/abstract/document/9330798">
          TCSS2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Detecting Conflicts Between Data-Minimization and Security Requirements in Business Process Models.</td>
      <td align="left">
        <ul>
          <li>xx</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Conference</td>
      <td align="center">
        <a href="https://link.springer.com/chapter/10.1007/978-3-319-92997-2_12">
          ECMFA2018
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">A semi-automated BPMN-based framework for detecting conflicts between security, data-minimization, and fairness requirements.</td>
      <td align="left">
        <ul>
          <li>Reusable domain-specific detection (conflict between needs and specifications)</li>
          <li>Fairness-related conflict</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Journal</td>
      <td align="center">
        <a href="https://link.springer.com/article/10.1007/s10270-020-00781-x">
          SSM2020
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">A Siamese Adversarial Anonymizer for Data Minimization in Biometric Applications.</td>
      <td align="left">
        <ul>
          <li>xxx</li>
          <li>xxx</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Conference</td>
      <td align="center">
        <a href="https://ieeexplore.ieee.org/abstract/document/9229760">
          EuroS&P
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Query-Driven Data Minimization with the DataEconomist.</td>
      <td align="left">
        <ul>
          <li>xxx</li>
          <li>xxx</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Conference</td>
      <td align="center">
        <a href="https://openproceedings.org/2019/conf/edbt/EDBT19_paper_365.pdf">
          EDBT2019
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Towards Query-Driven Data Minimization.</td>
      <td align="left">
        <ul>
          <li>xxx</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Conference</td>
      <td align="center">
        <a href="https://ceur-ws.org/Vol-2191/paper39.pdf">
          LWDA2018
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Embedding Personal Data Minimization Technologies in Organizations: Needs, Vision and Artifacts.</td>
      <td align="left">
        <ul>
          <li>xxx</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Conference</td>
      <td align="center">
        <a href="https://dl.acm.org/doi/abs/10.1145/3494193.3494203">
          ICEGOV2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Configurable Per-Query Data Minimization for Privacy-Compliant Web APIs.</td>
      <td align="left">
        <ul>
          <li>xxx</li>
        </ul>
      </td>
      <td align="center"></td>
      <td align="center">Conference</td>
      <td align="center">
        <a href="https://arxiv.org/abs/2203.09903">
          ICWE2022
        </a>
      </td>
    </tr>
  </tbody>
</table>