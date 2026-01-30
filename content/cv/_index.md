---
title: CV
type: landing

sections:
  # Clean header + download button (no avatar, no social icons)
  - block: markdown
    content:
      title: "Curriculum Vitae"
      text: |
        <a class="btn btn-primary" href="/uploads/resume.pdf" target="_blank" rel="noopener">
          Download full CV here (pdf)
        </a>
    design:
      columns: "1"

#   # Experience
#   - block: resume-experience
#     content:
#       username: me
#       title: Experience

  # Education (same block, just with a separate profile – see Option B below)
  - block: resume-experience
    content:
      username: cv
      title: Education

  # Awards before skills
  - block: resume-awards
    content:
      username: me
      title: Awards & Grants

  - block: resume-skills
    content:
      username: me
      title: Skills
---
