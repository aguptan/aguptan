# Amal Guptan

- Biomedical engineer experienced in algorithm design and large-scale data analysis across various modalities, with a strong ability to abstract complex problems and select suitable computational modeling strategies.
- Experienced in system-level design, pipeline planning, and integrating tools across multi-modal data streams.
- Developed pipelines for motor control, image processing, statistical modeling, and signal analysis (physiological and fluid-based) using MATLAB and Python. 

---

## About Me
- M.S. Biomedical Engineering, The George Washington University (2024)  
- B.S. Biomedical Engineering, University of Rhode Island (2022)  
- Current Role: Biomedical Data Engineer (Research Technician) at Children's National Medical Center (CNMC)  

---

## Technical Skills
**Languages**: Python, MATLAB, R  
**Frameworks & Libraries**: PyTorch, NumPy, Pandas, SciPy, OpenCV, scikit-learn, Matplotlib, Bioconductor (R)  
**Signal & Image Processing**: STFT, FIR/IIR Filtering, Artifact Removal, Feature Extraction (SIFT/ORB), Wavelet/Fourier Analysis  
**Machine Learning & Optimization**: Vision Transformers, PCA, Clustering (DBSCAN, K-Means), Hyperparameter Tuning (Optuna), Cross-validation (K-Fold, LOO)  
**Workflow Tools**: Git, Jupyter, VS Code, Anaconda, Spyder  
**Systems & Workflow Design**: Modular pipelines, dataset scaling, automation, toolchain integration  

---

## Selected Projects

### EEG-Based Delirium Classification
- Designed and deployed a full EEG classification pipeline using MATLAB and Python, integrating STFT-based Feature Extraction and Vision Transformer-based deep learning.  
- Designed and delivered a scalable solution for multi-subject EEG analysis across large pediatric datasets in MATLAB. Currently implementing multiprocessing to speed up spectrogram-creation for about 150 pediatric patients.
- Built a modular object-oriented Python framework to move and copy files using the shutil library, fine-tune and validate Vision Transformer models for pediatric delirium prediction, incorporating Youden’s J statistic, Leave-One-Out, and K-Fold cross-validation for patient-specific models.
- Optimized the deep learning frameworks for efficient parallelization for fold-wise GPU training.
[Delirium EEG Repository](https://github.com/aguptan/DeliriumEEG)  

---

### Tiling and Stitching Pipeline for High-Throughput Microscopy
- Owned the design and implementation of a Python-based imaging automation system for the Olympus BX-63 microscope.
- Integrated Pycro-Manager with Micro-Manager 2.0 and servo-controlled stage movement to replace commercial stitching tools, significantly reducing lab costs by $15K.
- Building an SIFT/ORB stitching pipeline and regularized least-squares alignment; applied Optuna multi-objective HPO + K-fold CV with Pareto/inter-fold analysis to a dataset-aware auto-tuner for new datasets.
[1. Hardware Repository](https://github.com/aguptan/MicroscopeScanTool)  [2. Stitching Algorithm Repository](https://github.com/aguptan/StitchingAlgorithm)

---

### Continuous Non-Invasive Blood Pressure Monitoring
- Led algorithm design for a novel fluid-based system for continuous blood pressure monitoring, driving research, and implementation to define key physiological parameters.
- Owned the design and deployment of signal processing and data-driven algorithms, including FIR/IIR & Notch Filtering, Oscillogram Generation, and Envelope-based Visualization
- Helped with developing and debugging the code for efficient data acquisition (Arduino) by implementing validation statements and editing faulty code.  
[BPP Repository](https://github.com/aguptan/Blood_Pressure_Project)  

---

## Teaching and Research
- Teaching Assistant, Introductory Genetics (GWU, Fall 2023)  
- Assisted Dr. Julia Omotade with course instruction and mentoring.  
- Awarded a paid fellowship for academic excellence.  

---

## Certifications
- Statistical Analysis of Genome-Scale Data Science – Cold Spring Harbor Laboratory  
- PyTorch, Deep Learning, and C++ Courses – Coursera (in progress)  

---

## Using AI in Coding
- **Breaking down complex problems & system design**
  - **Requirements → modules:** 
		- Turn problem statements into a module maps (data loaders, preprocessing, model/train loops, evaluation, logging) for architecture exploration.
  
  - **Architecture exploration:** 
		- Compare design options (e.g., LOOCV vs K-Fold, single vs multi-objective HPO, patient- vs electrode-level analysis) 
		- Draft pros/cons before implementation.
        - Produce stepwise build plans (prep → train → validate → analyze) to keep work scoped and reproducible.
		
- **Speeding up development**

- **Refinement**
  - **Speed**
  - **Refactoring** 
  - **Robustness** 

- **Aid with documentation**

---

## Contact
- [Email](mailto:aguptan@gmail.com)
- [GitHub](https://github.com/aguptan)
- [LinkedIn](https://www.linkedin.com/in/amal-g-107002163/)

