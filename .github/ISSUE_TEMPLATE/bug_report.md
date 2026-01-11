---
name: Bug Report
description: Report a bug in the mcpmark-cicd project
labels: bug
body:
  - type: textarea
    id: description
    attributes:
      label: Description
      description: A clear and concise description of what the bug is.
      placeholder: Describe the bug here.
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      description: Steps to reproduce the behavior.
      placeholder: |
        1. Go to '...'
        2. Click on '....'
        3. Scroll down to '....'
        4. See error
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
      description: A clear and concise description of what you expected to happen.
      placeholder: Describe what you expected to happen.
    validations:
      required: true
  - type: textarea
    id: actual
    attributes:
      label: Actual Behavior
      description: A clear and concise description of what actually happened.
      placeholder: Describe what actually happened.
    validations:
      required: true
  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots
      description: Add screenshots to help explain your problem.
      placeholder: Drag and drop screenshots here.
  - type: textarea
    id: environment
    attributes:
      label: Environment
      description: Details about your environment.
      placeholder: |
        - Browser: [e.g., Chrome 89.0.4389.82]
        - Node.js Version: [e.g., 16.0.0]
        - Operating System: [e.g., Windows 10]
    validations:
      required: true
