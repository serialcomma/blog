---
layout: post
title: "Accessibility"
date: 2020-05-10 12:00:00 +0800
categories: [tech, jekyll]
tags: [tech, design, accessibility]
image: 2020-05-10-accessibility.png
image-alt:  poor contrast tightly spaced text versus high contrast looser text
image-caption: 'Accessibility Comparison (Text from <a href="https://en.wikipedia.org/wiki/Giambattista_Bodoni">Wikipedia</a>)'
---

Are you reading this page without enlarging the text or using a screen reader or other assistive technology? If so, count yourself fortunate. A significant percentage of web users have one or more conditions that make it difficult or impossible to consume the content on a web page without assistance of some kind.

Designing a website for accessibility is a practice that seeks to remove barriers that prevent people of all abilities from using content. It's more than just choosing type sizes, weights, and colors to improve legibility, as the example above shows.

> For example, when a site is coded with semantically meaningful HTML, with textual equivalents provided for images and with links named meaningfully, this helps blind users using text-to-speech software and/or text-to-Braille hardware. When text and images are large and/or enlargeable, it is easier for users with poor sight to read and understand the content. When links are underlined (or otherwise differentiated) as well as colored, this ensures that color blind users will be able to notice them. When clickable links and areas are large, this helps users who cannot control a mouse with precision. When pages are not coded in a way that hinders navigation by means of the keyboard alone, or a single switch access device alone, this helps users who cannot use a mouse or even a standard keyboard. When videos are closed captioned or a sign language version is available, deaf and hard-of-hearing users can understand the video. When flashing effects are avoided or made optional, users prone to seizures caused by these effects are not put at risk. And when content is written in plain language and illustrated with instructional diagrams and animations, users with dyslexia and learning difficulties are better able to understand the content. When sites are correctly built and maintained, all of these users can be accommodated without decreasing the usability of the site for non-disabled users.
> -- [Wikipedia](https://en.wikipedia.org/wiki/Web_accessibility)

A lot has been said about accessibility. Scientific studies have been conducted, advocacy pieces have been published, guidelines have been written, laws have been adopted. Not all of it without controversy. Designing for accessibility is not easy or free. But it's the right thing to do.

The industry appears to be coalescing around the [Web Content Accessibility Guidelines (WCAG) 2.1](https://www.w3.org/TR/2018/REC-WCAG21-20180605/) published by the World Wide Web Consortium (W3C). The WCAG 2.1 is organized around four principles:

1. Perceivable - Information and user interface components must be presentable to users in ways they can perceive.
2. Operable - User interface components and navigation must be operable.
3. Understandable - Information and the operation of user interface must be understandable.
4. Robust - Content must be robust enough that it can be interpreted reliably by a wide variety of user agents, including assistive technologies.

Compliance with WCAG 2.1 requires satisfying success criteria. The success criteria are summarized on the W3C's [quick reference](https://www.w3.org/WAI/WCAG21/quickref/) page. There are three levels of compliance: A, AA, and AAA. Level A compliance signifies basic accessibility. Level AA compliance means the website addresses the biggest and most common barriers for disabled users. Level AAA compliance represents the highest (and most complex) level of web accessibility.

I won't discuss accessibility in more detail here because I am not an expert and haven't done enough research to speak knowledgeably about accessibility in general. I will address specific accessibility topics in future posts from time to time and intend to make the Serial Comma website as accessible as I can.

The W3C has compiled a database of tools that can be used to evaluate the accessibility of web pages, should you wish to check the sites you design or use -- the [Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/). The list is several years out of date but is still helpful. Here are three of the more useful other tools I have found:

* [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org)
* [WebAIM's WCAG 2 Checklist](https://webaim.org/standards/wcag/checklist)
* [AChecker](https://achecker.ca/checker/index.php)
* [whocanuse](https://whocanuse.com)

If you have a comment about the accessibility of the Serial Comma website, please leave it on my github page or in a tweet.