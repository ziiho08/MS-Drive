

# MS-Drive 

<div align="center">

[![Paper](https://img.shields.io/badge/📄_Paper-Coming_Soon-b31b1b?style=for-the-badge)](https://arxiv.org/)
[![Dataset](https://img.shields.io/badge/🗂_Dataset-Request_Access-FF6B35?style=for-the-badge)](#-access-and-usage)
[![License](https://img.shields.io/badge/License-Academic_Only-4A90D9?style=for-the-badge)](LICENSE)

</div>

## Abstract

<br>

The Multi-spectral rPPG Dataset for Remote Physiological Estimation in Real Driving Scenarios (MS-Drive) dataset includes synchronized RGB and NIR video recordings alongside ground truth ECG signals from 50 participants (28 male, 22 female, aged 20–34) captured during vehicle operation.
The dataset was designed to benchmark remote photoplethysmography (rPPG) algorithms under naturalistic driving conditions, with particular emphasis on skin tone diversity, unconstrained head motion, and dual-modality sensing.
MS-Drive covers five Fitzpatrick skin types (2–6), recorded at 1920×1080 (RGB) and 848×480 (NIR) at 30 FPS using an Intel RealSense D435i with an 850 nm NIR illuminator, with concurrent 3-lead ECG acquisition at 128 Hz via a Shimmer3 unit.

</div>

<br>


## 🎬 Sample Recordings
<br>
<div align="center">
<table>
  <tr>
    <td><img src="./assets/sample_video_1.gif" width="360" alt="RGB sample"/></td>
    <td><img src="./assets/sample_video_2.gif" width="360" alt="NIR sample"/></td>
  </tr>
  <tr>
    <td><img src="./assets/sample_video_3.gif" width="360" alt="RGB sample"/></td>
    <td><img src="./assets/sample_video_4.gif" width="360" alt="NIR sample"/></td>
  </tr>
</table>
<sub> Synchronized RGB (1920×1080) and NIR (848×480) sample clips. The red and blue signals denote the ground truth ECG and the estimated rPPG waveform, respectively. </sub>
</div>

## 🗂️ Dataset Structure

<br>

```
MS-Drive/
├── subject01/
│   ├── rgb.mp4           # 1920×1080
│   ├── nir.mp4           # 848×480  
│   ├── ecg.csv           # 3-lead ECG
│   └── GT_HR.csv         # Calculated HR from ECG
├── subject02/
│   └── ...
├── subject50/
└── README.md
```

<br>

## 🔑 Access and Usage

<br>

> **MS-Drive is released for academic research only. Commercial use is strictly prohibited.**

<br>

**To request access, follow these steps:**

**1.** Download the [Data Release Agreement](./MS-Drive_Database_Release_Agreement.pdf)

**2.** Complete, sign, and send the agreement from your **institutional email** to `jihochoi@jbnu.ac.kr`
  - Subject line: `MS-Drive Access Request — <Your Institution>`
  - Please include your institution's website, relevant publications, and a description of your intended use

**3.** Requests submitted by **students** will not be processed — please have a faculty member send the request

<br>



## 📄 Citation

If you use **MS-Drive** or find this repository useful for your research, please cite our paper:

```bibtex
@misc{choi2026msrppgmultispectralstatespace,
  title         = {MS-rPPG: Multi-spectral State Space Model for Remote Photoplethysmography in Driver Monitoring Systems},
  author        = {Choi, Jiho and Lee, Sang Jun},
  year          = {2026},
  eprint        = {2606.21115},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV},
  url           = {https://arxiv.org/abs/2606.21115}
}
```


<br>

## 📬 Contact

<br>

Questions about the dataset or access process? Open a [GitHub Issue](../../issues) or reach out directly at `jihochoi@jbnu.ac.kr`.

<br>

<div align="center">
  <sub>© 2025 [Machine Intelligence Lab / Jeonbuk National University]. Released for academic use only.</sub>
</div>
