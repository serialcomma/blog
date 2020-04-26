---
layout: post
title: "Choosing A Monospace Typeface"
date: 2020-04-25 11:00:00 +0800
categories: [design, jekyll]
tags: [design, typography]
image: 2020-04-25-jetbrains-mono.png
image-alt:  "screen capture of JetBrains Mono typeface"
image-caption: "JetBrains Mono"
---

Having chosen a primary typeface and a complementary typeface for this project, it occurs to me that I will also need a monospace typeface for displaying blocks and snippets of code.

I can't pretend I selected the monospace typeface with anything approaching the rigor of the other two. I saw a reference to JetBrains Mono, spent five minutes on the [website](https://www.jetbrains.com/lp/mono/), and made the decision.

JetBrains does a better job than I could of explaining why their typeface is well-suited to coding. Their website is a concise masterclass in demonstrating the considerations in designing a typeface for a specific purpose. I urge you to spend a few minutes studying their site.

Figure 1 is a comparison of JetBrains Mono and the sans serif typeface for this project, Sarabun.

<figure>
  <img src="{{ site.baseurl }}/static/img/2020-04-25-jetbrains-mono-sarabun.png" alt="sample text in jetbrains mono and sarabun" class="post__image" style="max-height: 10rem;" />
  <figcaption class="post__caption">Figure 1. JetBrains Mono (top) and Sarabun</figcaption>
</figure>

And here is a code block:

```css
hr {
  margin-top: 20px;
  margin-bottom: 20px;
  border: 0;
  border-top: 1px solid #F7F1F1;
  border-bottom: 1px solid #fff;
}
```

Very nice.

The only downside is the font is not available on Google Fonts so I had to figure out how to upload it a different way.