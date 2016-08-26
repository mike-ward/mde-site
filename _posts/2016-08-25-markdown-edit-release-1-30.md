---
layout: post  
title:  Markdown Edit Release 1.30  
...
<!-- MDE -->
Enhancements:

-   Add list indent on tab
    [\#170](https://github.com/mike-ward/Markdown-Edit/issues/170)
-   Allow per monitor dpi
-   Make style sheet less GitHub like
-   Add multicore-jit startup code
-   Enable newer common control styles
-   Separate commands from code behind
-   Update packages

![Chuck Norris meme](http://i.imgur.com/fMME81D.png)

Bug Fixes:

-   Navigate to named anchors in same document
    [\#171](https://github.com/mike-ward/Markdown-Edit/issues/171)
-   Only add to list items if it's increasing line count
    [\#172](https://github.com/mike-ward/Markdown-Edit/issues/172)
-   Check if previous/previous line in list
    [\#173](https://github.com/mike-ward/Markdown-Edit/issues/173)
-   Fix redraw issues
-   Fix index out of range when only front matter present
-   Fix clipboard to Data Uri

Much of the work in this release was restructuring the code. Someone
took me to task for wiring up my command elements in code behind. A
technical issue that doesn't make the program work better but it does
make it easier to maintain and enhance.

The “Per Monitor DPI” enhancement is only available if you upgrade you
.NET framework to 4.6. Get it at <http://smallestdotnet.com>.

The default style sheet was too much like GitHub. While this works for
us nerds, it is perhaps a bit too nerdy looking for other purposes. This
update will not replace your current style sheet. New installations will
get the newer style sheet.

The dialogs used for opening and saving files and displaying message
boxes have been updated to use the newer system styles in Windows 10.

Multicore-jit is one of those geeky little tweaks that allows the
program to startup faster. Don't know if I can see the difference but it
was easy to add so why not.

There were a number of bug fixes and enhancements around the editing of
lists. Small enhancements like these give the program refined feel.
Thanks for the suggestions.
