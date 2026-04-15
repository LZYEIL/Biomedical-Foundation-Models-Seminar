## Biomedical-Foundation-Models-Seminar
- This repo includes some interesting papers on biomedical foundation models and lectures on this topic.
- Note: The contents are from the STAT992 Seminar: Foundation Models for Biomedical Data (Spring 2026) at the University of Wisconsin-Madison.
- Course Website: [STAT992](https://adaptinfer.org/fm-spring-2026/)

<br>

### Topic 1: Multimodal Vision-Language & Pathology

**Focus:** Integrating images (radiology/pathology) with text or learning visual representations for diagnosis.

- **BiomedGPT**  
  *Summary:* VLM that achieves SOTA performance in biomedical tasks like radiology VQA and report generation.

- **BiomedCLIP**  
  *Summary:* Pretrained on 15M scientific image-text pairs, BiomedCLIP sets new benchmarks in biomedical image retrieval, classification, and VQA through domain-specific adaptations.

- **CTransPath**  
  *Summary:* CNN-Transformer backbone pretrained via semantically-relevant contrastive learning on unlabeled histopathology images for downstream pathology tasks.

- **Virchow**  
  *Summary:* Computational pathology foundation model, high-accuracy pan-cancer detection and outperforms tissue-specific models, particularly in identifying rare cancer variants.




### Topic 2: Sequential & Temporal Modeling 

**Focus:** Modeling longitudinal patient data, irregular time series, and medical events from EHRs.

- **CoMET**  
  *Summary:* Power-law scaling in medical event data, showing that large-scale generative pretraining on longitudinal EHRs improves clinical prediction without task-specific fine-tuning.

- **CLMBR**  
  *Summary:* Transformer-based EHR foundation models pretrained on large-scale patient data significantly improve robustness and reduce performance decay against temporal distribution shifts.

- **MOMENT**  
  *Summary:* Introduce open-source foundation models pretrained on the diverse "Time series Pile," demonstrating effective general-purpose time-series analysis with minimal supervision across various domains.

- **MIRA**  
  *Summary:* Unified foundation model for medical time series that handles irregular intervals and missing values via continuous-time encoding, achieving superior forecasting accuracy in clinical settings.




### Topic 3: Molecular Biology & Relational Data 

**Focus:** Protein sequences, structured tabular data, and relational databases.

- **ESM**  
  *Summary:* Scaling unsupervised learning to 250M protein sequences yields representations that inherently encode biological structures and functions, enabling SOTA predictions for protein properties.

- **ProteinDT**  
  *Summary:* Multimodal framework that leverages textual descriptions to guide protein design and editing, demonstrating high accuracy in generating proteins aligned with functional text prompts.

- **PLUREL**  
  *Summary:* Synthesize multi-tabular relational databases to enable the first observation of power-law scaling in Relational Foundation Models, improving generalization to real-world structured data.

- **PanMETAI**  
  *Summary:* Use TabPFN integrated with NMR metabolomics data to achieve robust early-stage pancreatic cancer diagnosis across diverse populations.




### Topic 4: Clinical Applications, Interpretability & Trials 

**Focus:** High-level clinical workflows (trials), model interpretability, and specific application frameworks.

- **TrialGPT**  
  *Summary:* End-to-end LLM framework that automates patient-to-trial matching through retrieval, eligibility prediction, and ranking, significantly reducing screening time and improving accuracy.

- **Panacea**  
  *Summary:* Specialized foundation model pretrained on large-scale trial documents that outperforms generic LLMs in multiple clinical trial tasks, including search, summarization, design, and recruitment.

- **Circuit Tracing**  
  *Summary:* Introduce cross-layer transcoders to construct interpretable attribution graphs that trace the computational circuits and feature interactions within language models.
