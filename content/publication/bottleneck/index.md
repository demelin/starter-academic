---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Widening the Representation Bottleneck in Neural Machine Translation with Lexical Shortcuts"
authors: [Denis Emelin, Ivan Titov, Rico Sennrich]
date: 2019-08-01
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: 2020-11-21T14:13:58Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Widening the Representation Bottleneck in Neural Machine Translation with Lexical Shortcuts"
publication_short: ""

abstract: The transformer is a state-of-the-art neural translation model that uses attention to iteratively refine lexical representations with information drawn from the surrounding context. Lexical features are fed into the first layer and propagated through a deep network of hidden layers. We argue that the need to represent and propagate lexical features in each layer limits the model’s capacity for learning and representing other information relevant to the task. To alleviate this bottleneck, we introduce gated shortcut connections between the embedding layer and each subsequent layer within the encoder and decoder. This enables the model to access relevant lexical content dynamically, without expending limited resources on storing it within intermediate states. We show that the proposed modification yields consistent improvements over a baseline transformer on standard WMT translation tasks in 5 translation directions (0.9 BLEU on average) and reduces the amount of lexical information passed along the hidden layers. We furthermore evaluate different ways to integrate lexical connections into the transformer architecture and present ablation experiments exploring the effect of proposed shortcuts on model behavior.

# Summary. An optional shortened abstract.
summary: We argue that the need to represent and propagate lexical features in each layer limits the transformer’s capacity for learning and representing contextual information. To alleviate this bottleneck, we introduce gated shortcut connections between the embedding layer and each subsequent layer within the encoder and decoder, which enables the model to access relevant lexical content dynamically, without expending limited resources on storing it within intermediate states.

tags: [translation, wmt, transformer, improved architecture, word sense disambiguation]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.aclweb.org/anthology/W19-5211.pdf
url_code: https://github.com/demelin/transformer_lexical_shortcuts
#url_dataset:
#url_poster:
#url_project:
url_slides: https://tinyurl.com/y5sucvql
#url_source:
#url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---
