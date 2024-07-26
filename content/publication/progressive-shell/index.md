---
title: 'Progressive Shell Quasistatics for Unstructured Meshes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:

# Author notes (optional)
author_notes:

date: '2023-09-01T00:00:00Z'
doi: ''

weight: 87

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-01T00:00:00Z'

abstract: Thin shell structures exhibit complex behaviors critical for modeling and design across wide-ranging applications. Capturing their mechanical response requires finely detailed, high-resolution meshes. Corresponding simulations for predicting equilibria with these meshes are expensive, whereas coarse-mesh simulations can be fast but generate unacceptable artifacts and inaccuracies. The recently proposed progressive simulation framework [Zhang et al. 2022] offers a promising avenue to address these limitations with consistent and progressively improving simulation over a hierarchy of increasingly higher-resolution models. Unfortunately, it is currently severely limited in application to meshes and shapes generated via Loop subdivision. <br><br> We propose Progressive Shells Quasistatics to extend progressive simulation to the high-fidelity modeling and design of all input shell (and plate) geometries with unstructured (as well as structured) triangle meshes. To do so, we construct a fine-to-coarse hierarchy with a novel nonlinear prolongation operator custom-suited for curved-surface simulation that is rest-shape preserving, supports complex curved boundaries, and enables the reconstruction of detailed geometries from coarse-level meshes. Then, to enable convergent, high-quality solutions with robust contact handling, we propose a new, safe, and efficient shape-preserving upsampling method that ensures non-intersection and strain limits during refinement. With these core contributions, Progressive Shell Quasistatics enables, for the first time, wide generality for progressive simulation, including support for arbitrary curved-shell geometries, progressive collision objects, curved boundaries, and unstructured triangle meshes – all while ensuring that preview and final solutions remain free of intersections. We demonstrate these features across a wide range of stress tests where progressive simulation captures the wrinkling, folding, twisting, and buckling behaviors of frictionally contacting thin shells with orders-of-magnitude speed-up in examples over direct fine-resolution simulation.

# Summary. An optional shortened abstract.
summary: '<b>Jiayi Eris Zhang</b>, Jérémie Dumas, Yun (Raymond) Fei, Alec Jacobson, Doug L. James, Danny M. Kaufman <br>
          <i>ACM Transactions on Graphics (SIGGRAPH Asia 2023) </i> <br>'

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: uploads/psq-combined.pdf
- name: Project
  url: https://pcs-sim.github.io/psq/

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false


---
