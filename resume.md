<button id="theme-toggle" aria-label="Toggle light/dark mode">
  ☀️ / 🌙
</button>

<script>
  const btn = document.getElementById('theme-toggle');

  btn.addEventListener('click', () => {
    document.documentElement.classList.toggle('dark-mode');
  });
</script>

---
layout: page
title: Resume
---

<div style="width:100%; height:90vh;">
  <iframe
    src="/assets/Vignesh_AK_Resume.pdf#toolbar=0&navpanes=0&scrollbar=0"
    width="100%"
    height="100%"
    style="border:none;">
  </iframe>
</div>
