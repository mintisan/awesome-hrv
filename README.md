# Awesome HRV(Heart Rate Variability)


![Awesome](https://awesome.re/badge.svg) ![GitHub stars](https://img.shields.io/github/stars/mintisan/awesome-hrv.svg?style=social)

A curated list of awesome libraries, datasets, tutorials, papers, and other resources related to Heart Rate Variability (HRV) analysis. This repository aims to be a comprehensive and organized collection that will help researchers and developers in the world of HRV!

## Table of Contents

- [Standard](#standard)
- [Library](#library)
- [Papers](#papers)
- [Datasets](#datasets)
- [Tutorial](#tutorial)
- [Datasets](#datasets)
- [Contributing](#contributing)

## Standard

- [HRV: Standards of Measurement, Physiological Interpretation and Clinical Use](https://www.ahajournals.org/doi/10.1161/01.CIR.93.5.1043)
- [Kubios HRV Standard](https://www.kubios.com/hrv-standard/) : [Kubios HRV Software](https://www.kubios.com/downloads/Kubios_HRV_Users_Guide.pdf) | [Kubios HRV Scientific](https://www.kubios.com/downloads/HRV-Scientific-Users-Guide.pdf)

## Library

- [neuropsychology/NeuroKit2](https://github.com/neuropsychology/NeuroKit) : NeuroKit2: The Python Toolbox for Neurophysiological Signal Processing
- [MIT-LCP/wfdb-python](https://github.com/MIT-LCP/wfdb-python) : Native Python WFDB package
- [cbrnr/sleepecg](https://github.com/cbrnr/sleepecg) : Sleep stage detection using ECG
- [berndporr/py-ecg-detectors](https://github.com/berndporr/py-ecg-detectors) : Popular ECG R peak detectors written in python
- [scientisst/BioSPPy](https://github.com/scientisst/BioSPPy) : Biosignal Processing in Python[Deprecated]
- [paulvangentcom/heartrate_analysis_python](https://github.com/paulvangentcom/heartrate_analysis_python) : HeartPy - Python Heart Rate Analysis Toolkit



### Comparison

- [ECG R peak detection in Python: a comparison of libraries](https://www.samproell.io/posts/signal/ecg-library-comparison/)

## Papers

- 2002-[An advanced detrending method with application to HRV analysis](https://pubmed.ncbi.nlm.nih.gov/12066885/)-1196
- 2018-[An Open Source Benchmarked Toolbox for Cardiovascular Waveform and Interval Analysis](https://pubmed.ncbi.nlm.nih.gov/30199376/)-185 | [code](https://github.com/cliffordlab/PhysioNet-Cardiovascular-Signal-Toolbox)-m
- 2020-[RR-APET - Heart rate variability analysis software](https://pubmed.ncbi.nlm.nih.gov/31648100/)-15 | [code](https://gitlab.com/MegMcC/rr-apet-hrv-analysis-software)-py
- 2020-[Heart rate n-variability (HRnV) and its application to risk stratification of chest pain patients in the emergency department](https://bmccardiovascdisord.biomedcentral.com/articles/10.1186/s12872-020-01455-8)-19 | [code](https://github.com/nliulab/HRnV)-m
- 2021-[Heart Rate Variability in Psychology: A Review of HRV Indices and an Analysis Tutorial](https://www.mdpi.com/1424-8220/21/12/3998)-87
- 2021-[HRnV-Calc: A software package for heart rate n-variability and heart rate variability analysis](https://arxiv.org/abs/2111.09649) | [code](https://github.com/nliulab/HRnV-Calc)-m
- 2021-[Unveiling the Structure of Heart Rate Variability (HRV) Indices: A Data-driven Meta-clustering Approach](https://psyarxiv.com/mwa6x/)
- 2022-[Comprehensive HRV estimation pipeline in Python using Neurokit2: Application to sleep physiology](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9307944/)-1


### R-peak

- 1986-[Quantitative Investigation of QRS Detection Rules Using the MIT/BIH Arrhythmia Database](https://ieeexplore.ieee.org/document/4122227)-1555
- 1987-[A Real-Time QRS Detection Algorithm](https://ieeexplore.ieee.org/document/4122029)-8721 | [code](https://github.com/antimattercorrade/Pan_Tompkins_QRS_Detection) | [PanTompkinsQRS](https://github.com/rafaelmmoreira/PanTompkinsQRS)
- 2011-[An Efficient R-peak Detection Based on New Nonlinear Transformation and First-Order Gaussian Differentiator](https://link.springer.com/article/10.1007/s13239-011-0065-3)-88 | [code](https://github.com/tru-hy/rpeakdetect)
- 2013- [A Comparison of Three QRS Detection Algorithms Over a Public Database](https://www.sciencedirect.com/science/article/pii/S2212017313002831)-89
- 2014-[A real-time QRS detector based on higher-order statistics for ECG gated cardiac MRI](https://www.cinc.org/archives/2014/pdf/0733.pdf)-22
- 2014-[3DQRS: A method to obtain reliable QRS complex detection within high field MRI using 12-lead ECG traces](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3961533/)-25
- 2017-[A convolutional neural network based approach to QRS detection](https://ieeexplore.ieee.org/document/8073581)-57
- 2020-[A Crucial Wave Detection and Delineation Method for Twelve-Lead ECG Signals](https://ieeexplore.ieee.org/document/8954716)-20
- 2020-[A Real Time QRS Detection Algorithm Based on ET and PD Controlled Threshold Strategy](https://www.mdpi.com/1424-8220/20/14/4003)
- 2020-[Analysis of Pan-Tompkins Algorithm Performance with Noisy ECG Signals](https://iopscience.iop.org/article/10.1088/1742-6596/1532/1/012022)-53
- 2021-[Robust R-Peak Detection in Low-Quality Holter ECGs Using 1D Convolutional Neural Network](https://ieeexplore.ieee.org/abstract/document/9451595)-43 | [code](https://github.com/MUzairZahid/R-Peak-Detection-1D-CNN)
- 2021-[Robust Peak Detection for Holter ECGs by Self-Organized Operational Neural Networks](https://arxiv.org/pdf/2110.02381.pdf)-11 | [code](https://github.com/MUzairZahid/R-Peak-Detection-1D-SelfONN)
- 2022-[QRS complexes and T waves localization in multi-lead ECG signals based on deep learning and electrophysiology knowledge](https://www.sciencedirect.com/science/article/abs/pii/S0957417422005747)-9
- 2022-[Pan-Tompkins++: A Robust Approach to Detect R-peaks in ECG Signals](https://arxiv.org/abs/2211.03171)-1 | [code](https://github.com/Niaz-Imtiaz/Pan-Tompkins-Plus-Plus)
- 2022-[Tiny-HR: Towards an interpretable machine learning pipeline for heart rate estimation on edge devices](https://arxiv.org/pdf/2208.07981.pdf)-2 | [code](https://github.com/tataganesh/HRV-edgedevice)
- 2023-[A Deep Learning Architecture Using 3D Vectorcardiogram to Detect R-Peaks in ECG with Enhanced Precision](https://www.mdpi.com/1424-8220/23/4/2288) | 

### Compression

- 2018-[An efficient compression of ECG signals using deep convolutional autoencoders](https://www.sciencedirect.com/science/article/abs/pii/S1389041718302730)-182
- 2020-[An Efficient Lossless Compression Method for Periodic Signals Based on Adaptive Dictionary Predictive Coding](https://www.mdpi.com/2076-3417/10/14/4918)-3

### Denoise

- 1985-Removal of base-line wander and power-line interference from the ecg by an efficient fir filter with a reduced number of taps-487
- 2015-Removal of noise from electrocardiogram using digital fir and iir filters with various methods
- 2018-Baseline wander removal methods for ECG signals- A comparative study-19
- 2018-Deep recurrent neural networks for ecg signal denoising-94
- 2019-Deep Learning Models for Denoising ECG Signals-66
- 2019-[Noise Reduction in ECG Signals Using Fully Convolutional Denoising Autoencoders](https://www.researchgate.net/publication/333228342_Noise_Reduction_in_ECG_Signals_Using_Fully_Convolutional_Denoising_Autoencoders)-192 | [code](https://github.com/sophie091524/Noise-Reduction-in-ECG-Signals)
- 2021-[DeepFilter- An ECG baseline wander removal filter using deep learning techniques](https://www.sciencedirect.com/science/article/abs/pii/S1746809421005899)-13 | [code](https://github.com/fperdigon/DeepFilter)
- 2023-[DeScoD-ECG- Deep Score-Based Diffusion Model for ECG Baseline Wander and Noise Removal](https://arxiv.org/abs/2208.00542)-2 | [code](https://github.com/huayuliarizona/score-based-ecg-denoising)

### Outiler

- 2013-[Detecting outliers: Do not use standard deviation around the mean, use absolute deviation around the median](https://www.sciencedirect.com/science/article/abs/pii/S0022103113000668)-3637 | [code](https://www.sciencedirect.com/science/article/abs/pii/S0022103113000668)
- 2019-[A robust algorithm for heart rate variability time series artefact correction using novel beat classification](https://pubmed.ncbi.nlm.nih.gov/31314618/)-164 | [code-systole](https://github.com/embodied-computation-group/systole) | [code-hrv-correction](https://github.com/sokolmarek/hrv-correction)
- 2019-[Outlier Detection: How to Threshold Outlier Scores?](http://www.cs.joensuu.fi/sipu/pub/a37-yang.pdf)

#### outlier detection library
- [Anomaly Detection Learning Resources](https://github.com/yzhao062/anomaly-detection-resources) : Anomaly detection related books, papers, videos, and toolboxes
- [awesome-TS-anomaly-detection](https://github.com/rob-med/awesome-TS-anomaly-detection) : List of tools & datasets for anomaly detection on time-series data.
- [PyOD](https://github.com/yzhao062/pyod) : A Comprehensive and Scalable Python Library for Outlier Detection (Anomaly Detection)
  - [Handbook of Anomaly Detection: With Python Outlier Detection](https://medium.com/dataman-in-ai/handbook-of-anomaly-detection-with-python-outlier-detection-1-introduction-c8f30f71961c)  
- [TODS](https://github.com/datamllab/tods) : An Automated Time-series Outlier Detection System

#### outlier tutorial

- [Top 5 Outlier Detection Methods Every Data Enthusiast Must Know](https://dataheroes.ai/blog/outlier-detection-methods-every-data-enthusiast-must-know/#Choosing_the_Right_Outlier_Detection_Method_for_Your_Data_Analysis_Project)

### Classification 
- 2015-[Real-Time Patient-Specific ECG Classification by 1D Convolutional Neural Networks](https://ieeexplore.ieee.org/document/7202837)-1605
- 2020-[Automatic diagnosis of the 12-lead ECG using a deep neural network](https://www.nature.com/articles/s41467-020-15432-4)-482 | [code](https://github.com/antonior92/automatic-ecg-diagnosis)
- 2021-[Real-Time Patient-Specific ECG Classification by 1D Self-Operational Neural Networks](https://arxiv.org/pdf/2110.02215.pdf)-34 | [code](https://github.com/omerferhatt/ecg-dnn)
- 2021-[Automatic ECG Classification Using Continuous Wavelet Transform and Convolutional Neural Network](https://www.mdpi.com/1099-4300/23/1/119)-136 | [code](https://github.com/JackAndCole/ECG-Classification-Using-CNN-and-CWT)
- 2021-[An Attention-based Deep Learning Approach for Sleep Stage Classification with Single-Channel EEG](https://ieeexplore.ieee.org/document/9417097)-212 | [code](https://github.com/emadeldeen24/AttnSleep)
- 2022-[A novel deep learning package for electrocardiography research](https://iopscience.iop.org/article/10.1088/1361-6579/ac9451/meta)-1 | [code](https://github.com/DeepPSP/torch_ecg)
- 2022-[ECG-based Real-time Arrhythmia Monitoring Using Quantized Deep Neural Networks: A Feasibility Study](https://intsav.github.io/realtime_ecg.html)-24 | [code](https://github.com/intsav/RealtimeArrhythmiaMonitoring)
- 2023-[A Tiny Matched Filter-Based CNN for Inter-Patient ECG Classification and Arrhythmia Detection at the Edge](https://www.mdpi.com/1424-8220/23/3/1365)-5

### Quality Assessment
- 2022-[Robustness of electrocardiogram signal quality indices](https://royalsocietypublishing.org/doi/10.1098/rsif.2022.0012)-16


## Indices

- https://github.com/nliulab/HRnV-Calc#metrics-descriptions
- https://github.com/cliffordlab/PhysioNet-Cardiovascular-Signal-Toolbox#iii-guide-to-output
- https://www.mdpi.com/1424-8220/21/12/3998 Table 1. A summary of HRV indices according to their respective analysis domains.
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9307944/table/tbl0001/?report=objectonly

| Metrics                           | Units | Description                                                                             |
|-----------------------------------|-------|-----------------------------------------------------------------------------------------|
| **Tiem Domain**                       |       |                                                                                         |
| Average RR                        | ms    | The mean of RR intervals                                                                |
| SDRR                              | ms    | The standard deviation of RR intervals                                                  |
| Average HR                        | 1/min | The mean of heart rate                                                                  |
| SDHR                              | 1/min | The standard deviation of heart rate                                                    |
| RMSSD                             | ms    | Square root of the mean squared differences between successive RR intervals             |
| NN50                              | count | Numbers of RR intervals differ more than 50 ms from the previous intervals              |
| pNN50                             | %     | Percentage of NN50 intervals within the entire RR intervals                             |
| RR Skewness                       | -     | The skewness of the RR intervals distribution                                           |
| RR Kurtosis                       | -     | The kurtosis of the RR intervals distribution                                           |
| RR Triangular Index               | -     | The integral of the RR intervals histogram divided by the height of the histogram       |
| **Frequency Domain**                  |       |      For more detailed documentations of the frequency domain metrics, check out [here](https://github.com/cliffordlab/PhysioNet-Cardiovascular-Signal-Toolbox#frequency-domain-measures-of-hrv-default-using-lomb-periodogram-method).                                                                                   |
| VLF, LF, and HF Peak frequencies  | Hz    | The peak frequencies in the power spectral distribution (PSD) for VLF, LF, and HF bands |
| VLF, LF, and HF Powers            |       | Absolute powers of VLF, LF, and HF bands                                                |
| VLF, LF, and HF Power Percentages | %     | The percentage for powers of VLF, LF, and HF bands within the overall spectrum          |
| LF and HF Normalized Powers       | n.u.  | Normalized powers for LF and HF bands                                                   |
| Total Power                       |       | The overall power of the PSD                                                            |
| LF/HF                             | -     | The ratio between the powers of LF and HF bands                                         |
| **Nonlinear Domain**                   |       |                                                                                         |
| Poincare SD1 and SD2              | ms    | The width and length of the eclipse fitted in the Poincare plot                         |
| App_Ent                           | -     | Approximate entropy                                                                     |
| Sam_Ent                           | -     | Sample entropy                                                                          |
| DFA &alpha;<sub>1</sub> and &alpha;<sub>2</sub>                              | -     | Short-term and long-term fluctuations of detrended fluctuation analysis (DFA)           | 



## Tutorial

- [Heart Rate Variability Analysis with the HRV Toolkit](https://archive.physionet.org/tutorials/hrv-toolkit/)
- [Everything You Should Know About Heart Rate Variability (HRV)](https://www.youtube.com/watch?v=ozcZSnjbPoE)


## Datasets

- [MIT-BIH Arrhythmia Database](https://www.physionet.org/content/mitdb/1.0.0/)
- [St Petersburg INCART 12-lead Arrhythmia Database](https://physionet.org/content/incartdb/1.0.0/)
- [MIT-BIH Polysomnographic Database](https://physionet.org/content/slpdb/1.0.0/)
- [ECG GUDB](https://github.com/berndporr/ECG-GUDB) : High precision ECG Database with annotated R peaks, recorded and filmed under realistic conditions
- [Chinese Cardiovascular Disease Database—CCDD Dataset](http://www.ecgdb.com/index.html)
- [The 8th International Conference on Biomedical Engineering and Biotechnology (ICBEB 2019)](http://2019.icbeb.org/Challenge.html)
- [CSPC2020](http://2020.icbeb.org/CSPC2020)
- [Lobachevsky University Electrocardiography Database (LUDB)](https://physionet.org/content/ludb/1.0.1/)
- [St. Petersburg Institute of Cardiological Technics 12-lead Arrhythmia Database (IN- CART)](https://physionet.org/content/incartdb/1.0.0/)

## Contributing

We welcome your contributions! Please follow these steps to contribute:

1. Fork the repo.
2. Create a new branch (e.g., `feature/new-hrv-resource`).
3. Commit your changes to the new branch.
4. Create a Pull Request, and provide a brief description of the changes/additions.

Please make sure that the resources you add are relevant to the field of Heart Rate Variability. Before contributing, take a look at the existing resources to avoid duplicates.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
