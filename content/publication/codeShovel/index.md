---
title: "CodeShovel: Constructing Method-Level Source Code Histories"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Felix Grund
- Shaiful Chowdhury
- admin
- Braxton Hall
- Reid Holmes


date: "2021-05-07T00:00:00Z"
doi: "10.1109/ICSE43902.2021.00135"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Software Engineering (ICSE)*, IEEE.
publication_short: In *ICSE*

abstract: Source code histories are commonly used by developers and researchers to reason about how software evolves. Through a survey with 42 professional software developers, we learned that developers face significant mismatches between the output provided by developers' existing tools for examining source code histories and what they need to successfully complete their historical analysis tasks. To address these shortcomings, we propose CodeShovel, a tool for uncovering method histories that quickly produces complete and accurate change histories for 90% methods (including 97% of all method changes) outperforming leading tools from both research (e.g, FinerGit) and practice (e.g., IntelliJ / git log). CodeShovel helps developers to navigate the entire history of source code methods so they can better understand how the method evolved. A field study on industrial code bases with 16 industrial developers confirmed our empirical findings of CodeShovel's correctness, low runtime overheads, and additionally showed that the approach can be useful for a wide range of industrial development tasks. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
links:
- name: Demo
  url: https://se.cs.ubc.ca/CodeShovel

url_pdf: 'icse21_grund.pdf'
url_code: 'https://github.com/ataraxie/codeshovel'
url_dataset: 'https://zenodo.org/record/4543820'
url_poster: ''
url_project: 'https://doi.org/10.1109/ICSE-Companion52605.2021.00100'
url_slides: 'https://docs.google.com/presentation/d/1sez4o1KC41j1Z1D4dq7LojDxnGn5peboH-qjWUTykVQ/edit?usp=sharing'
url_source: ''
url_video: 'https://youtu.be/EFwybMlaRfU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "CodeShovel's web interface showing the complete history of a method."
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

