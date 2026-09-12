# fMRI-Anhedonia-Brain-Connectivity

## Anhedonia Symptoms: The Assessment of Brain Functional Mechanism Following Music Stimuli Using Functional Magnetic Resonance Imaging

This repository presents a research project investigating the functional brain mechanisms associated with anhedonia during music stimulation using functional magnetic resonance imaging (fMRI).

The study focused on differences in brain responses and effective connectivity among healthy individuals, depressed patients without anhedonia, and depressed patients with anhedonia.

## Research Question

How are brain functional responses and effective connectivity associated with anhedonia during music stimulation in patients with major depressive disorder?

## Study Focus

- Anhedonia
- Major depressive disorder
- Music stimulation
- Functional magnetic resonance imaging (fMRI)
- Brain activation
- Effective connectivity
- Dynamic causal modeling (DCM)
- Emotion-related brain networks

## Study Design

The study included three groups:

- 20 healthy controls
- 25 depressed patients without anhedonia
- 24 depressed patients with anhedonia

Participants underwent fMRI while listening to positive and negative Iranian music stimuli.

The music task included 50 music tracks, with each track presented for 12 seconds.

## MRI Acquisition

MRI data were acquired using a 3 Tesla Siemens MAGNETOM Prisma scanner with a 20-channel head coil.

Structural T1-weighted images were acquired using an MPRAGE sequence. Functional images were acquired using a T2*-weighted gradient-echo EPI sequence.

Functional MRI parameters included:

- TR = 3000 ms
- TE = 25 ms
- Flip angle = 90°
- FOV = 220 mm
- Matrix = 64 × 64
- Slice thickness = 3 mm
- 230 volumes

## fMRI Preprocessing

The fMRI data were processed using SPM12 in MATLAB.

The preprocessing pipeline included:

- Slice timing correction
- Realignment
- Co-registration
- Segmentation
- Normalization
- Spatial smoothing

A general linear model (GLM) was then used to investigate brain responses to the music stimuli.

## Brain Regions of Interest

The analysis focused on several emotion-related brain regions, including:

- Supragenual anterior cingulate cortex (sgACC)
- Subgenual anterior cingulate cortex
- Amygdala
- Fusiform gyrus

## Effective Connectivity Analysis

Dynamic causal modeling (DCM) was used to investigate effective connectivity between the selected brain regions.

The analysis examined how music stimulation influenced interactions between emotion-related brain regions and whether these connectivity patterns differed between the study groups.

Model identification and group-level analysis were performed, with false discovery rate (FDR) correction applied to statistical results.

## Research Workflow

```text
Music Stimulation
        ↓
fMRI Acquisition
        ↓
SPM12 Preprocessing
        ↓
General Linear Model
        ↓
Brain Activation
        ↓
Region of Interest Selection
        ↓
Dynamic Causal Modeling
        ↓
Effective Connectivity
        ↓
Group-Level Analysis
        ↓
Anhedonia-Related Brain Mechanisms
```

## Software and Tools

- MATLAB
- SPM12
- Dynamic Causal Modeling (DCM)
- General Linear Model (GLM)

## Publication

Faramarzi, A., Sharini, H., Shanbehzadeh, M., Yousef Pour, M., Fooladi, M., Jalalvandi, M., Amiri, S., & Kazemi-Arpanahi, H. (2022).

**Anhedonia Symptoms: The Assessment of Brain Functional Mechanism Following Music Stimuli Using Functional Magnetic Resonance Imaging.**

*Psychiatry Research: Neuroimaging, 326, 111532.*

## Author

**Ayob Faramarzi**

Biomedical Engineering | Neuroimaging | fMRI | MRS | Brain Connectivity | Machine Learning
