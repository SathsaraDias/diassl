---
title: "Identifying Buffet Oscillations Using Sliding-Window Dynamic Mode Decomposition"
authors:
- Sathsara Dias
- Marko Budišić
- Pat Piperni
- Brian T. Helenbrook
date: "2024-03-01T00:00:00Z"
# doi: "10.2514/1.J063929"
weight: 1

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "AIAA Journal"
publication_short: "AIAA J."

abstract: >
  Buffet is a self-sustaining oscillation that can endanger an aircraft in transonic flight. Early automatic detection of the onset of buffet from simulation data is a necessary step in optimization algorithms used to design new aircraft geometries. We use the Dynamic Mode Decomposition (DMD) eigenvalues to detect the onset of buffet from transient simulations of the OAT15A airfoil across a range of angles of attack. During transients, different eigenvalues may be expressed at different times; we process shorter segments of the data (sliding windows) in order to obtain robust, time-varying estimates of frequency of oscillation and decay/growth rates. We demonstrate that the onset of oscillation can be identified by analyzing DMD eigenvalues, and that physically different mechanisms of oscillation can additionally be identified from spatial profiles associated with DMD modes. The dominant buffeting modes can be detected through DMD before they become apparent in the physically relevant quantities, such as the coefficient of lift. We expect that such early detection of the onset of buffet could reduce the computational burden of aircraft design and expand the feasible design space.

# Summary. An optional shortened abstract.
summary: "First-author research on unsupervised learning for buffet detection using DMD and model reduction. Early detection of aerodynamic buffet using a sliding-window DMD framework."

tags:
- Dynamic Mode Decomposition
- Buffet Detection
- Unsupervised Learning
- CFD
- Aerospace

featured: true

links:
- name: Journal PDF
  url: https://arc.aiaa.org/doi/10.2514/1.J063929
- name: DOI
  url: https://doi.org/10.2514/1.J063929
- name: Download Paper (Google Drive)
  url: https://drive.google.com/file/d/1d_HpIf9t6nYgIyurCVAzrQecRnmFXbTE/view

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: "Visual summary of buffet detection using sliding-window DMD"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""

weight: 1
---

{{% alert note %}}
For supplementary technical notes, figures, or data, please contact the corresponding author.
{{% /alert %}}

<!-- 
**Supplementary notes:**  
Add additional technical explanations, figures, or code snippets here. 
-->
