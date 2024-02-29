---
title: 'Robust Eulerian-on-Lagrangian Rods'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Rosa M. Sánchez-Banderas
  - Alejandro Rodríguez
  - admin
  - Miguel A. Otaduy

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2020-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In * ACM Transactions on Graphics (Proc. of SIGGRAPH)*
publication_short: In *ACM ToG*

abstract: This paper introduces a method to simulate complex rod assemblies and stacked layers with implicit contact handling, through Eulerian-on-Lagrangian (EoL) discretizations. Previous EoL methods fail to handle such complex situations, due to ubiquitous and intrinsic degeneracies in the contact geometry, which prevent the use of remeshing and make simulations unstable. We propose a novel mixed Eulerian-Lagrangian discretization that supports accurate and efficient contact as in EoL methods, but is transparent to internal rod forces, and hence insensitive to degeneracies. By combining the standard and novel EoL discretizations as appropriate, we derive mixed statics-dynamics equations of motion that can be solved in a unified manner with standard solvers. Our solution is simple and elegant in practice, and produces robust simulations on large-scale scenarios with complex rod arrangements and pervasive degeneracies. We demonstrate our method on multi-layer yarn-level cloth simulations, with implicit handling of both intra and inter-layer contacts.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#links:
#  - name: Demo
#    url: https://drive.google.com/drive/folders/1jaQuyP20mfPv1q8KaJkdYaVXQE1Sklzg?usp=sharing

url_pdf: 'uploads/papers/sanchez2020robusteolrods.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'http://mslab.es/projects/RobustEOLRods/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=Y2g5Fn18lNk'

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
