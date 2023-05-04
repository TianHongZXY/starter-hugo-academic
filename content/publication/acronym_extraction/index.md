---
title: 'Acronym Extraction with Hybrid Strategies'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Siheng Li
  - Cheng Yang
  - Tian Liang
  - admin
  - Chengze Yu
  - Yujiu Yang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
date: "2021-12-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *SDU Workshop at Association for the Advancement of Artificial Intelligence 2022*
publication_short: In SDU@AAAI 2022

abstract: 'Acronym extraction plays an important role in scientific document understanding. Recently, the AAAI-22 Workshop on Scientific Document Understanding released multiple highquality datasets and attracted widespread attention. In this work, we present our hybrid strategies with adversarial training for this task. Specifically, we first apply pre-trained models to obtain contextualized text encoding. Then, on the one hand, we employ a sequence labeling strategy with BiL-STM and CRF to tag each word in a sentence. On the other hand, we use a span selection strategy that directly predicts the acronym and long-form spans. In addition, we adopt adversarial training to further improve the robustness and generalization ability of our models. Experimental results show that both methods outperform strong baselines and rank high on the SDU@ AAAI-22-Shared Task 1: Acronym Extraction, our scores rank 2nd in 4 test sets and 3rd in 3 test sets. Moreover, the ablation study further verifies the effectiveness of each component. Our code is available at https://github.com/carlyoung1999/AAAI-SDU-Task1.'


tags: []

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://ix.cs.uoregon.edu/~apouranb/sdu22/SDUAAAI22_paper_15.pdf'

---
