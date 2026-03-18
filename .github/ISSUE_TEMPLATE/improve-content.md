name: Improve Content
description: Suggest improvements to an existing documentation page
labels: ["documentation"]
body:
  - type: input
    id: page
    attributes:
      label: Page to improve
      placeholder: "e.g., docs/fundamentals/soc-basics.md"
    validations:
      required: true
  - type: textarea
    id: suggestions
    attributes:
      label: Suggestions
      placeholder: "What should be changed or added?"
    validations:
      required: true
