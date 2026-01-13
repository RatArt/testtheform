name: Bug report
description: Create a report to help us improve
title: "[Bug]: "
labels: ["bug"]
body:
  - type: input
    id: sandbox_id
    attributes:
      label: Sandbox ID or Build ID
      description: Output of `sbx.sandbox_id` or the build ID printed in the console during the build
      placeholder: e.g. sbx_123456
    validations:
      required: true

  - type: input
    id: sdk_version
    attributes:
      label: SDK version
      description: Output of `pip list` or `npm list` (or at least the e2b package version)
      placeholder: e.g. e2b==1.2.3
    validations:
      required: true

  - type: input
    id: timestamp
    attributes:
      label: Timestamp of the issue
      description: When did the error occur? (include timezone if possible)
      placeholder: e.g. 2026-01-12 14:32 UTC
    validations:
      required: true

  - type: input
    id: start_time
    attributes:
      label: When did this start happening?
      placeholder: e.g. Today / Yesterday / After upgrading SDK

  - type: dropdown
    id: frequency
    attributes:
      label: Frequency
      options:
        - One-time occurrence
        - Happens intermittently
        - Happens every time
    validations:
      required: true

  - type: input
    id: os
    attributes:
      label: Operating system
      description: OS used to run your code (not the sandbox OS)
      placeholder: e.g. macOS 14, Ubuntu 22.04, Windows 11
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: Bug description
      description: A clear and concise description of the bug
    validations:
      required: true

  - type: textarea
    id: reproduce
    attributes:
      label: Steps to reproduce
      description: Step-by-step instructions to reproduce the issue
      placeholder: |
        1. Go to '...'
        2. Run '...'
        3. See error
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: Expected behavior
      description: What did you expect to happen?
    validations:
      required: true

  - type: textarea
    id: actual
    attributes:
      label: Actual behavior
      description: What actually happened?

  - type: textarea
    id: additional
    attributes:
      label: Additional context
      description: Logs, screenshots, error messages, or any other relevant details
