---
title: 'Surface Multigrid via Intrinsic Prolongation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:

# Author notes (optional)
author_notes:

date: '2013-07-01T00:00:00Z'
doi: ''

weight: 2

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

abstract: This paper introduces a novel geometric multigrid solver for unstructured curved surfaces. Multigrid methods are highly efficient iterative methods for solving systems of linear equations. Despite the success in solving problems defined on structured domains, generalizing multigrid to unstructured curved domains remains a challenging problem. The critical missing ingredient is a prolongation operator to transfer functions across different multigrid levels. We propose a novel method for computing the prolongation for triangulated surfaces based on intrinsic geometry, enabling an efficient geometric multigrid solver for curved surfaces. Our surface multigrid solver achieves better convergence than existing multigrid methods. Compared to direct solvers, our solver is orders of magnitude faster. We evaluate our method on many geometry processing applications and a wide variety of complex shapes with and without boundaries. By simply replacing the direct solver, we upgrade existing algorithms to interactive frame rates, and shift the computational bottleneck away from solving linear systems.

# Summary. An optional shortened abstract.
summary: 'Hsueh-Ti Derek Liu, <b>Jiayi Eris Zhang</b>, Mirela Ben-Chen, Alec Jacobson <br>
          <i>ACM Transactions on Graphics (SIGGRAPH North America 2021)</i>'

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: uploads/surface-multigrid-high.pdf
- name: ArXiv
  url: https://arxiv.org/abs/2104.13755
- name: Project
  url: https://www.dgp.toronto.edu/projects/intrinsic-prolongation/
- name: Code
  url: https://github.com/HTDerekLiu/surface_multigrid_code
- name: Talk
  url: https://www.youtube.com/watch?v=oQdhzaD62jg


url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
