---
layout: post
title:  "Markdown Rundown"
date:   2019-01-30 16:54:00 -0500
categories: programming tools
---

Markdown is, on some level, something familiar to everyone with almost any exposure to programming. You may not recognize it as such, but it’s in just about every Github repository out there, hiding in plain sight. In fact, if you’ve ever seen a README, you’ve likely seen a use-case of Markdown, recognizable by the .md filename extension if nothing else. But what kind of weird extension is that? And why is it so ubiquitous?

For those who are curious, Markdown can be a blissfully convenient tool for writing content for the web. Given that this is such an omnipresent task in today’s world, you don’t really have to know any more to understand why it’s everywhere. But the more you learn about its simplicity and ease-of-use, the more it makes sense why you see where you see it.

Markdown is more than just a filename extension. It’s a lightweight markup language. You’ll be familiar with the idea of a markup language from the most famous of them all, HTML. To understand the difference between a markup language and one that is lightweight, imagine the difference between Ruby and Java; ActiveRecord and SQL; or Rails and Rack. There are still syntactic rules that are there to communicate format guidance to a computer, but a remarkable amount of instruction has been abstracted into the background. Just as Ruby can almost escape being recognizable from the symbol-full languages like Java or PHP, Markdown can achieve much of the most common work of HTML while still _basically_ being plain text. Hence, markup that has been pared down—mark-down.

For a clear, comprehensive syntax guide, you can’t beat the one written by John Gruber. Gruber’s documentation is so clear and concise, that I began to question my choice of topic for this post as I was reading it. I was seeing the obfuscation of the very post I was writing right before my eyes! _I paused to think about how this happens to a lot of content creators on the web these days. I paused to think about how the majority of them plow on through that same realization of instant obfuscation because there’s only so much content to be created, yet their jobs are to continually feed the bottomless pit that is the corporate content-ad-industrial complex. I paused to think about what that must do to their souls, remembering that it was exactly this sort of thinking that led me here, to Flatiron School, writing a blog post that nobody was asking for…_

I digress.

Anyway, John Gruber has two or three really good reasons for having what I would call the definitive guide to Markdown. For one, he invented it. For another, besides a few software tools he built that are available for purchase online, his blog and his podcast are his only sources of income. That’s right—the inventor of one of the most widely used tools for writing and formatting content for the web makes his living writing content for the web. Or, more precisely, by being a really knowledgeable person with some widely admired projects under his belt, who has found a way to monetize his opinions. It’s a story of the new American Dream. John Gruber was one of the original influencers. His audience is the old guard of the original web. And Markdown helped him achieve this. It can help you, too.

How does it work? Gruber wrote a software tool (called Markdown) that converts the syntax into HTML. The Markdown system is so popular that pretty much every personal computer is equipped to handle it.

Given that the definitive guide already exists, this post will serve as a high-level overview of what you’d mostly be doing with Markdown.

There are just a handful of things you need to know to get started with Markdown. The first is that once you’ve seen a Markdown file or two, you already know the essentials of how to work with it. It’s that easy. The perfect example of this is how Markdown handles paragraphs. In a .md file, a paragraph is indicated by...a paragraph! You don't have to do anything!

To create an unordered list, there are three options: **\***, **-**, and **+**. Simply use whichever symbol like a bullet, and Markdown does the rest for you:

    - bright
    * city
    + lights

No more `<ul></ul>` or `<li></li>` tags!

Numbered lists are just as intuitive, using numbers followed by periods:

    1. Form a small loop
    2. Pass the free end of the line through the loop
    3. Bring around behind the line
    4. Bring free end down through the loop, while maintaining the original loop

Links are so simple it’s silly. Just wrap the text you want to appear as a hyperlink in square brackets ( [ ] ), with the length juxtaposed as a parenthetical:

    [The NY Times](https://nytimes.com)

You can add a **title** that will appear when a user hovers over the link by adding it in quotations into the parentheses after the link and a single space.

To add emphasis (_italics_), place either an underscore or asterisk on either side of what you want to italicize. To **bold** something, use two.

To designate a header, place an octothorpe ( # ) on either side of the header—one for each hierarchical header step down (two for `<h2>`, three for `<h3>`, etc.).

To apply the “code” format to something, use backticks ( ` ` ).

Block quotes simply use a closing angle bracket ( > ) at the start of each line.

    > email used to look like this
    >
    > you are too young to remember, probably

To make a block of code, forget backticks and just indent each line with four spaces.

To add an image, the syntax looks similar to our aref replacement:

    ![alt text](/image/path.jpg "hover text")

And last, but certainly not least, you can create an unordered list with check boxes as bullets:

    * [ ] got it done
     -  [ ] got the bread
    + [ ] remembered to put spaces between each character

And that’s about it! That should be enough to get you started at least, and everything else is covered by Gruber's [documentation](https://daringfireball.net/projects/markdown/syntax).

This might seem pretty incomplete, given the number of things you can do with HTML. And it is. Markup covers only the most commonly used parts of HTML. However, if you don't want to part with the full functionality of HTML, it doesn't have to be a deal-breaker. You can insert any form of HTML anywhere in a Markdown file totally seamlessly! In this respect, Markup is an excellent example of how you, as a developing programmer, ought to aim to build things. It's **intuitive**. And **it just works**.

To play around with some text and see it work for yourself, John Gruber provides a helpful tool on his website. It's called a [Dingus](https://daringfireball.net/projects/markdown/dingus).

At risk of succumbing to Dingus jokes, I'll conclude here, and just say that if you haven't yet, give Markdown a try!


#### (re)sources ####

* [https://daringfireball.net/projects/markdown/dingus](https://daringfireball.net/projects/markdown/dingus)

#### sources ####

* [https://daringfireball.net/projects/markdown/](https://daringfireball.net/projects/markdown/)

* [https://en.wikipedia.org/wiki/John_Gruber](https://en.wikipedia.org/wiki/John_Gruber)

* [https://en.wikipedia.org/wiki/Markdown](https://en.wikipedia.org/wiki/Markdown)

* [https://en.wikipedia.org/wiki/Lightweight_markup_language](https://en.wikipedia.org/wiki/Lightweight_markup_language)
