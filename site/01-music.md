---
layout: page
title: Music
permalink: music
description: Menghe Jing/井梦鹤
image: assets/images/yinfu.jpg
nav-menu: true
media:
- title: Rock Show cover Halestorm
  type: video # audio or video
  filename: rock show.mp4
  
- title: 停格 cover 蔡健雅
  type: audio # audio or video
  filename: tingge.mp3
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Music</h1>
		</header>

<!-- Content -->

<section class="media">
  {% for item in page.media %}
    <div class="media-item">
      <h3>{{item.title}}</h3>
      {% if item.type == "video" %}
      <video src="/assets/videos/{{item.filename}}" controls></video>
      {% elsif item.type == "audio" %}
      <audio src="/assets/audio/{{item.filename}}" controls></audio>
      {% endif %}
    </div>
  {% endfor %}
</section>

</div>

</section>

</div>
