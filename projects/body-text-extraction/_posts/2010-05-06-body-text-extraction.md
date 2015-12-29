---
title: Body Text Extraction
author: bill
layout: post
redirect_from:
  - /index.php/projectslink/38-past-projects/67-body-text-extraction
  - /2010/05/body-text-extraction/
tags:
  - Berkman Center
  - BTE
  - Python
---
A while back, when I was a Berkman intern, fellow Berktern Brian Young and I
spent an afternoon modifying a Python script called BTE (Body Text Extraction).
The script is an automated way to pull out the principal portion of text (the
body) of an HTML document, and works by finding the portion of the document
that has the highest ratio of text to tags. At the time I was interested in
using BTE in a web application to do real time body extraction, which meant I
needed something that was fast. BTE wasn't quite fast enough, so Brian and I
made it faster (for the nerdy among you, we improved BTE from O(n<sup>3</sup>)
to O(n<sup>2</sup>)).

So why am I posting this now? Well Brian and I contacted BTE's author, Aidan
Finn, regarding the changes, and Aidan has recently incorporated our changes
into the official code.

Big thanks go to Brian. I couldn't have done the coding myself (I didn't and
still don't know Python,) and while at the end we weren't sure who did what,
I'm sure Brian's 1337 computer hacking skills were far greater than mine.

More information on BTE can be found [here][1], and the code can be found at
[GitHub][2].

 [1]: http://www.aidanf.net/archive/software/bte-body-text-extraction
 [2]: http://github.com/aidanf/BTE
