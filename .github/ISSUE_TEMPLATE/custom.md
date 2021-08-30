---
name: Software submission
about: Submit software for review
title: "[Submission]:"
body:
  - type: markdown
    attributes:
      value: |
        Thanks for submitting your software to rOpenSci
  - type: input
    id: submitting-author
    attributes:
      label: Submitting Author
      description: Please do not delete the HTML comments.
      placeholder: <!--author1-->Name (@github_handle)<!--end-author1-->
      value: "<!--author1-->Name (@github_handle)<!--end-author1-->"
    validations:
      required: true
---

Some text here


