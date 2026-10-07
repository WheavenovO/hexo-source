---
title: 音乐库
date: 2026-10-04 19:36:02
type: music
---

{% raw %}
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aplayer@1.10.1/dist/APlayer.min.css">
<div id="aplayer"></div>
<script src="https://cdn.jsdelivr.net/npm/aplayer@1.10.1/dist/APlayer.min.js"></script>
<script>
const ap = new APlayer({
  container: document.getElementById('aplayer'),
  listFolded: false,
  audio: [
    {
      name: 'China-X',
      artist: '徐梦圆',
      url: 'https://files.catbox.moe/01n425.mp3',
      cover: 'https://p3-hippo-sign.byteimg.com/tos-cn-i-a9rns2rl98/44100400119344389d04211402043101~tplv-a9rns2rl98-image.image'
    },
    {
      name: 'China-Y',
      artist: '徐梦圆',
      url: 'https://files.catbox.moe/01n425.mp3',
      cover: 'https://p3-hippo-sign.byteimg.com/tos-cn-i-a9rns2rl98/44100400119344389d04211402043101~tplv-a9rns2rl98-image.image'
    }
  ]
})
</script>
{% endraw %}
