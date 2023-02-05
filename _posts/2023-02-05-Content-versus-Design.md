---
layout: post
title:  Content versus design
date:   2023-02-05
categories: design content
---
## The benefit and dangers of being in total control!
Now that this blog is hosted on [Github Pages](https://pages.github.com/) and using [Jekyll](https://jekyllrb.com/) as the
technology, in theory I now have total control over both the content and the design of the blog.

For me this presents a wonderful opportunity, but also a great danger.
It's quite possible that I'll just obsess about the design, and never write
any posts at all!

I've decided to do one thing that I hope will support me
in keeping the two concerns apart. 'Themes' are what controls how a Jekyll looks. I discovered that there is a ```remote_theme``` plugin that allows you to specify a theme held in a separate repository. Right now I have;

``` yaml
remote_theme: benbalter/retlab
```
which exploits the ``retlab`` theme from [Ben Balter](https://github.com/benbalter). If I ever want to tweak it, I'll fork it into a new repo, e.g. ```robs-theme``` and be able to
specify;

``` yaml
remote_theme: robphippen/robs-theme
```

That means I won't 'pollute' this repo with design stuff. When I want to think 'content' I'll come to this repo instead.

:smiley:.
