name: Bug Report
description: Create a detailed bug report to help improve system reliability and quality
title: "[BUG] "
labels: ["bug"]
assignees: []
body:
  - type: markdown
    attributes:
      value: "## Bug Severity"

  - type: checkboxes
    attributes:
      label: Select the severity level based on system impact
      options:
        - label: Critical - System downtime or data loss, affecting uptime SLA
        - label: High - Major functionality broken, significant performance impact
        - label: Medium - Feature partially broken, moderate impact
        - label: Low - Minor issues, minimal impact

  - type: checkboxes
    attributes:
      label: Bug Type
      options:
        - label: Functional - Core feature malfunction
        - label: Performance - System speed or resource usage
        - label: Security - Vulnerability or security concern
        - label: UI/UX - Interface or usability issue
        - label: Data - Data processing or integrity
        - label: Integration - System integration failure

  - type: textarea
    attributes:
      label: Issue Summary
      description: Provide a clear and concise description of the bug

  - type: textarea
    attributes:
      label: Business Impact
      description: Describe the impact on business operations including affected user groups, system components, uptime impact, and data impact

  - type: textarea
    attributes:
      label: Steps to Reproduce
      description: Provide detailed step-by-step instructions including test data requirements and required permissions

  - type: textarea
    attributes:
      label: Expected Behavior
      description: Describe what should happen including expected outcome and business rules

  - type: textarea
    attributes:
      label: Current Behavior
      description: Describe what actually happens including error messages and system response

  - type: dropdown
    attributes:
      label: Environment Type
      options:
        - Production
        - Staging
        - Development

  - type: input
    attributes:
      label: Application Version

  - type: textarea
    attributes:
      label: Logs and Screenshots
      description: Attach relevant logs, stack traces, and visual evidence

  - type: textarea
    attributes:
      label: Additional Context
      description: Include any related issues, known workarounds, or time sensitivity information