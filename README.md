# ☁️✨ Enhanced Hybrid Cloud Removal on Sentinel-2 Imagery using STGAN + CycleGAN

**🚀 Deep Learning for a Clearer Earth View **

---

## 🧠 Project Summary

**-Cloud cover poses a significant challenge for satellite imagery analysis, obstructing surface 
observations and creating data gaps that impede various applications, including land cover 
classification, weather forecasting, and disaster monitoring.
-The proposed hybrid model leverages 
the temporal context provided by STGAN to generate initial cloud-free images by processing sequences 
of satellite images over time. These initial images are then refined using CycleGAN, which employs 
cycle consistency loss to ensure the transformation between cloudy and cloud-free images preserves 
essential features and realism.
-This work demonstrates the potential of integrating spatiotemporal and cycle-consistent approaches to significantly enhance cloud removal 
processes, offering a robust solution for real-time monitoring and analysis in various satellite imagery 
downstream applications**


This project introduces a **hybrid deep learning pipeline** combining:

- 🛰️ **Spatio-Temporal GAN (STGAN)** to utilize image sequences across time and maintains temporal consistency.
- 🎨 **Cycle-Consistent GAN (CycleGAN)** to maintain cycle consistency loss and enhances spatial refinement for cloud realism.
- 🌍 Built on Sentinel-2 multi-temporal data, our model ensures both **temporal coherence** and **visual fidelity** for downstream tasks like environmental monitoring, land classification, and urban planning.

---

## 📌 Highlights

✅ Hybrid architecture using **STGAN + CycleGAN**  
✅ High-quality reconstruction with **Cycle Consistency + Temporal Loss**  

---

✨ Future Enhancements

Generalize the model across multi-sensor datasets

Real-time deployment on clouds using dashboard

Try to integrate physical cloud distortion models

---
