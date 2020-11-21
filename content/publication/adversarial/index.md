---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Detecting Word Sense Disambiguation Biases in Machine Translation for Model-Agnostic Adversarial Attacks"
authors: [Denis Emelin, Ivan Titov, Rico Sennrich]
date: 2020-11-01
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

abstract: Word sense disambiguation is a well-known source of translation errors in NMT. We posit that some of the incorrect disambiguation choices are due to models’ over-reliance on dataset artifacts found in training data, specifically superficial word co-occurrences, rather than a deeper understanding of the source text. We introduce a method for the prediction of disambiguation errors based on statistical data properties, demonstrating its effectiveness across several domains and model types. Moreover, we develop a simple adversarial attack strategy that minimally perturbs sentences in order to elicit disambiguation errors to further probe the robustness of translation models. Our findings indicate that disambiguation robustness varies substantially between domains and that different models trained on the same data are vulnerable to different attacks.

# Summary. An optional shortened abstract.
summary: "We introduce a method for the prediction of disambiguation errors based on statistical data properties, and develop a simple adversarial attack strategy that minimally perturbs sentences in order to elicit disambiguation errors to further probe the robustness of translation models."

tags: [translation, emnlp, adversarial, data biases, word sense disambiguation]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.aclweb.org/anthology/2020.emnlp-main.616.pdf
url_code: https://github.com/demelin/detecting_wsd_biases_for_nmt
#url_dataset:
#url_poster:
#url_project:
url_slides: https://tinyurl.com/y3cyutzr
#url_source:
url_video: https://slideslive.com/38939052

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
