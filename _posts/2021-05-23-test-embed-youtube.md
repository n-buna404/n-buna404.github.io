---
layout: post
title: "embed youtube"
date: 2021-05-23
---

Test youtube embed.
<pre>
<div class="video-container">
  <iframe src="https://www.youtube.com/embed/MMhZNseGtAY?start=0" width="800" height="450" frameborder="0" allowfullscreen></iframe>
</div>
</pre>
<!-- <hr> space with underline <br> line break but jekyll stupid spacing is too large until resolved use pre tag to preserve the enter and use it for spacing;comment youtube iframe can start with in seconds 16:9 ratio got time learn about frameborder -->
<div class="flex"><label class="btn" for="show-vid">Show Video</label></div>  
<input id="show-vid" type="checkbox" />
<div id="overlay" for="show-vid">
  <div class="video-wrapper">
    <label class="close" for="show-vid">Hide Video</label>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/MMhZNseGtAY?start=0" frameborder="0" allowfullscreen></iframe>
  </div>
</div>
