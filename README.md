# Selected Machine Learning and Security Projects

This repository is a portfolio of selected academic projects in machine learning, anomaly detection, cybersecurity analytics, wireless systems, and intelligent transportation. It currently contains the project reports and documents the motivation, methodology, evaluation approach, and key findings for each study.

The projects focus not only on model performance, but also on practical questions such as class imbalance, false alarms, missed detections, robustness, alert latency, and the limitations of offline evaluation.

## Projects

### Real-Time Anomaly Detection in Road-Traffic Sensor Data

Anomaly Detection in Road Traffic Sensor Data_NAB.pdf

This project evaluates two streaming anomaly-detection methods—Hierarchical Temporal Memory (HTM) and Random Cut Forest (RCF)—using the Numenta Anomaly Benchmark traffic dataset.

The analysis emphasizes early detection and operational alert quality rather than accuracy alone. Models are compared using latency-aware NAB scoring, precision, recall, F1, ROC-AUC, PR-AUC, time-to-detect, and false-alarm behavior. On a representative traffic series, HTM detected all four anomaly windows and achieved an F1 score of 0.727, while RCF generated fewer false alarms but missed one event.

**Topics:** streaming anomaly detection, time-series analysis, imbalanced data, threshold selection, alert latency, operational evaluation

### Deep Learning-Based Detection of Abnormal Wireless Activity
Deep Learning-Based Detection of Abnormal Signals in Spectrogram Data Using ResNet18.pdf

This project treats wireless-spectrum monitoring as an image-classification problem. A pretrained ResNet18 model was fine-tuned on 85,500 LTE/5G spectrogram samples to distinguish normal signals from tone, chirp, and pulse anomalies.

The model achieved 96.48% validation accuracy. Robustness was evaluated across signal-to-noise ratios from -10 dB to 10 dB, with test accuracy ranging from 87.6% under severe noise to 98.0% under high-SNR conditions. The analysis also examines class-level precision, recall, F1, confusion patterns, and performance degradation as noise increases.

**Topics:** deep learning, transfer learning, ResNet18, spectrogram classification, wireless security, robustness testing

### LTE C-V2X Vehicular Communication Simulation and Performance Evaluation

This project studies LTE Mode 4 vehicle-to-everything communication in simulated downtown and suburban Montréal environments. Scenarios were developed using Veins, OMNeT++, and SUMO, and Python was used to process simulation outputs and calculate Packet Reception Ratio (PRR).

The experiments compare Nakagami and Jakes fading models and evaluate the effects of vehicle density and environmental conditions. Increasing the number of vehicles from 10 to 20 reduced average PRR by approximately 14% to 17%, demonstrating the effect of congestion, interference, and mobility on communication reliability.

**Topics:** C-V2X, LTE Mode 4, OMNeT++, Veins, SUMO, wireless simulation, Python data analysis

### Semantic and Context-Aware Security Analysis

This project evaluates machine-learning approaches for multiclass network-attack classification using the UNSW-NB15 dataset. XGBoost models were compared under severe class imbalance, including an experiment using class weighting to improve recognition of minority attack categories.

The evaluation goes beyond overall accuracy by examining per-class precision, recall, F1, false negatives, and false alarms. The report discusses why apparently strong aggregate performance can conceal unsafe behavior for rare attacks and considers the implications of model errors for Security Operations Centre workflows and alert fatigue.

**Topics:** intrusion detection, XGBoost, multiclass classification, class imbalance, error analysis, trustworthy AI, SOC analytics

## Methods and Tools

- Python, Pandas, NumPy, scikit-learn, XGBoost, and PyTorch
- Jupyter notebooks and reproducible analytical workflows
- Classification, anomaly detection, transfer learning, and robustness evaluation
- Precision, recall, F1, ROC-AUC, PR-AUC, confusion matrices, and latency-aware scoring
- OMNeT++, Veins, and SUMO for vehicular-network simulation
- Technical reporting, visualization, and critical analysis of model limitations





## Author

**Maha Mubarak**  
Master of Engineering candidate in Computer Engineering, Polytechnique Montréal

- [GitHub](https://github.com/Maha-Mubarak)
- [LinkedIn](https://www.linkedin.com/in/maha-mubarak-mcgill2023)

