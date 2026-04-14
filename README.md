# Measurement, Processing, and Analysis of MEMS-FPI Spectrophotometer Data

This repository contains the documentation and research data related to the internship project conducted at the **Istituto Nazionale di Ricerca Metrologica (INRIM)** in collaboration with **Politecnico di Torino**.

## 📌 Project Overview
The project focuses on the acquisition and processing of data from **MEMS-FPI Spectrum Modules** and the **MS9740A Spectrum Analyzer**. The core objective is the 3D reconstruction of samples using **Optical Coherence Tomography (OCT)** technology.

OCT is a non-invasive imaging technique, similar to ultrasound but using light waves. By analyzing the intensity and delay of reflected waves through interferometry, it is possible to achieve high-resolution 3D images (micrometric resolution) with a depth of several millimeters.

## 🛠 Technology Stack & Tools
* **Hardware:** * MEMS-FPI Spectrum Module (Hamamatsu)
    * MS9740A Optical Spectrum Analyzer
    * Interferometric setup (Beam Splitters, Reference Mirrors, Photodetectors)
* **Software:** * **MATLAB:** Used for data analysis, statistical verification, and 3D prototyping.
    * **Hamamatsu Driver For MEMS-FPI:** Used for real-time data acquisition and initial spectral plotting.

## 🔬 System Architecture
The measurement system is based on an interferometric layout consisting of:
1.  **Swept Source (SS):** The MEMS-FPI module acting as the photon source.
2.  **Beam Splitter (BS):** Divides the light beam toward the sample and the reference mirror.
3.  **Reference Mirror (REF):** Reflects the reference signal.
4.  **Sample (SMP):** The object under scan for data acquisition.
5.  **Photodetector (PD):** Converts the optical signal into an electrical signal proportional to the radiation intensity.
6.  **Digital Signal Processing (DSP):** Computer-based processing of discrete data saved in `.txt` format to verify precision and reconstruct the 3D model.

## 📊 Key Results
* Successful implementation of a data processing pipeline in MATLAB.
* Verification of data accuracy within defined tolerance ranges.
* Generation of 3D prototypes (e.g., silicon wafer slices) using laser scanning data.
* Automated plotting of wavelength vs. intensity ratios.

## 📁 Repository Structure
* `relazione_finale.pdf`: The full technical report detailing the internship activities, theoretical background, and experimental results.
  

## 🎓 About the Author
* **Student:** Menghan Xu (Politecnico di Torino)
* **Academic Tutor:** Prof. Claudio Passerone
* **Company Tutor:** Dr. Massimo Zucco (INRIM)
* **Internship Period:** 2021/2022

---
*This project was carried out at the INRIM - Palazzina 7 (Mechanics/Lengths Section) in Turin, Italy.*
