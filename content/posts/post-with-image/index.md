---
title: "Post With Image"
date: 2020-11-27T09:01:53-07:00
draft: true
summary: <img src='../content/posts/post-with-image/images/testimage.png'> overwritten by <!--more--> in the body
featured_image: "images/testimage.png"
authors: 
  - colinbledsoe
resources:
  - name: testimage
    src: "images/testimage.png"
    title: This is a test image
    params:
      credits: "[David Pennington](https://unsplash.com/@dtpennington) on [Unsplash](https://unsplash.com/s/photos/test)"
---
{{< img name="testimage" size="small">}}
<!--more-->
hihi
![testimage](images/testimage.png)
![family](../about-me/images/family.jpg)

<div class="flex justify-center">
<figure class="gblog-post__figure">
    <video
            src="images/Thermo_MP4.mp4" alt="Test this?" controls="controls">
    </video>
    <figcaption>An all too familiar sequence of events.</figcaption>
</figure>
</div>
Shortcode notation, see layouts>shortcodes>img 
Inside of that shortcode html file we have div classes that specify center justification and grey background
I think that re-scaling the .png is causing the change in quality


was  size="tiny">}}