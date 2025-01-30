---
name: "Bug Report"
about: "Report a bug to be fixed"
title: "[Bug]: "
labels: ["bug"]
assignees: []
body:
  - type: markdown
    attributes:
      value: |
        ## 🪳 Bug Report
        Thanks for taking the time to report a bug!  
        Please ensure you're running the **latest version** before submitting.  

  - type: input
    id: bug-title
    attributes:
      label: "Bug Title"
      description: "Provide a short and clear title for the bug."
      placeholder: "e.g. Crash when opening settings"
    validations:
      required: true

  - type: textarea
    id: steps-to-reproduce
    attributes:
      label: "Steps to Reproduce"
      description: "List the exact steps to recreate the bug."
      placeholder: |
        1. Run `...`
        2. Click `...`
        3. Observe the issue
    validations:
      required: true

  - type: textarea
    id: expected-behavior
    attributes:
      label: "Expected Behavior"
      description: "Describe what should have happened instead."
      placeholder: "e.g. The program should open the settings menu without crashing."
    validations:
      required: true

  - type: textarea
    id: actual-behavior
    attributes:
      label: "Actual Behavior"
      description: "Describe what actually happened."
      placeholder: "e.g. The program crashes immediately with error XYZ."
    validations:
      required: true

  - type: dropdown
    id: operating-system
    attributes:
      label: "Operating System"
      description: "Which OS are you using?"
      placeholder: "WindOS"
      options:
        - Windows 10
        - Windows 11
        - macOS
        - Linux (Ubuntu)
        - Linux (Other)
        - Other
    validations:
      required: true

  - type: input
    id: version
    attributes:
      label: "Software Version"
      description: "Which version of the program are you using?"
      placeholder: "e.g. v1.2.3"
    validations:
      required: true

  - type: textarea
    id: logs
    attributes:
      label: "Error Message or Logs"
      description: "Paste any error messages or logs related to the issue."
      placeholder: "e.g. Stack trace or console output"
      render: shell
    validations:
      required: false

  - type: textarea
    id: additional-context
    attributes:
      label: "Additional Context"
      description: "Any extra details or relevant information?"
      placeholder: "e.g. Any other observations about the bug?"
    validations:
      required: false

  - type: checkboxes
    id: latest-version-check
    attributes:
      label: "Latest Version Confirmation"
      description: "Please confirm that you've tested on the latest version."
      options:
        - label: "I have tested this on the latest version, and the bug still occurs."
          required: true

  - type: textarea
    id: screenshot
    attributes:
      label: "Screenshot (if applicable)"
      description: "Paste a link to a screenshot or attach it below."
      placeholder: "e.g. Drag and drop an image here"
    validations:
      required: false
