name: Fix Broken Link
description: Report a broken or incorrectly formatted link
labels: ["broken-link"]
body:
  - type: input
    id: url
    attributes:
      label: Broken URL
    validations:
      required: true
  - type: input
    id: replacement
    attributes:
      label: Suggested Replacement (optional)
  - type: textarea
    id: context
    attributes:
      label: Context
      placeholder: "Where did you find this link?"
