---
title: 'Fast Complementary Dynamics via Skinning Eigenmodes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:

# Author notes (optional)
author_notes:

date: '2023-01-01T00:00:00Z'
doi: ''

weight: 89

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-01T00:00:00Z'

abstract: We propose a reduced-space elasto-dynamic solver that is well suited for augmenting rigged character animations with secondary motion. At the core of our method is a novel deformation subspace based on Linear Blend Skinning that overcomes many of the shortcomings prior subspace methods face. Our skinning subspace is parameterized entirely by a set of scalar weights, which we can obtain through a small, material-aware and rig-sensitive generalized eigenvalue problem. The resulting subspace can easily capture rotational motion and guarantees that the resulting simulation is rotation equivariant. We further propose a simple local-global solver for linear co-rotational elasticity and propose a clustering method to aggregate per-tetrahedra non-linear energetic quantities. The result is a compact simulation that is fully decoupled from the complexity of the mesh.

# Summary. An optional shortened abstract.
summary: 'Otman Benchekroun, <b>Jiayi Eris Zhang</b>, Siddhartha Chaudhuri, Eitan Grinspun, Yi Zhou, Alec Jacobson <br>
          <i>ACM Transactions on Graphics (SIGGRAPH North America 2023)</i> <br>'

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: uploads/fast-cd.pdf
- name: ArXiv
  url: https://arxiv.org/abs/2303.11886
- name: Project
  url: https://www.dgp.toronto.edu/projects/fast_complementary_dynamics_site/


url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---
