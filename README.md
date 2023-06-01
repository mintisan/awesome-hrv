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
- [Kubios HRV Standard](https://www.kubios.com/hrv-standard/) : [Kubios HRV Software](https://www.kubios.com/downloads/Kubios_HRV_Users_Guide.pdf)

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

- 2018-[An Open Source Benchmarked Toolbox for Cardiovascular Waveform and Interval Analysis](https://pubmed.ncbi.nlm.nih.gov/30199376/)-185 | [code](https://github.com/cliffordlab/PhysioNet-Cardiovascular-Signal-Toolbox)-m
- 2011-[An Efficient R-peak Detection Based on New Nonlinear Transformation and First-Order Gaussian Differentiator](https://link.springer.com/article/10.1007/s13239-011-0065-3)-88 | [code](https://github.com/tru-hy/rpeakdetect)
- 2020-[RR-APET - Heart rate variability analysis software](https://pubmed.ncbi.nlm.nih.gov/31648100/)-15 | [code](https://gitlab.com/MegMcC/rr-apet-hrv-analysis-software)-py
- 2020-[Heart rate n-variability (HRnV) and its application to risk stratification of chest pain patients in the emergency department](https://bmccardiovascdisord.biomedcentral.com/articles/10.1186/s12872-020-01455-8)-19 | [code](https://github.com/nliulab/HRnV)-m
- 2021-[Heart Rate Variability in Psychology: A Review of HRV Indices and an Analysis Tutorial](https://www.mdpi.com/1424-8220/21/12/3998)-87
- 2021-[HRnV-Calc: A software package for heart rate n-variability and heart rate variability analysis](https://arxiv.org/abs/2111.09649) | [code](https://github.com/nliulab/HRnV-Calc)-m
- 2021-[Unveiling the Structure of Heart Rate Variability (HRV) Indices: A Data-driven Meta-clustering Approach](https://psyarxiv.com/mwa6x/)

## Indices

- https://github.com/nliulab/HRnV-Calc#metrics-descriptions
- https://github.com/cliffordlab/PhysioNet-Cardiovascular-Signal-Toolbox#iii-guide-to-output
- https://www.mdpi.com/1424-8220/21/12/3998 Table 1. A summary of HRV indices according to their respective analysis domains.

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

- [MIT-BIH Polysomnographic Database](https://physionet.org/content/slpdb/1.0.0/)

## Contributing

We welcome your contributions! Please follow these steps to contribute:

1. Fork the repo.
2. Create a new branch (e.g., `feature/new-hrv-resource`).
3. Commit your changes to the new branch.
4. Create a Pull Request, and provide a brief description of the changes/additions.

Please make sure that the resources you add are relevant to the field of Heart Rate Variability. Before contributing, take a look at the existing resources to avoid duplicates.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
