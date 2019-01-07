---
title: test
author: ''
date: '2019-01-01'
slug: testnewpost
categories: []
tags: [help!]
---

{{ partial "about.html" . }}

Testing to see if this new page appears anywhere. Okay, it does. Excellent. Now how do I remove the date and tags? Not by removing it from the YAML!

For Markdown syntax: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet



Can I do line breaks just with enter? Kind of. But it didn't add the extras. <a href="http://twitter.com">Twitter link</a> Links work using html, so maybe linebreaks will too.
</br>
</br>
</br>
</br>
Add some words after the break. Excellent, that works. Now a list! Can't do a bullet list with bullets using only this page - may need to add style="list-style-type:disc" to css. That's true even when using markdown syntax instead of html.
</br>
<ol>
<li>List item 1</li>
<li>List item 2</li>
<li>List item 3</li>
</ol>

* List item 1
* List item 2

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")