---
layout: demo
title: "Tray/box configurator"
name: "bestekbak config"
order: 11
descr: "grid-based configure with 3d preview"
img: "/assets/projs/bestekbak_thumb.png"
---

The grid structure is utilised to build a configurator for cutlery trays, but can also be applied to closets, drawers, and the likes!

The app has reached a functional state, but development is halted until we have further plans for our wood workshop.

<p class="demo_link"><a href="https://bestekbak-config.netlify.app/" target="_blank">pay a visit</a></p>

![](/assets/proj_scr/bestekbak2.png)


In short, users can customise their desired tray by its size, depth, wood thickness, column/row layout and sizes. A demo can be rendered to preview the configured set up.


![](/assets/proj_scr/bestekbak.png)

### info

- vue app deployed with netlify
- add/remove cols/rows by side bar
- change cols/rows size by number or dragging
- press and drag to define sections
- click x to remove sections
- overlapping sections are obviously forbidden
- click preview to show how it would look like
- fr(ame) = equal division, click to change to cm
- 3d model generated using troisjs
- based on [cssgrid-generator](https://cssgrid-generator.netlify.app/)

