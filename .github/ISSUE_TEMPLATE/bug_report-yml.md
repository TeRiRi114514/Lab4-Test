---
name: bug_report.yml
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

name: Bug Report Form
description: File a bug report using interactive form
title: "[Bug]: "
labels: ["bug"]
assignees:
  - TeRiRi114514
body:
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: A clear and concise description of what the bug is.
      placeholder: Tell us what you see!
    validations:
      required: true
  - type: textarea
    id: reproduction
    attributes:
      label: Steps to reproduce
      description: How can we reproduce the issue?
      placeholder: |
        1. Go to '...'
        2. Click on '...'
        3. Scroll down to '...'
        4. See error
    validations:
      required: false
  - type: input
    id: os
    attributes:
      label: Operating system
      placeholder: e.g. Windows 11, macOS Ventura
    validations:
      required: false
  - type: input
    id: browser
    attributes:
      label: Browser
      placeholder: e.g. Chrome 120, Safari 17
    validations:
      required: false
