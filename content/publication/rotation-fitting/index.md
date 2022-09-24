---
title: 'Fast Updates for Least-Squares Rotational Alignment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:

# Author notes (optional)
author_notes:

date: '2013-07-01T00:00:00Z'
doi: ''

weight: 3

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'


abstract: Across computer graphics, vision, robotics and simulation, many applications rely on determining the 3D rotation that aligns two objects or sets of points. The standard solution is to use singular value decomposition (SVD), where the optimal rotation is recovered as the product of the singular vectors. Faster computation of only the rotation is possible using suitable parameterizations of the rotations and iterative optimization. We propose such a method based on the Cayley transformations. The resulting optimization problem allows better local quadratic approximation compared to the Taylor approximation of the exponential map. This results in both faster convergence as well as more stable approximation compared to other iterative approaches. It also maps well to AVX vectorization. We compare our implementation with a wide range of alternatives on real and synthetic data. The results demonstrate up to two orders of magnitude of speedup compared to a straightforward SVD implementation and a 1.5-6 times speedup over popular optimized code.

# Summary. An optional shortened abstract.
summary: '<b>Jiayi Eris Zhang</b>, Alec Jacobson, Marc Alexa <br>
          <i>Computer Graphics Forum (Eurographics 2021)</i>'

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}
