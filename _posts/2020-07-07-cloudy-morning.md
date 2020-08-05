---
title: "using Jekyll on tilde.town, circa 7th July 2020"
layout: post
---

Running *jekyll -v*, on the command line, resulted in the following
message:

> -bash: /usr/local/bin/jekyll: /usr/bin/ruby2.5: bad interpreter: No such file or directory

After some research, I found that I could run the following command:

*/usr/bin/jekyll -v*

which resulted in the following message:

> jekyll 3.8.6

I hope this post saves someone else some time.
