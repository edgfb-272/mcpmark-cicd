---
name: Feature Request
description: Suggest an idea for the mcpmark-cicd project
labels: enhancement
body:
  - type: textarea
    id: description
    attributes:
      label: Feature Description
      description: A clear and concise description of the feature you'd like to see.
      placeholder: Describe the feature here.
    validations:
      required: true
  - type: textarea
    id: use-case
    attributes:
      label: Use Case
      description: Explain how this feature would benefit the project and its users.
      placeholder: Describe the use case for this feature.
    validations:
      required: true
  - type: textarea
    id: alternatives
    attributes:
      label: Alternatives Considered
      description: A clear and concise description of alternative solutions or features you've considered.
      placeholder: Describe alternative solutions.
    validations:
      required: true
  - type: textarea
    id: additional-context
    attributes:
      label: Additional Context
      description: Add any other context or screenshots related to the feature request.
      placeholder: Add additional context here.
