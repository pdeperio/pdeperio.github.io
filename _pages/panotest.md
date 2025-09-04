---
title: "Pano Test"
layout: single
permalink: /panotest/
---

<!-- A-Frame -->
<script src="https://aframe.io/releases/1.5.0/aframe.min.js"></script>

<div style="max-width:100%;border:1px solid #eee">
  <a-scene embedded renderer="antialias: true" style="width:100%;height:60vh">
    <a-assets>
      <img id="pano" src="/assets/IMG_20250904_174621_00_114.jpg">
    </a-assets>
    <a-sky src="#pano" rotation="0 -90 0"></a-sky>
    <a-entity camera look-controls wasd-controls></a-entity>
  </a-scene>
</div>

<p>If you still see a flat image above, something else is intercepting rendering.</p>
