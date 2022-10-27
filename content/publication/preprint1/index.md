---
title: "An example preprint / working paper"
authors:
- admin
date: "2022-10-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Distributed stochastic gradient descent (SGD) with gradient compression has emerged as a communication-efficient solution to accelerate distributed learning. Top-K sparsification is one of the most popular gradient compression methods that sparsifies the gradient in a fixed degree during model training. However, there lacks an approach to adaptively adjust the degree of sparsification to maximize the potential of model performance or training speed. This paper addresses this issue by proposing a novel adaptive Top-K SGD framework, enabling adaptive degree of sparsification for each gradient descent step to maximize the convergence performance by exploring the trade-off between communication cost and convergence error. Firstly, we derive an upper bound of the convergence error for the adaptive sparsification scheme and the loss function. Secondly, we design the algorithm by minimizing the convergence error under the communication cost constraints. Finally, numerical results show that the proposed adaptive Top-K in SGD achieves a significantly better convergence rate compared with the state-of-the-art methods.

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'


---