# 🚢 Radar–Vision Fusion for Ship Tracking

This study proposes a weakly supervised cross-modal representation learning framework for ship tracking, enabling feature-level interaction between radar and vision while reducing reliance on manual annotations. Radar and camera measurements are processed into motion-related time series, forming the radar and visual feature streams. A pseudo-labelling strategy combining geometric consistency, motion consistency, and signal confidence is developed to generate high-confidence radar–vision pairs. These pairs supervise a Transformer-based dual-encoder that maps multi-modal features into a shared latent space. A novel ordinal loss is incorporated alongside a contrastive loss to optimise the network under physical constraints. The fused dual-modal outputs are overlaid onto video frames, providing intuitive situational awareness for bridge authorities and supporting ship–bridge collision early warning.

---

## 📺 Display

This repository provides visual demonstrations of radar–vision fusion.  
The display videos have been temporally accelerated for ease of viewing.

All videos are available under the **Release** section of this repository.


These examples illustrate:

- Transformer-based dual-encoder cross-modal alignment  
- Radar–vision pseudo-labelling quality  
- Ship-motion trajectory fusion  
- Enhanced situational awareness for long-distance waterway monitoring  

---

## 📦 Full Dataset Access

To access the **full dataset** , please contact the corresponding authors:

**Name:** Yiming Zhang or Hao Wang  
**Email:** yiming.zhang@seu.edu.cn, wanghao1980@seu.edu.cn  

Requests should include:

- Your name  
- Institution  
- Intended use of the dataset  

The dataset is available **for non-commercial research purposes only**.

---

## 📜 License

Visualisations in this repository are shared under the terms of the **LICENSE** file.  
Full dataset access requires prior permission from the corresponding authors.


