---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
*  **School of Software, Northwestern Polytechnical University**
   *  _Sep. 2022 - July. 2025(expected)_,  Xi'an, China
   *  GPA: 3.55/4.00  
   *  Master’s Degree in Software Engineering,               
   *  Research area: Brain-Computer Interface, Machine Learning, Singal Processing, Artificial Intelligence.
*  **College of Material Science and Engineering, Zhejiang University of Technology**         
   *  _Sep. 2022 - July. 2025(expected)_  Hangzhou, China
   *  Bachelor’s Degree in Polymer Science and Engineering,
   *  GPA: 3.18/4.00, Last 2 years GPA: 3.59/4.0
   *  Key Courses: Additive Manufacturing, Finite Element Analysis, Computational Chemistry, CAE

Research Experience
======
_Research assistant_, Advisior: Prof. Hongqi Li
* **Project I: Foundational Model Application on Brain Signals (Ongoing)**  _June. 2024 - Present_
  *  _Keywords: LLMs, GPT, LLaMA, Self-supervised Learning, Brain signals_
  * Collect and preprocess large-scale public EEG datasets to build a comprehensive training corpus.
  * Pre-train models using self-supervised learning on large language models (e.g., GPT, LLaMA) and EEG-specific architectures to reconstruct neural signals.
  * Fine-tune models for EEG decoding tasks, enhancing feature extraction and reducing dependency on labeled data while generalizing across tasks.

* **Project II: Transformer-based Novel Model For Seizure Prediction (Ongoing)**  _Aug. 2024 - Present_
  *  _Keywords: Swin Transformer, Hierarchical Transformer, Seizure Prediction_
  * Inspired by Swin Transformer, Developing the Novel Transformer model, incorporating a hierarchical Transformer architecture (C12T), using specific attention mechanisms to capture spatio-temporal correlations in EEG data for accurate seizure prediction.
  * Designing the C12T Block structure to enhance global spatial interactions and long-range temporal dependencies crucial for seizure onset prediction.

* **Project III: Comprehensive Analysis of Transformer Applications in EEG Decoding**  _May. 2024 - July. 2024_
  * _keywords: Transformer Architectures, Large Models, Survey_
  * Conducted a comprehensive review of Transformer-based EEG decoding models by analyzing around 400 papers and selecting approximately 180 key publications.
  * Categorized Transformer models into basic, hybrid with other deep learning techniques, Vision Transformers, and modified models, highlighting their impact on decoding performance.
  * Defined the concept of the "Large Brain-signal Model," providing the first formal characterization for EEG signal decoding, exploring its architecture, functions, and potential impact.
  * Developed a comprehensive flowchart of Transformer architectures in EEG decoding and discussed key challenges (e.g., data diversity, model generalization) and future prospects for the field.
* **Project IV: EEG Decoding with Temporal-Spectral-Spatial Transformer** _Oct. 2023 - May. 2024_
  * CNN, Transformer, Multi-Features, Multi-Branch,
  * Developed a novel EEG decoding model, Dual-TSST, which integrates both temporal and spectral features using a dual-branch convolutional neural network to handle raw EEG and time-frequency data derived from wavelet transformations.
  * Combined extracted features using a Transformer encoder, capturing global long-range dependencies in non-stationary EEG signals, leading to superior classification performance.
  * Achieved competitive results on public datasets such as BCI IV 2a, BCI IV 2b, and SEED, with accuracy rates of 80.67%, 88.64%, and 96.65%, respectively, surpassing state-of-the-art models.
  * Demonstrated that Dual-TSST enhances EEG decoding by efficiently capturing both short-term temporal patterns and long-term spatial dependencies, paving the way for more accurate brain-computer interface applications.
*  **Project V: Generative Multichannel EEG Modeling Based on Neuronal Mass Models** _Aug. 2023 - Oct. 2023_
  *  _keyword: EEG, Generative Modeling, Neuronal Mass Models, GAN, BCI_
  * Developed a generative EEG modeling method using interconnected neuronal mass models (NMM) and a spatiotemporal source model for simulating neural signal dynamics.
  * Integrated a biophysical volume conduction model and GAN to generate high-quality, multichannel EEG signals with physiological interpretability.
  * Addressed the challenge of data scarcity in brain-computer interface (BCI) systems by creating realistic EEG signals, enabling more accessible and efficient research for neural signal decoding and BCI applications.
* **Project VI: Pix2Pix GAN for Realistic Face Generation**
  _keyword: Image Generation, GAN, Pix2Pix, U-Net, CelebA_ 
  * Developed a Pix2Pix GAN-based model with a U-Net generator and Patch GAN discriminator to generate face images from random noise.
  * Trained the model using a subset of the CelebA dataset (1,000 images), optimizing with L1 and GAN losses for image-to-image translation tasks.
  * Conducted extensive tests to evaluate the model performance at different epochs, analyzing generated image quality and training anomalies.

Skills
======
* **Programming Languages**: Python, Java, C/C++, Matlab, R
* **Data Science & Machine Learning**: Pytorch, Scikit-learn, Numpy, Scipy, Pandas, OpenCV
* **Other Tools & Technologies**: LATEX, Figma, Notion, Microsoft Office, Blender, MNE-Python, Brain-decoding
* **Research Skills**: Literature Review, Data collection, Experimental Design, Statistical Analysis, Hypothesis Testing, Scientific Writing, Academic Presentations, Citation Management
* **Language Skills**: Mandarin Chinese (Native), English (Proficiency), Japanese (Proficiency)


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
