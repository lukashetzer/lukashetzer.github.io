---
title: Publications
type: landing

sections:
  # # Featured (same as homepage)
  # - block: collection
  #   id: featured-publications
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2


  # Journal Articles
  - block: collection
    id: journal-articles
    content:
      title: Journal Articles
      filters:
        folders:
          - publications
        publication_type: "article-journal"
    design:
      view: citation

  # Book Chapters
  - block: collection
    id: book-chapters
    content:
      title: Book Chapters
      filters:
        folders:
          - publications
        publication_type: "book chapter"
    design:
      view: citation

  # Edited Volumes
  - block: collection
    id: edited-volumes
    content:
      title: Edited Volumes
      filters:
        folders:
          - publications
        publication_type: "edited volume"
    design:
      view: citation

  # Edited Volume Contributions
  - block: collection
    id: edited-volumes-contrib
    content:
      title: Contributions to Edited Volumes
      filters:
        folders:
          - publications
        publication_type: "edited volume contribution"
    design:
      view: citation

  # Policy Reports (if you also use report for working papers, see note below)
  - block: collection
    id: policy-reports
    content:
      title: Policy Reports
      filters:
        folders:
          - publications
        publication_type: report
    design:
      view: citation
---
