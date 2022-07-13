---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Wino-X: Multilingual Winograd Schemas for Commonsense Reasoning and Coreference Resolution"
authors: [Denis Emelin, Rico Sennrich]
date: 2021-11-07
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-21T14:14:05Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the Conference on Empirical Methods in Natural Language Processing (**EMNLP**)*"
publication_short: ""

abstract: Winograd schemas are a well-established tool for evaluating coreference resolution (CoR) and commonsense reasoning (CSR) capabilities of computational models. So far, schemas remained largely confined to English, limiting their utility in multilingual settings. This work presents Wino-X, a parallel dataset of German, French, and Russian schemas, aligned with their English counterparts. We use this resource to investigate whether neural machine translation (NMT) models can perform CoR that requires commonsense knowledge and whether multilingual language models (MLLMs) are capable of CSR across multiple languages. Our findings show Wino-X to be exceptionally challenging for NMT systems that are prone to undesirable biases and unable to detect disambiguating information. We quantify biases using established statistical methods and define ways to address both of these issues. We furthermore present evidence of active cross-lingual knowledge transfer in MLLMs, whereby fine-tuning models on English schemas yields CSR improvements in other languages.

# Summary. An optional shortened abstract.
summary: "We introduce the novel Wino-X benchmark to investigate whether translation models can perform coreference resolution that requires commonsense knowledge and whether multilingual language models are capable of commonsense reasoning across multiple languages. Our findings indicate that models are prone to biases and often fail to identify disambiguating information."

tags: [translation, coreference resolution, commonsense reasoning, emnlp, data biases]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://aclanthology.org/2021.emnlp-main.670.pdf
url_code: https://github.com/demelin/Wino-X
#url_dataset:
#url_poster:
#url_project:
#url_source:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
