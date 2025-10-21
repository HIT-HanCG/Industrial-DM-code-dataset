# 🏭 Industrial Data Matrix (DM) Code Dataset

This repository contains a collection of **industrial-grade Data Matrix (DM) code datasets**, gathered from real-world production environments in multiple industries, including:

- 📦 **Printed Circuit Board (PCB) manufacturing**
- ⚙️ **Wheel manufacturing**
- 🔧 **Electronic assembly & SMT (Surface Mount Technology)**

---

## 📖 Overview

The **Data Matrix (DM) code** is a two-dimensional barcode widely used in industrial production for **product traceability, quality control, and manufacturing process tracking**.

This dataset is built to support research and application development in **industrial machine vision**, particularly focusing on **DM code detection, localization, and decoding** under various challenging conditions such as:

- Lighting variation and glare  
- Dirty or scratched surfaces  
- Low contrast or motion blur  
- Different materials and printing methods  

---

## 📂 Dataset Structure

```bash
dataset/
│
├── PCB/
│   ├── aluminum/
|       ├──images/
│   ├── copper/
|       ├──images/
│   ├── metal/
|       ├──images/
│   ├── resin/
|       ├──images/       
│   
│
├── Ohter/
│   ├── images/

Each industry subfolder contains:

images/: Original DM code image samples captured from industrial environments

```

## 🧠 Applications


This dataset can be used for a variety of research and engineering purposes, including but not limited to:

Industrial DM code detection and decoding algorithm development

Deep learning–based computer vision model training and evaluation

Smart manufacturing systems for automated product traceability

Benchmarking for robustness under industrial noise and environmental variation

## ⚙️ Technical Notes

Images are captured using multiple types of industrial cameras and lighting setups

Includes samples from metal, PCB, plastic, and printed surfaces

Compatible with standard computer vision frameworks (e.g., OpenCV, PyTorch, TensorFlow)

## 📜 License & Usage

This dataset is provided for academic and non-commercial research purposes only.
For commercial usage, collaboration, or extended dataset access, please contact the repository maintainer.

## 🤝 Citation

If you use this dataset in your research, please cite this repository as follows:
@dataset{industrial_dm_dataset,
  author    = {Chungang Han},
  title     = {Industrial Data Matrix (DM) Code Dataset},
  year      = {2025},
  url       = {https://github.com/yourusername/industrial-dm-dataset},
  note      = {Dataset collected from PCB, wheel, and electronic assembly industries for industrial DM code research.}
}
## 📬 Contact

For questions, collaborations, or dataset contributions:
📧 Email: chunghan@stu.hit.edu.cn

🌐 GitHub: [https://github.com/HIT-HanCG/Industrial-DM-code-dataset]

Last Updated: October 2025
