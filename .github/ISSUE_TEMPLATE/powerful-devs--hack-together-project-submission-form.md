---
name: 'Powerful Devs: Hack Together Project Submission Form'
about: Share your project with us to get a digital badge and win prizes
title: ''
labels: ''
assignees: ''

---

title: "Project: <short description>"
body:
  - type: input
    id: name
    attributes:
      label: Project Name
      description: Name of your project
    validations:
      required: true
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Provide a short description of your solution. What data sources did you use? How would this solution scale? How does this solution ensure security best practices? How is this solution AI powered?
    validations:
      required: true
  - type: checkboxes
    attributes:
      label: Technology & Languages
      description: Check any technologies or languages used for your solution.
      options:
        - label: Integrations with tools outside of the Power Platform (M365, Connectors)? 
          required: false
        - label: Power Automate
          required: false  
        - label: Power Apps
          required: false 
        - label: Copilot Studio
          required: false
        - label: Power Pages
          required: false
        - label: AI (AI Builder, Copilot, Azure AI, etc)
          required: false
  - type: input
    id: url_repo
    attributes:
      label: Project Repository URL
      description: URL of the GitHub repo with your project
    validations:
      required: true
  - type: input
    id: video
    attributes:
      label: Project Video
      description: A short demo video of your project
    validations:
      required: true
  - type: input
    id: teammembers
    attributes:
      label: Team Members
      description: Comma-separated list of GitHub users who worked on this project
    validations:
      required: true