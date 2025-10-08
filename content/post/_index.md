+++
draft = true
+++
title: "Posts"
url: /post/
_build:
  render: always
---
<script>
  window.location.href = "{{ (index (where .Site.RegularPages "Section" "post") 0).RelPermalink }}";
</script>
