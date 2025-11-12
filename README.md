---
layout: default
permalink: /
home: True
---

<script>
  const userLang = navigator.language || navigator.userLanguage;
  if (userLang.startsWith('es')) {
    window.location.href = '/es/';
  } else if (userLang.startsWith('fr')) {
    window.location.href = '/fr/';
  } else {
    window.location.href = '/en/';
  }
</script>