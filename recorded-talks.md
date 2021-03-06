---
layout: page
order: 3
title: "Recorded Talks"
titleDisplay: "Recorded Talks"
redirect_from:
  - "/2018/conference/recorded-talks"
  - "/conference/recorded-talks"
---

## Our Networks 2018 Archive

Full archives of 2018 videos are available:

- IPFS: [ipfs://QmQQfD1ztg1aG82VmUmutusbxn7tL4c2o1qHv1ivyWbNj6](https://ipfs.io/ipfs/QmQQfD1ztg1aG82VmUmutusbxn7tL4c2o1qHv1ivyWbNj6/)
- Internet Archive: [Our Networks 2018 Talks](https://archive.org/details/ournetworks2018) (torrent available)
- YouTube playlist: [Our Networks 2018 Beyond DIY: Do It With Others](https://www.youtube.com/playlist?list=PLx7_J32Ys60ey2bgSn2soAoBy0v9bBUbT)

 We want to thank our A/V volunteers again, without whom the sharing of these videos would have been impossible: [Yurko](https://github.com/darkdrgn2k), [Henry Wilkinson](https://github.com/Shrinks99), [Elon Li](https://github.com/ASoTNetworks), and [Benedict Lau](https://github.com/benhylau).

## Our Networks 2018 Videos
{:.program-heading}

{% assign sortedSessions = site.data.sessions | sort: 'title' %}

<div class="row video-grid">
{%- for session in sortedSessions -%}
  {%- if session.ipfs720 or session.ipfs1080 or session.youtube -%}
    {% include session-video.html %}
  {%- endif -%}
{%- endfor -%}
</div>
