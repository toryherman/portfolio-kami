---
layout: post
title: Dev Gadget
thumbnail-path: "img/devgadget.png"
short-description: Build a Chrome Extension.

---

{:.center}
![]({{ site.baseurl }}/img/icon128.png)

I&rsquo;ve recently begun working on my first open source project&mdash;a Chrome extension called Dev Gadget. The idea for Dev Gadget was an inspector-type tool that would allow web developers to quickly and easily copy CSS for any given element on a web page. You can already do this with your inspector tools, but the process is somewhat cumbersome. I was hoping to create something that was a much more seamless process. Hover, click, done.

As of this posting, the current iteration of Dev Gadget allows you to hover over HTML elements, displaying the tag, font family, font size, and text color of that element in a frame at the top of the window. A click on that element copies those styles to your clipboard. The scope is a bit limited with just showing those three styles, but I intend to add more functionality soon&mdash;such as the ability to select which styles you would like to copy. Being that this is intended to be an open source project, I am hoping other developers can bring more ideas to the table, so we can hone in what features are most useful to web designers and developers.

{:.center}
![]({{ site.baseurl }}/img/devgadget.png)

The process of developing this extension has gone relatively smoothly thus far. It was a little slow at the beginning getting acquainted with the architecture of Chrome extensions, but I found many other repos on Github that helped me smooth everything out. I&rsquo;m hoping this project has some legs and can really become something useful to more people than just me!

**[Github repo](https://github.com/toryherman/dev-gadget)**
