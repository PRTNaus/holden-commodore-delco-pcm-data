name: Reference Request
description: Submit a source reference for priority addition to the knowledge base.
title: "[REFERENCE]"
labels: ["reference"]
body:
  - type: markdown
    attributes:
      value: |
        Priority reference submissions are added to the knowledge base as soon as possible, no questions asked. If the source checks out it will be added, and if it already exists in the pending database it will be pulled forward for immediate inclusion.

  - type: textarea
    id: location
    attributes:
      label: Knowledge Base Location
      description: Identified by the section heading or content subheading. A screenshot is also fine.
    validations:
      required: true

  - type: input
    id: author
    attributes:
      label: Original Contributor
      description: Name or username of the original author. Include a profile link if known.
    validations:
      required: true

  - type: input
    id: platform
    attributes:
      label: Platform
      description: Website or forum the source is hosted on.
      placeholder: e.g. PCMHacking.net
    validations:
      required: true

  - type: input
    id: date
    attributes:
      label: Post Date
      placeholder: DD/MM/YYYY
    validations:
      required: false

  - type: input
    id: link
    attributes:
      label: Direct Link
      placeholder: https://
    validations:
      required: true

  - type: textarea
    id: notes
    attributes:
      label: Notes
      description: Brief description of what the source covers and why it's relevant.
    validations:
      required: false
