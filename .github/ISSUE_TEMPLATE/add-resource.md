name: Add Resource
description: Propose a new resource for the SOC Knowledge Hub
labels: ["add-resource"]
body:
  - type: input
    id: title
    attributes:
      label: Title
      placeholder: "e.g., MITRE ATT&CK Roadmap"
    validations:
      required: true
  - type: dropdown
    id: category
    attributes:
      label: Category
      options:
        - Fundamentals
        - SOC Architecture
        - Detection Engineering
        - Threat Intelligence
        - Incident Response
        - SOAR and Automation
        - SOC Tools
        - SOC Management
        - Learning Path
        - Live Website Monitoring
    validations:
      required: true
  - type: input
    id: link
    attributes:
      label: Link
    validations:
      required: true
  - type: textarea
    id: summary
    attributes:
      label: Summary
      placeholder: "What is this and why is it useful for SOC?"
    validations:
      required: true
  - type: dropdown
    id: difficulty
    attributes:
      label: Difficulty
      options:
        - Beginner
        - Intermediate
        - Advanced
    validations:
      required: true
