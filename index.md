---
layout: default
title: Unsafe Input Demo
---

# 🧪 Unsafe Input Simulation

This page simulates unsafe handling of user input for demonstrating a code review scenario.

Below is an example where user input is directly injected into the page without any sanitization:

```html
<!-- Example of unsafe input usage -->
<script>
  const userInput = location.search;
  document.body.innerHTML = "User said: " + userInput;
</script>
