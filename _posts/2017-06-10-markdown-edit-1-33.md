---
layout: post  
title: "Markdown Edit 1.33"  
...

![welcome back with dog](http://ak.imgfarm.com/images/fwp/myfuncards/Everyday/lg/WelcomeBackPooch.jpg)

Yeah, it's been a while since I've updated things. Too many distractions
I guess. Consider this release the beginning of a new round of
development. There are a number of issues open that I'll start plowing
through.

This release will require .NET 4.7. Why you ask? Because 4.7 has a
number of enhancements for high DPI screens that WPF apps get
automatically. I get the occasional report about things not looking
right on high DPI screens. I don't have one of those screens which makes
it difficult to address. Let me know if it works.

I've also taken the opportunity to fix some crash reports and update
packages.

-   VS like selection style for editor
-   update packages, remove browser unload code, move to vs2017
-   move to .net 4.7, update get/setter styles
-   fix out of range crash
-   fix file in use crash
-   fix some other crash reports
-   add GitHub's cmark for for future consideration
-   update pandoc, mess around with *cmark-gfm*

I've built and included *cmark-gfm* in this release. It's not used in
the program although your welcome to mess around with it using the
custom engine option in MDE.
