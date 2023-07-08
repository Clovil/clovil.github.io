title: HTML, CSS & JavaScript
date: 2020-11-22 15:36
modified: 2020-11-22 15:36
tags: Tech, Web, Blog 
keywords:
category: Blog
slug: html-css-&-javascript
author: Raymond Halim
summary: What are HTML, CSS, and JavaScript?
lang: en 
translation: false 
status: published 

## HTML, CSS & JavaScript

When we browse the web and stumble on websites, we are looking at how these 3 languages comprise a website.

Understanding how these 3 languages (HTML, CSS & JavaScript) interacts will be a key element if you are pursuing a web developer career.

This is pretty much the gist of HTML, CSS, and JavaScript:

- HTML is for adding meaning to raw content by marking it up.
- CSS is for formatting that marked up content.
- JavaScript is for making that content and formatting interactive.

<br/>

## Examples

This is what HTML looks like for displaying a paragraph of text.

<pre>
    <code>
    &lt;p id='some-paragraph'&gt;
        This is a small paragraph. A paragraph might consist more than 1 sentence. That is why I am writing this example.
    &lt;/p&gt;
    </code>
</pre>

<br/>

CSS example when you set the size and color of that paragraph.

<pre>
    <code>
    p {
        font-size: 20px;
        color: blue;
    }
    </code>
</pre>

The appearance of a website is determined and controlled by HTML and CSS. In you want to have interaction within a website, that is where JavaScript takes a part in building a website.

Below is an example of what happens when user clicks a paragraph that we wrote above.

<pre><code>
    var p = document.getElementById('some-paragraph');

    p.addEventListener('click', function(event) {
            p.innerHTML = 'You clicked it!';
        }
    );
</code></pre>

This is part 1 of Introduction of HTML and CSS. I found out that the tutorial is very friendly for beginners who wants to learn more about web development or HTML and CSS in general. HTML & CSS is hard [but it doesn't have to be].

Cheers!
