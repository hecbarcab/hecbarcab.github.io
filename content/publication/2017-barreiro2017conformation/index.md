---
title: 'Conformation Constraints for Efficient Viscoelastic Fluid Simulation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ignacio García-Fernández
  - Iván Alduán
  - Miguel A. Otaduy

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2017-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Graphics (Proceedings of ACM SIGGRAPH Asia)*
publication_short: In *ACM ToG*

abstract: The simulation of high viscoelasticity poses important computational challenges. One is the diffculty to robustly measure strain and its derivatives in a medium without permanent structure. Another is the high stiffness of the governing differential equations. Solutions that tackle these challenges exist, but they are computationally slow. We propose a constraint-based model of viscoelasticity that enables effcient simulation of highly viscous and viscoelastic phenomena. Our model reformulates, in a constraint-based fashion, a constitutive model of viscoelasticity for polymeric fluids, which defines simple governing equations for a conformation tensor. The model can represent a diverse palette of materials, spanning elastoplastic, highly viscous, and inviscid liquid behaviors. In addition, we have designed a constrained dynamics solver that extends the position-based dynamics method to handle effciently both position-based and velocity-based constraints. We show results that range from interactive simulation of viscoelastic effects to large-scale simulation of high viscosity with competitive performance.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/papers/barreiro2017conformation.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'uploads/videos/barreiro2017conformation.m4v'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
