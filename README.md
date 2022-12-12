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

*Search for some FL-related papers.*

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
      <th>Title</th>
      <th align="center">Stage</th>
      <th align="center">Min. entity</th>
      <th align="center">Min. tech./meas.</th>
      <th align="center">Note</th>
      <th align="center">Link</th>
    </tr>
    <tr>
      <td align="left">From Data Minimization to Data Minimummization.</td>
      <td align="center">Data collection</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">The context of the data in the form of metadata is collected along with the data. | Database</td>
      <td align="center">
        <a href="https://link.springer.com/chapter/10.1007/978-3-642-30487-3_15">
           DPIS2013
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Privacy Architectures: Reasoning About Data Minimisation and Integrity.</td>
      <td align="center">Data collection</td>
      <td align="center">Property</td>
      <td align="center">Integrity</td>
      <td align="left">Privacy architecture | Focus on a key aspect of privacy, data minimisation, and its tension with integrity requirements.</td>
      <td align="center">
        <a href="https://link.springer.com/chapter/10.1007/978-3-319-11851-2_2">
          STM2014
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Towards Query-Driven Data Minimization.</td>
      <td align="center">Data collection</td>
      <td align="center">Query meta-information</td>
      <td align="center">User-specific access</td>
      <td align="left">Database</td>
      <td align="center">
        <a href="https://ceur-ws.org/Vol-2191/paper39.pdf">
          LWDA2018
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Student Success Prediction and the Trade-Off between Big Data and Data Minimization.</td>
      <td align="center">Data collection</td>
      <td align="center">Daily activity data</td>
      <td align="center">Anonymization</td>
      <td align="left">Education</td>
      <td align="center">
        <a href="https://dspace.gi.de/bitstream/handle/20.500.12116/21041/proceedings_22.pdf?sequence=1&isAllowed=y">
          DeLFI2018
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Query-Driven Data Minimization with the DataEconomist.</td>
      <td align="center">Data collection</td>
      <td align="center">Data amount, Data access</td>
      <td align="center">User-specific access</td>
      <td align="left">Database | Delete unnecessary data</td>
      <td align="center">
        <a href="https://openproceedings.org/2019/conf/edbt/EDBT19_paper_365.pdf">
          EDBT2019
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">A Data Minimization Model for Embedding Privacy into Software Systems.</td>
      <td align="center">Data collection</td>
      <td align="center">Data usage</td>
      <td align="center">Data sensitivity, visibility, relevance</td>
      <td align="left">
        Understand and minimize the use of data | Software system design
      </td>
      <td align="center">
        <a href="https://www.sciencedirect.com/science/article/pii/S0167404818309106">
          ComSec2019
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Operationalizing the Legal Principle of Data Minimization for Personalization.</td>
      <td align="center">Data collection</td>
      <td align="center">Per-user data</td>
      <td align="center">Average performance/Per-user performance</td>
      <td>
        Recommender systems | Personalization | Performance-based data minimization
      </td>
      <td align="center">
        <a href="https://dl.acm.org/doi/abs/10.1145/3397271.3401034">
          SIGIR2020
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Fair Inputs and Fair Outputs The Incompatibility of Fairness in Privacy and Accuracy.</td>
      <td align="center">Data collection</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left"></td>
      <td align="center">
        <a href="https://dl.acm.org/doi/abs/10.1145/3386392.3399568">
          UMAP2020
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Embedding Personal Data Minimization Technologies in Organizations: Needs, Vision and Artifacts.</td>
      <td align="center">Data collection</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://dl.acm.org/doi/abs/10.1145/3494193.3494203">
          ICEGOV2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">A Lightweight Scheme Exploiting Social Networks for Data Minimization According to the GDPR.</td>
      <td align="center">Data collection</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      <td align="center">
        <a href="https://ieeexplore.ieee.org/abstract/document/9330798">
          TCSS2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">How to address data privacy concerns when using social media data in conservation science.</td>
      <td align="center">Data collection</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://conbio.onlinelibrary.wiley.com/doi/epdf/10.1111/cobi.13708">
          ConBio2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Towards a Formal Approach for Data Minimization in Programs.</td>
      <td align="center">Data collection</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://link.springer.com/chapter/10.1007/978-3-030-93944-1_11">
           DPM/CBT2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Configurable Per-Query Data Minimization for Privacy-Compliant Web APIs.</td>
      <td align="center">Data collection</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://arxiv.org/abs/2203.09903">
          ICWE2022
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Learning to Limit Data Collection via Scaling Laws: A Computational Interpretation for the Legal Principle of Data Minimization.</td>
      <td align="center">Data collection</td>
      <td align="center"></td>
      <td align="center"></td>
      <td>
        Performance-based data minimization, Depth-based data minimization, Data collection stopping criterion</li>
      </td>
      <td align="center">
        <a href="https://dl.acm.org/doi/pdf/10.1145/3531146.3533148">
          FAccT2022
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Practical Data Access Minimization in Trigger-Action Platforms.</td>
      <td align="center">Data collection</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://www.usenix.org/conference/usenixsecurity22/presentation/chen-yunang-practical">
          USENIXSS2022
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">I Prefer not to Say: Operationalizing Fair and User-guided Data Minimization.</td>
      <td align="center">Data collection</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://arxiv.org/abs/2210.13954">
          CoRR2022
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Privacy for Free: How does Dataset Condensation Help Privacy.</td>
      <td align="center">Data collection</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://arxiv.org/pdf/2206.00240.pdf">
          ICML2022
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Detecting Conflicts Between Data-Minimization and Security Requirements in Business Process Models.</td>
      <td align="center">Data inference</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="center">
        <a href="https://link.springer.com/chapter/10.1007/978-3-319-92997-2_12">
          ECMFA2018
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">A semi-automated BPMN-based framework for detecting conflicts between security, data-minimization, and fairness requirements.</td>
      <td align="center">Data inference</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
        <ul>
          <li>Reusable domain-specific detection (conflict between needs and specifications)</li>
          <li>Fairness-related conflict</li>
        </ul>
      </td>
      <td align="center">
        <a href="https://link.springer.com/article/10.1007/s10270-020-00781-x">
          SSM2020
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">A Siamese Adversarial Anonymizer for Data Minimization in Biometric Applications.</td>
      <td align="center">Data inference</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://ieeexplore.ieee.org/abstract/document/9229760">
          EuroS&P2020
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Data Minimization for GDPR Compliance in Machine Learning Models.</td>
      <td align="center">Data inference</td>
      <td align="center"></td>
      <td align="center"></td>
      <td>
        Breadth-based data minimization, Runtime data minimization, Personalized data minimization, Knowledge distillation
      </td>
      <td align="center">
        <a href="https://link.springer.com/article/10.1007/s43681-021-00095-8">
          AIEthics2022
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Auditing Black-Box Prediction Models for Data Minimization Compliance.</td>
      <td align="center">Data audit</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
        Breadth-based data minimization, Feature replacement, Operational definition of the data minimization
      </td>
      <td align="center">
        <a href="https://proceedings.neurips.cc/paper/2021/file/ac6b3cce8c74b2e23688c3e45532e2a7-Paper.pdf">
          NIPS2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Auditing Algorithms: On Lessons Learned and the Risks of Data Minimization.</td>
      <td align="center">Data audit</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://dl.acm.org/doi/abs/10.1145/3375627.3375852">
          AIES2021
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Privacy 3.0 := Data Minimization + User Control + Contextual Integrity.</td>
      <td align="center">Other</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://www.degruyter.com/document/doi/10.1524/itit.2011.0622/html">
          InfTech2011
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Regime Change: Enabling Big Data through Europe's New Data Protection Regulation.</td>
      <td align="center">Other</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left"></td>
      <td align="center">
        <a href="https://heinonline.org/HOL/LandingPage?handle=hein.journals/cstlr17&div=11&id=&page=">
          SciTech2016
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">A Process for Data Protection Impact Assessment Under the European General Data Protection Regulation.</td>
      <td align="center">other</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://link.springer.com/chapter/10.1007/978-3-319-44760-5_2">
          APF2016
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">The European General Data Protection Regulation: challenges and considerations for iPSC researchers and biobanks.</td>
      <td align="center">Other</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://www.futuremedicine.com/doi/10.2217/rme-2017-0068">
          FutMed2017
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">The Legal Challenges of Big Data: Putting Secondary Rules First in the Field of EU Data Protection.</td>
      <td align="center">Other</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
      </td>
      <td align="center">
        <a href="https://heinonline.org/HOL/LandingPage?handle=hein.journals/edpl3&div=9&id=&page=">
          EDPL2017
        </a>
      </td>
    </tr>
    <tr>
      <td align="left">Reviving Purpose Limitation and Data Minimisation in DataDriven Systems.</td>
      <td align="center">Other</td>
      <td align="center"></td>
      <td align="center"></td>
      <td align="left">
        Performance-based data minimization, Data-driven systems, Data collection stopping criterion
      </td>
      <td align="center">
        <a href="https://techreg.org/article/download/10986/version/10973/11960/20667">
          TechReg2021
        </a>
      </td>
    </tr>
  </tbody>
</table>
