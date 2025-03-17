---
layout: page
title: YouTube
permalink: /youtube/
description: Check out my YouTube playlist for more content.
---

<div class="youtube-container">
  <iframe src="https://www.youtube.com/embed/videoseries?list=PLexample" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
  </iframe>
</div>

<style>
.youtube-container {
  position: relative;
  width: 100%;
  padding-bottom: 56.25%; /* 16:9 aspect ratio */
  height: 0;
  overflow: hidden;
}

.youtube-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style> 