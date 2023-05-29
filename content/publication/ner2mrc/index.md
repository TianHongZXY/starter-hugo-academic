---
title: 'NER-to-MRC: Named-Entity Recognition Completely Solving as Machine Reading Comprehension'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yuxiang Zhang
  - Junjie Wang
  - admin
  - Tetsuya Sakai
  - Hayato Yamana

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
date: "2023-05-06T00:01:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "PrePrint"
# publication: In *The 2022 Conference on Empirical Methods in Natural Language Processing*
# publication_short: In ACL2023

abstract: "Named-entity recognition (NER) detects texts with predefined semantic labels and is an essential building block for natural language processing (NLP). Notably, recent NER research focuses on utilizing massive extra data, including pre-training corpora and incorporating search engines. However, these methods suffer from high costs associated with data collection and pre-training, and additional training process of the retrieved data from search engines. To address the above challenges, we completely frame NER as a machine reading comprehension (MRC) problem, called NER-to-MRC, by leveraging MRC with its ability to exploit existing data efficiently. Several prior works have been dedicated to employing MRC-based solutions for tackling the NER problem, several challenges persist: i) the reliance on manually designed prompts; ii) the limited MRC approaches to data reconstruction, which fails to achieve performance on par with methods utilizing extensive additional data. Thus, our NER-to-MRC conversion consists of two components: i) transform the NER task into a form suitable for the model to solve with MRC in a efficient manner; ii) apply the MRC reasoning strategy to the model. We experiment on 6 benchmark datasets from three domains and achieve state-of-the-art performance without external data, up to 11.24% improvement on the WNUT-16 dataset."

tags: []

# Display this page in the Featured widget?
featured: false

url_pdf: 'https://arxiv.org/abs/2305.03970'

---
