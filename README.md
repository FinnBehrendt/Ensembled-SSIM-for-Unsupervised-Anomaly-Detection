# Ensembled-SSIM-for-Unsupervised-Anomaly-Detection
This Repository contains code for the paper "DIFFUSION MODELS WITH ENSEMBLED STRUCTURE-BASED ANOMALY SCORING FOR UNSUPERVISED ANOMALY DETECTION".

The paper is accepted at the IEEE International Symposium on Biomedical Imaging (ISBI) 2024 conference.

A preprint is available [Here](https://arxiv.org/abs/2403.14262)

**Abstract**

Supervised deep learning techniques show promise in medical image analysis. However, they require comprehensive annotated data sets, which poses challenges, particularly for rare diseases. Consequently, unsupervised anomaly detection (UAD) emerges as a viable alternative for pathology segmentation, as only healthy data is required for training. However, recent UAD anomaly scoring functions often focus on intensity only and neglect structural differences, which impedes the segmentation performance. This work investigates the potential of Structural Similarity (SSIM) to bridge this gap. SSIM captures both intensity and structural disparities and can be advantageous over the classical l1 error. However, we show that there is more than one optimal kernel size for the SSIM calculation for different pathologies. Therefore, we investigate an adaptive ensembling strategy for various kernel sizes to offer a more pathology-agnostic scoring mechanism. We demonstrate that this ensembling strategy can enhance the performance of DMs and mitigate the sensitivity to different kernel sizes across varying pathologies, highlighting its promise for brain MRI anomaly detection.

**Citation**


    @article{behrendt2024diffusion,
      title={Diffusion Models with Ensembled Structure-Based Anomaly Scoring for Unsupervised Anomaly Detection},
      author={Behrendt, Finn and Bhattacharya, Debayan and Maack, Lennart and Kr{\"u}ger, Julia and Opfer, Roland and Mieling, Robin and Schlaefer, Alexander},
      journal={arXiv preprint arXiv:2403.14262},
      year={2024}
    }

**Code**

The code will be available soon.
