name: 🚀 Pull Request
description: Propose changes to OpenIPTVItaly
title: "[PR] "
labels: ["pull-request"]

body:
  - type: textarea
    id: summary
    attributes:
      label: Summary
      description: Describe clearly what this PR does
      placeholder: |
        Example:
        - Added a new free-to-air TV channel
        - Fixed a broken stream URL
        - Updated metadata or logos
    validations:
      required: true

  - type: dropdown
    id: pr_type
    attributes:
      label: Type of change
      description: Select the main purpose of this pull request
      options:
        - Playlist update (channels / streams)
        - Metadata or logos improvement
        - Bug fix
        - Documentation
        - Other
    validations:
      required: true

  - type: textarea
    id: source
    attributes:
      label: Source / Reference (if applicable)
      description: Official website or public source of the stream or information
      placeholder: https://example.com/live

  - type: checkboxes
    id: checklist
    attributes:
      label: Checklist
      description: Please confirm the following
      options:
        - label: The content is **free-to-air and legally accessible**
          required: true
        - label: No pay-TV, DRM-protected or pirated streams are included
          required: true
        - label: I tested the stream / playlist where applicable
          required: true
        - label: I read and followed CONTRIBUTING.md
          required: true
