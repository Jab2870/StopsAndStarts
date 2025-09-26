---
name: Submit Location
about: Submit a new location
title: "[new location] - "
labels: new location
assignees: Jab2870
body:
  - type: input
    id: country
    attributes:
      label: country
      description: 2 letter country code
      placeholder: ex. uk
    validations:
      required: true
  - type: input
    id: county
    attributes:
      label: county
      description: county
      placeholder: ex. Suffolk
    validations:
      required: true
  - type: input
    id: lat
    attributes:
      label: Latitude
      description: Latitude
    validations:
      required: true
  - type: input
    id: long
    attributes:
      label: Longitude
      description: Longitude
    validations:
      required: true
  - type: checkboxes
    id: facilities
    attributes:
      label: Facilities
      description: Facilities
      options:
        - label: Toilets
        - label: Showers
        - label: Water Filling
        - label: Grey Water Disposal
        - label: Toilet Disposal
        - label: Electricity
        - label: Laundry
        - label: WiFi
        - label: LPG
  - type: textarea
    id: description
    attributes:
      label: Description
    validations:
      required: true
---


