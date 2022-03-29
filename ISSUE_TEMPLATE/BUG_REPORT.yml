name: Bug Report
description: File a bug report
title: "[Bug]: "
labels: ["bug"]
assignees:
  - userjack6880
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Also tell us, what did you expect to happen?
      placeholder: Tell us what you see!
      value: "A bug happened!"
    validations:
      required: true
  - type: dropdown
    id: version
    attributes:
      label: Version
      description: What version of our software are you running?
      options:
        - Version 0 Alpha 8.1 (Dev)
        - Version 0 Alpha 8 (Main)
        - Other (Include in Description)
    validations:
      required: true
  - type: input
    id: browser
    attributes:
      label: What browsers are you seeing the problem on?
  - type: input
    id: client-os
    attributes:
      label: What OS(es) are your client systems running, including version?
  - type: input
    id: server-os
    attributes:
      label: What OS is your server system running, including version?
      required: true
  - type: input
    id: webserver
    attribute:
      label: What Web Server are you using?
      required: true
  - type: input
    id: php-version
    attribute:
      label: What version of PHP are you using?
      required: true
  - type: input
    id: sql
    attribute:
      label: What SQL Server are you using?
      required: true
  - type: textarea
    id: logs
    attributes:
      label: Relevant log output
      description: Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.
      render: shell
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow the [Code of Conduct](https://github.com/userjack6880/Open-DMARC-Analyzer/blob/main/docs/CODE_OF_CONDUCT.md)
      options:
        - label: I agree to follow the Code of Conduct
          required: true
