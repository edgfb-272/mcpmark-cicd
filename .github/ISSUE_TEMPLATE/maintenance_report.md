---
name: Maintenance Report
description: Report a maintenance or housekeeping task for the mcpmark-cicd project
labels: maintenance
body:
  - type: textarea
    id: description
    attributes:
      label: Maintenance Description
      description: A clear and concise description of the maintenance task.
      placeholder: Describe the maintenance task here.
    validations:
      required: true
  - type: textarea
    id: impact
    attributes:
      label: Impact
      description: Explain the impact of this maintenance task on the project.
      placeholder: Describe the impact of this maintenance task.
    validations:
      required: true
  - type: textarea
    id: timeline
    attributes:
      label: Timeline
      description: Suggested timeline for completing this maintenance task.
      placeholder: Suggest a timeline for this maintenance task.
    validations:
      required: true
  - type: textarea
    id: additional-context
    attributes:
      label: Additional Context
      description: Add any other context or details related to this maintenance task.
      placeholder: Add additional context here.
