---
title: "424: File List Optimization"
url: "https://blog.codepen.io/2026/04/29/424-file-list-optimization/"
date: "2026-04-29"
author: "Chris Coyier"
feed_url: "https://blog.codepen.io/feed/"
---
The 2.0 Editor can support hundreds of files per Pen, not to mention folders mixed in which don’t count toward that total. This can be pretty weighty on the DOM and thus adversely affect performance. Especially as each file/folder has children, a variety of event listeners, are drag and drop enabled, etc.
