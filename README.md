# Protecting Privacy in Software Logs: What Should be Anonymized?

This repository hosts the replication package for the paper "Protecting Privacy in Software Logs: What Should be Anonymized?", accepted at The ACM International Conference on the Foundations of Software Engineering (FSE) 2025.

To support future replication or extension of our research, we have made our replication package available. For any questions or clarifications, feel free to open an issue or contact us.

## Contents

The replication package includes the following files:

- [`Replication Package/Article attributes.csv`](Replication%20Package/Article%20attributes.csv) – List of sensitive attributes studied or used in each of the 58 reviewed research articles.
- [`Replication Package/List of articles.csv`](Replication%20Package/List%20of%20articles.csv) – Metadata for the 58 reviewed research articles, including their input data, anonymization approaches, and evaluation metrics.
- [`Replication Package/List of log datasets.csv`](Replication%20Package/List%20of%20log%20datasets.csv) – A list of all 25 studied log datasets.
- [`Replication Package/Log attributes.csv`](Replication%20Package/Log%20attributes.csv) – Log attributes identified in each of the 25 studied log datasets.
- [`Replication Package/Survey responses.csv`](Replication%20Package/Survey%20responses.csv) – Raw survey responses from 61 industry participants on log privacy and anonymization practices.
- [`Replication Package/Survey.pdf`](Replication%20Package/Survey.pdf) – The survey questionnaire used in the study.

## Abstract
Software logs, generated during the runtime of software systems, are essential for various development and analysis activities, such as anomaly detection and failure diagnosis. However, the presence of sensitive information in these logs poses significant privacy concerns, particularly regarding *Personally Identifiable Information (PII)* and quasi-identifiers that could lead to re-identification risks. While general data privacy has been extensively studied, the specific domain of privacy in software logs remains underexplored, with inconsistent definitions of sensitivity and a lack of standardized guidelines for anonymization. To mitigate this gap, this study offers a comprehensive analysis of privacy in software logs from multiple perspectives. We start by performing an analysis of 25 publicly available log datasets to identify potentially sensitive attributes. Based on the result of this step, we focus on three perspectives: privacy regulations, research literature, and industry practices. We first analyze key data privacy regulations, such as the *General Data Protection Regulation (GDPR)* and the *California Consumer Privacy Act (CCPA)*, to understand the legal requirements concerning sensitive information in logs. Second, we conduct a systematic literature review to identify common privacy attributes and practices in log anonymization, revealing gaps in existing approaches. Finally, we survey 45 industry professionals to capture practical insights on log anonymization practices. Our findings shed light on various perspectives of log privacy and reveal industry challenges, such as technical and efficiency issues while highlighting the need for standardized guidelines. By combining insights from regulatory, academic, and industry perspectives, our study aims to provide a clearer framework for identifying and protecting sensitive information in software logs.
