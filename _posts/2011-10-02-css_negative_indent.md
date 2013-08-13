---
title: "CSS troubles: Negative text-indent not hiding your text?"
category: tech
layout: note
---

I am so totally thankful for this post I found today by [Adam Bard](0).

If you’re using the tried-and-true [negative `text-indent` for image replacement technique](1) whilst building a website, make sure that the element you’re working with is not aligned to the right.

Simply setting `text-align: left` will fix this problem.

Thanks, Adam Bard! :) This problem had me stumped for a while.

*PS:* An astute reader pointed out that I neglected to explain why someone would consider using a negative text-indent in the first place. If you're using a background image replacement for image-text, then a negative indent will shuffle the text off the page. The technique gets used a lot for things like logos or icons.

[0]: http://blog.adambard.com/2008/02/20/why-isnt-my-negative-text-indent-hiding-text/
[1]: http://www.mezzoblue.com/tests/revised-image-replacement/

