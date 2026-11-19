---
title: "GVGS: Gaussian Visibility-Aware Multi-View Geometry for Accurate Surface Reconstruction"
collection: publications
permalink: /publication/2026-ACM-MM-GVGS
date: 2026-11-09
venue: "34th ACM International Conference on Multimedia (MM '26)"
link: "https://doi.org/10.1145/3767308.3835176"
github: "https://github.com/GVGScode/GVGS"
citation: >-
  <b>Mai Su</b>, Qihan Yu, Zhongtao Wang, Yilong Li, Chengwei Pan, Yisong Chen, Guoping Wang, and Fei Zhu (2026).
  <i>GVGS: Gaussian Visibility-Aware Multi-View Geometry for Accurate Surface Reconstruction</i>.
  In Proceedings of the 34th ACM International Conference on Multimedia (MM '26), Rio de Janeiro, Brazil, pp. 9128–9136.
abstract: >-
  3D Gaussian Splatting (3DGS) has emerged as a highly efficient representation for novel view synthesis.
  However, extracting accurate surfaces from 3DGS remains challenging due to unreliable geometric supervision.
  Existing methods heavily rely on depth-based reprojection for visibility estimation and multi-view consistency.
  This creates a fundamental circular dependency: precise visibility estimation requires accurate depth, yet depth supervision itself is conditioned on visibility.
  To break this cycle, we rethink multi-view geometric supervision through the lens of visibility, modeling it directly at the Gaussian level.
  Specifically, we propose a Gaussian Visibility-aware Multi-View (GVMV) geometric consistency formulation.
  By aggregating the cross-view visibility of shared Gaussians, GVMV enables robust supervision specifically over co-visible regions.
  Furthermore, to effectively integrate monocular depth priors, we introduce a progressive Quadtree-calibrated Depth Constraint (QDC).
  Guided by our visibility formulation, QDC performs block-wise affine calibration to mitigate scale ambiguity while strictly preserving local geometric structures.
  Extensive experiments on the DTU and Tanks and Temples benchmarks demonstrate that our approach consistently outperforms prior Gaussian-based methods in surface reconstruction accuracy.
  Our code is fully open-sourced and available at https://github.com/GVGScode/GVGS.
---
