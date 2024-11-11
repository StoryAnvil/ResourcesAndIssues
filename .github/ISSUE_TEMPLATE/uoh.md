name: Universal Ore Highligher mod request
description: Requsest mod support for ore borders
title: "[RP-OH] <title here>"
labels: ["Type: enhancement", "Project type: Resource pack", "Project: OreBorders"]
body:
  - type: input
    id: modlink
    attributes:
      label: Link to requested mod
      placeholder: https://curseforge/minecraft/...
    validations:
      required: true
  - type: textarea
    id: additional
    attributes:
      label: Any other info?
      value: | 
        ...
    validations:
      required: true
  - type: checkboxes
    id: check
    attributes:
      label: Little checking
      options:
        - label: I checked [issues](https://github.com/StoryAnvil/ResourcesAndIssues/issues) for duplicates
          required: true
  - type: markdown
    attributes:
      value: |
        Thanks for requesting feature!
