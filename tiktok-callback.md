---
title: TikTok connected
---

# Benz Signals Uploader

Copy the code below and paste it on the Raspberry Pi when the setup asks for it. It works only once and for a few minutes.

<p><b>Code:</b> <code id="c">(none)</code></p>

<script>
var p = new URLSearchParams(location.search);
document.getElementById('c').textContent = p.get('code') || ('error: ' + (p.get('error_description') || p.get('error') || 'no code'));
</script>
