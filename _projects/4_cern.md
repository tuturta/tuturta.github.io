---
layout: page
title: Deep Learning for Dynamic Aperture Measurement
description: Master Project (CERN) | 2022.09 - 2023.01
img: assets/img/cern.jpg
importance: 4
category: work
---

The **Dynamic Aperture (DA)** is a key concept in accelerator physics, defining the region of phase space where particle motion remains stable over time. Its accurate measurement is crucial for understanding beam losses and improving the operation of accelerators such as the LHC at CERN, as well as for designing future accelerators. Traditional methods approximate the DA as a regular circle or rely on numerical integration, which can be slow or insufficiently precise due to nonlinear effects that create complex, irregular shapes.

This project explores the use of **Deep Learning**, specifically **Graph Neural Networks (GNNs)**, to efficiently and accurately estimate the 2D volume of the DA. Particles in the DA are represented as nodes in a graph, with edges connecting nearby particles. This allows the network to distinguish simply-connected regions of phase space from disconnected, unstable particles. Two main GNN architectures were studied: **Graph Convolutional Networks (GCN)** and **GraphSAGE**, implemented in three model variants (GCN, SIMPLE, and SAGE).  

Since no labeled dataset of DA shapes existed, a large synthetic dataset of **275,000 DA samples** was generated, simulating complex, irregular shapes with connected regions and islands. This dataset was used to train the models on EPFL's SCITAS supercomputer. All models achieved high accuracy (~98%) on the synthetic test set, while the **SAGE model** performed best on real DA data from the LHC (~91% accuracy), demonstrating robust generalization to unseen structures.

Compared to classical numerical methods such as OpenCV’s `contourArea()`, the GNNs offer a **significant speed advantage** while maintaining competitive accuracy, making them a promising tool for scalable DA estimation. Future extensions include generating larger, more diverse datasets, considering more graph connectivity, and exploring cutting-edge architectures such as Vision Transformers to extend volume estimates into 4D phase space.  

For a detailed description of the project, you can access the [full PDF](/assets/pdf/cern.pdf).

**Project Supervisor & Contact:**  
[Dr. Davide Di Croce](mailto:dicrocedavide@gmail.com) – CERN, NextGen Trigger Project