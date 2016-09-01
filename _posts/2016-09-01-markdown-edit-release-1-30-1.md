---
layout: post  
title:  Markdown Edit Release 1.30.1  
...

Bug Fixes:

-   Fix "Auto-sync of edit and preview panes fails for block quotes in
    lists" #176

Enhancements:

-   Changed `CustomMarkdownEngine` setting to accept only a file name.
-   Added `CustomMarkdownEngineArgs` for additional arguments to pass to
    `CustomMarkdownEngine`.

![tuning forks](http://i.imgur.com/MigtPB3.png)

Scroll synchronization continues to improve. There's no direct way at
present to know what bit of Markdown generates what bit of HTML. The
current method is essentially a block counting algorithm with special
case handling. Scroll synchronization can still be fooled by large
blocks of embedded HTML, although most of the time it gets things right.

I separated the arguments from the file name to deal with long file
names. While it's possible to parse these things, there seems to always
be breaking edge cases. Better to be conservative and just keep the
items separate.

I'm slowly plowing through the backlog of issues. Don't be afraid to
nudge me if you don't see movement on your issue.
