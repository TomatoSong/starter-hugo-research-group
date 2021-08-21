---
advanced:
  ? css_style
  ? css_class
widget: hero
widget_id: RECENT-POSTS
headless: true
weight: 10
title: Medical Guidance Systems Group
subtitle: ""
design:
  columns: "1"
  background:
    image: ""
hero_media: welcome.jpg
---
<style>
.button {
  display: inline-block;
  border-radius: 4px;
  background-color: #f4511e;
  border: none;
  color: #FFFFFF;
  text-align: center;
  font-size: 28px;
  padding: 20px;
  width: 320px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}
</style>

<button class="button" style="vertical-align:middle"><a href="/courses" style="color:#bbdefb">View our Projects</a></button>
<br />
<button class="button" style="vertical-align:middle"><a href="/demo" style="color:#bbdefb">Watch our Demos</a></button>
<br />
<button class="button" style="vertical-align:middle"><a href="/publication" style="color:#bbdefb">Cite our Publications</a></button>
