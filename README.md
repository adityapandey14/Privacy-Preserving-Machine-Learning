# Privacy-Preserving-Machine-Learning

## Problem Description

· **System:** Electronic Health Record (EHR) systems store patients' medical data, including diagnoses, treatments, and personal information. Machine learning algorithms can analyze EHR data to improve patient care, but privacy concerns are a major obstacle.

· **Assets:** The privacy of patients' personal and medical information, which can be valuable for unauthorized uses (e.g., identity theft or blackmail).

· **Attackers:** Potential attackers include cybercriminals, hackers, or other unauthorized third parties.

· **Vulnerabilities:** Data breaches, insecure communication channels, or insufficient access controls.

· **Threats:** Unauthorized access, data leakage, or misuse of sensitive information.

· **Risks:** The risks are significant given the sensitive nature of medical data, the potential harm to patients, and possible legal repercussions for healthcare providers.


## Proposed Solution
**Category**

· Our solution falls into secure multi-party computation (SMPC), differential privacy, and/or fully homomorphic encryption (FHE).

· We propose a privacy-preserving machine learning framework for EHR systems, which allows healthcare providers to collaboratively train and evaluate machine learning models without sharing raw patient data.

**Expected Benefits**

· Enhanced data privacy and security for patients

· Compliance with privacy regulations (e.g., HIPAA, GDPR)

· Improved collaboration between healthcare providers

· Greater adoption of machine learning in healthcare

**Known Drawbacks**

· Potential increase in computational complexity

· Potential decrease in model accuracy due to privacy constraints

· Potential increase in costs due to complexity

**Reference Datasets**

· Synthea: An open-source, synthetic patient generator that models the medical history of synthetic patients, providing a realistic EHR dataset for research purposes. Link: https://synthea.mitre.org/

## **Sprint Planning**

**Product Backlog**

· Comprehensive literature review on privacy-preserving machine learning techniques

· Design and implementation of the privacy-preserving machine learning framework

· Evaluation of the proposed framework's performance and privacy guarantees

· Final report detailing the problem, proposed solution, and results

· Presentation highlighting the project's key findings and contributions

**Sprint Backlog**

**Sprint 1 – Planning (Complete Week 7)**

1. Conduct a literature review on existing privacy-preserving machine learning techniques, focusing on healthcare applications

2. Identify key requirements for a privacy-preserving machine learning framework in the context of EHR systems

3. Begin designing the proposed framework, outlining its main components and their interactions

4. Obtain access to the MIMIC-III dataset or download the Synthea dataset for experimentation

5. Identify vulnerable areas of attack in in EHR systems

6. Understand EHR architectures

## Installation

```python
!pip install pydot pydotplus
!apt-get install -y graphviz libgraphviz-dev
!pip install pygraphviz
