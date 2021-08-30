---
name: Software submission
description: Submit software for review
title: "[Submission]: <package name>"
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
  - type: input
    id: other-authors
    attributes:
      label: Other Package Authors
      descriptions: Delete if not, otherwise please do not delete the HTML comments
      placeholder: <!--author-others-->Name (@github_handle)<!--end-author-others-->
      value: "<!--author-others-->Name (@github_handle)<!--end-author-others-->"
labels: ''
assignees: ''

---


