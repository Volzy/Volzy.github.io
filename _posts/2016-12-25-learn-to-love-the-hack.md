---
layout: post
title: Learn to love the hack
---

# Learn to love the hack

Last week I held a talk about Flexbox at work. My CTO uploaded a picture from my slide to social media.

Whenever I see quoted tweets from conferences and such, I always feel a bit torn. The content is probably pretty cool and give great insight to the attendee, but often doesn't say much about the context it was said in.

Therefore I decided to do a little write-up on the context behind the slide - mostly because seeing a quote like that, would personally leave me either mortified or intrigued to know more.

![The slide in question](https://image-store.slidesharecdn.com/e1689125-952d-494f-9da9-715c3f0cc034-large.jpeg)

## The context of my point

Back in October when I attended Smashing Conference in Barcelona. Jen Simmons had a very exciting talk about ["Real Art Direction on the Web"](https://www.youtube.com/watch?v=5Z7lSSMwRgo). She stated that Flexbox wasn't really intended for layouts and that the future draft of CSS Grid was indeed the power player for future layouts. Backed by Chris House in ["A Complete Guide to CSS Grid Layout" (featured on CSS-Tricks.com)](https://css-tricks.com/snippets/css/complete-guide-grid/), where he essentially calls all layout possibilities prior to "CSS Grids" a hack. That may be true, but my point in "Learn to love the hack" is that there are differences between hacks - and all hacks are not all bad. In fact, some hacks are awesome and we should learn to embrace them, simply because our future work depends on them to pave the way (I'll get back to that).

## A bad hack

The bad hack is the unintelligent solution to a problem, that is done in a way, so the user may experience it as an error and adds doubt or confusion to the situation, the user is in.

## A clever hack

My definition of a good hack is a solution to a problem, which is solved in a way that is seamless and provide a good user experience (UX).

## Hacks are the corner stone to innovation

If we didn't hack to solve UX issues, I bet you that we wouldn't have the exciting web technologies we have today. Hacks are essentially solutions to unconventional behavior and "odd thinking" in our search for a good customer experience.

During my ten-something years as a web developer, I don't think, I ever came across a UI designer who was satisfied with the visual appearance of checkboxes, radio buttons and select/dropdowns provided by the browser. These are the perfect example of how innovation happens through hacks. The hack of styling checkboxes was to add a background-image to the radio button's label and a bit of javascript to toggle true/false. This can now be achieved using CSS only with ```:before``` and ```:after``` pseudo classes ([If you have no idea what I'm talking about, here's an example](http://codepen.io/volzy/pen/YpmLgy/)).

And it (the true/false toggle we call a radio button) can look in all kinds of shapes and sizes. Like Apple's sliding toggle. It's simply a styled checkbox. Nothing more, nothing less, yet most of us agree, that it looks a bit more sexy and adds more branding than the good ol' [x] appearance.

Same goes with sticky footers, holy grail layouts and the list goes on. Flexbox solves this with ease today, but less straight forward (yet still clever) ways paved the way for years. The (clever) hacks we do today, will, if the use case prove valid, be the standard of tomorrow.
