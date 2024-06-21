# Graph-Based Cardiac Event Detection

This repository contains related work and resources for the project on graph-based characterization of cardiac events for the early detection of heart failure.
## Introduction

Heart failure (HF) is a major global health concern, affecting millions of individuals worldwide. Early detection of acute decompensated heart failure (ADHF) is crucial for improving patient outcomes and reducing healthcare costs. This project aims to characterize and classify HF and HF-free episodes using graph signal processing (GSP) and machine learning techniques on ECG data.
![DALL·E-2024-06-21-01 07](https://github.com/wissal9999999999999/Graph-based-cardiac-event-detection/assets/98689079/158fbc42-0f5f-4120-a04f-387bdc166096)

## Repository Structure

- `papers/`: Collection of research papers from Google Scholar, PubMed, IEEE, and ScienceDirect between 2022 and 2024 related to graph-based signal processing, heart failure detection, and ECG analysis.
- `datasets/`: References and links to relevant datasets used in cardiac event detection studies.
- `code/`: Scripts and code snippets related to graph signal processing and machine learning on ECG data.
- `tutorials/`: Tutorials and learning resources on graph signal processing, machine learning, and biomedical signal processing.
- `references/`: Bibliography of books, articles, and other resources.
- `notes/`: Personal notes and observations on related work and the project.

## Key Papers

This section includes important research papers related to graph signal processing, graph neural networks, machine learning, and ECG analysis.

### Graph Signal Processing

- Shuman, D. I., Narang, S. K., Frossard, P., Ortega, A., & Vandergheynst, P. (2013). The emerging field of signal processing on graphs: Extending high-dimensional data analysis to networks and other irregular domains. IEEE Signal Processing Magazine, 30(3), 83-98. [Link](https://doi.org/10.1109/MSP.2012.2235192)
- Mateos, G., Segarra, S., Marques, A. G., & Ribeiro, A. (2018). Inference of graph topology. Chapter 13 – Cooperative and Graph Signal Processing, Editor(s): Petar M. Djurić, Cédric Richard, Academic Press, pp. 349-374. [Link](https://doi.org/10.1016/B978-0-12-813677-5.00013-4)

### Graph Neural Networks

- Hamilton, W., Ying, R., & Leskovec, J. (2017). Representation learning on graphs: Methods and applications. IEEE Data Eng. Bull., 40(3), 52-74. [Link](https://arxiv.org/abs/1709.05584)
- Kipf, T. N., & Welling, M. (2017). Semi-supervised classification with graph convolutional networks. In ICLR. [Link](https://arxiv.org/abs/1609.02907)
- Veličković, P., Cucurull, G., Casanova, A., Romero, A., Liò, P., & Bengio, Y. (2018). Graph attention networks. ICLR. [Link](https://arxiv.org/abs/1710.10903)

### Machine Learning and Deep Learning

- LeCun, Y., Bengio, Y., & Hinton, G. (2015). Deep learning. Nature, 521(7553), 436-444. [Link](https://doi.org/10.1038/nature14539)
- Goodfellow, I., Bengio, Y., & Courville, A. (2016). Deep Learning. MIT Press. [Link](https://www.deeplearningbook.org/)

### ECG Analysis

- Acharya, U. R., Fujita, H., Lih, O. S., Hagiwara, Y., Tan, J. H., & Adam, M. (2017). Automated detection of arrhythmias using different intervals of tachycardia ECG segments with convolutional neural network. Information Sciences, 405, 81-90. [Link](https://doi.org/10.1016/j.ins.2017.04.012)
- Kiranyaz, S., Ince, T., & Gabbouj, M. (2016). Real-time patient-specific ECG classification by 1-D convolutional neural networks. IEEE Transactions on Biomedical Engineering, 63(3), 664-675. [Link](https://doi.org/10.1109/TBME.2015.2468589)


### Datasets
| Name of Dataset | Source | Description | Link |
|-----------------|--------|-------------|------|
| MIT-BIH Arrhythmia Database | PhysioNet | A widely used dataset for the study of arrhythmias, containing 48 half-hour excerpts of two-channel ambulatory ECG recordings. | [MIT-BIH Arrhythmia Database](https://physionet.org/content/mitdb/1.0.0/) |
| PhysioNet/Computing in Cardiology Challenge 2017 | PhysioNet | Dataset focused on early prediction of sepsis from clinical data. | [PhysioNet Challenge 2017](https://physionet.org/content/challenge-2017/1.0.0/) |
| European ST-T Database | PhysioNet | Contains annotated ECG records from 79 subjects, useful for the analysis of ST-T changes. | [European ST-T Database](https://physionet.org/content/edb/1.0.0/) |
| PTB Diagnostic ECG Database | PhysioNet | Includes 549 ECG records from 290 subjects, providing detailed information for diagnostic ECG analysis. | [PTB Diagnostic ECG Database](https://physionet.org/content/ptbdb/1.0.0/) |
| Cardiovascular Disease Dataset | Kaggle | A Kaggle dataset containing data for predicting cardiovascular disease events. | [Cardiovascular Disease Dataset](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset) |
| CPSC 2018 Challenge | PhysioNet | Dataset from the China Physiological Signal Challenge 2018 focused on classifying arrhythmias. | [CPSC 2018 Challenge](https://physionet.org/content/challenge-2018/1.0.0/) |
| Ludb | PhysioNet | A collection of ECG recordings for various diagnostic categories, including myocardial infarction. | [Ludb](https://physionet.org/content/ludb/1.0.1/) |
| Chapman-Shaoxing | PhysioNet | A comprehensive dataset of ECG recordings from patients with a wide range of heart conditions. | [Chapman-Shaoxing](https://physionet.org/content/chapman-shaoxing/1.0.0/) |
| CardioSignals | Kaggle | Contains over 50,000 labeled ECG segments for the purpose of classifying heartbeats into different types. | [CardioSignals](https://www.kaggle.com/sergiofigaro/cardiosignals-ecg-classification) |
| CinC Challenge 2017 | PhysioNet | Data from the PhysioNet/Computing in Cardiology Challenge 2017, focused on the detection of AF from short single lead ECG recordings. | [CinC Challenge 2017](https://physionet.org/content/challenge-2017/1.0.0/) |
| Georgia 12-lead ECG Challenge | PhysioNet | A dataset providing 12-lead ECG recordings collected for classification challenges. | [Georgia 12-lead ECG Challenge](https://physionet.org/content/georgia-ecg/1.0.0/) |
| Long-Term ST Database | PhysioNet | Contains long-term ECG recordings annotated with ST segment changes. | [Long-Term ST Database](https://physionet.org/content/ltstdb/1.0.0/) |
| INCART Database | PhysioNet | 75 annotated ECG recordings from patients with a variety of diagnoses. | [INCART Database](https://physionet.org/content/incart/1.0.0/) |
| MIT-BIH Noise Stress Test Database | PhysioNet | A set of ECG recordings with added calibrated noise for testing noise resistance of QRS detectors. | [MIT-BIH Noise Stress Test Database](https://physionet.org/content/nstdb/1.0.0/) |
| PhysioNet/CinC Challenge 2020 | PhysioNet | A dataset for classifying cardiac abnormalities from 12-lead ECGs. | [PhysioNet/CinC Challenge 2020](https://physionet.org/content/challenge-2020/1.0.0/) |

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or additions.

