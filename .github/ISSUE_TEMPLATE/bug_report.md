---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

**Describe the bug**
A clear and concise description of what the bug is.

**Complete EspHome project config**

```yaml
# Add EspHome project config
external_components:
  - source: github://soldierkam/vl53l1x_sensor

esp32:
  board: esp32dev
  framework:
    type: arduino 

...

```

**To Reproduce**
Steps to reproduce the behavior:
1. Compile project '...'
2. Wait n minutes '....'
3. See error in log: "..."

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

Add any other context about the problem here.
