---
name: New Cake request
about: You can request for cakes here.
title: "[Cake Request]"
labels: cake-request
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: input
    id: language-and-framework
    attributes:
        label: Which language/Framework
        description: Which language/framework is this cake based on?
        placeholder: ex. Python - Flask or Javascript - React
    validations:
      required: true
---


