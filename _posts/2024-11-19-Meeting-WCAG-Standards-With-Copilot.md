---
layout: post
title: Meeting WCAG Standards With Copilot
tags: web accessibility
categories: tech
thumbnail: accessibility-thumbnail.png
---

As I watched a video on Accessibility Standards, [WCAG](https://www.w3.org/TR/WCAG22/){:target="_blank"}, I thought I'd better check my site and make it at least Level A compliant. 

I used [WAVE Evaluation Tool](https://chromewebstore.google.com/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh){:target="_blank"} Chrome extention to scan my site and saw a bunch of issues with my website....as expected:

- alt tags missing
- mislabeling
- contrast errors
- heading level skipped

<img src="/images/accessibility-thumbnail.png" alt="thumbnail image for Meeting WCAG Standards With Copilot" style="width: 100%" />

As for the contrast errors, I wanted to keep the green as light as possible without making the background completely white. The visual aesthetic adjustment was done manually. I didn't think automating the adjustment may be more time consuming if the outcome was not my linking and trying to express my visual preference in words seemed too much work than me just tweaking the color code.

With alt tage, however, I love that GitHub Copilot installed in VSCode pretty much took care of it for me. All I did was asked Copilot to `add alt tags to the images that's missing the tag in this page`...and boom, it figured the alt text based on the image file name and added them to 50+ images without the tag. 

Copilot also quickly fixed "heading level skipped" issue found on my resume page. The prompt I used was `Can you "heading level skipped" problem in this file?`...and done.

So much has changed since I was a web developer, when all those adjustments were done manually, one by one, taking hours, to make a website accessible. Back then the adjustments could be expensive and time consuming. Today, the hurdles are much much lower. 