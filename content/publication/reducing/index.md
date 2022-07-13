---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Reducing Disambiguation Biases in NMT by Leveraging Explicit Word Sense Information"
authors: [Niccolò Campolungo, Tommaso Pasini, Denis Emelin, Roberto Navigli]
date: 2022-07-10
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-21T14:14:05Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Conference of the North American Chapter of the Association for Computational Linguistics (**NAACL**)*"
publication_short: ""

abstract: Recent studies have shed some light on a common pitfall of Neural Machine Translation (NMT) models, stemming from their struggle to disambiguate polysemous words without lapsing into their most frequently occurring senses in the training corpus. In this paper, we first provide a novel approach for automatically creating high-precision sense-annotated parallel corpora, and then put forward a specifically tailored fine-tuning strategy for exploiting these sense annotations during training without introducing any additional requirement at inference time. The use of explicit senses proved to be beneficial to reduce the disambiguation bias of a baseline NMT model, while, at the same time, leading our system to attain higher BLEU scores than its vanilla counterpart in 3 language pairs.

# Summary. An optional shortened abstract.
summary: "We provide a novel approach for automatically creating high-precision sense-annotated parallel corpora, and put forward a specifically tailored fine-tuning strategy for exploiting these sense annotations during training without introducing any additional requirement at inference time, for improved word sense disambiguation in machine translation."

tags: [translation, naacl, data biases, word sense disambiguation, data augmentation, fine-tuning strategies]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://aclanthology.org/2022.naacl-main.355.pdf
url_code: https://github.com/sapienzanlp/reducing-wsd-bias-in-nmt
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
