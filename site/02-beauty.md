---
layout: post
title: Beauty
permalink: beauty
description: Samantha
image: assets/images/Beauty1.jpg
nav-menu: true
---

Outside of music, Menghe focus on skincare and cosmetics comparison and exploration and called Miss. Samantha as a beauty-blogger. 

除了音乐，井梦鹤同时致力于对护肤化妆的尝试和探索并在美妆领域称为美妆博主Samantha..

<section class="videos">
  {% for video in page.videos %}
    <div class="video">
      <h3>{{video.title}}</h3>
      <video src="/assets/videos/{{video.filename}}" controls></video>
    </div>
  {% endfor %}
</section>