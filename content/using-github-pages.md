title: Using GitHub pages 
date: 2023-06-03 20:20 
modified: 2023-06-05 20:36
tags: Pelican, Blog 
keywords:
category: Blog
slug: using-github-pages 
author: Raymond Halim
summary: Why do I choose to use GitHub pages?
lang: en 
translation: false 
status: published 

## Why do I choose to use GitHub pages?

From the opening sentences of [GitHub pages](https://pages.github.com/), this solution seems to be a good match to my need to make a online resume or 1-page portfolio.

Below is an excerpt directly from [GitHub pages](https://pages.github.com/).

> Websites for you and your projects <br/>
Hosted directly from your GitHub repository. Just edit, push, and your changes are live

It could also serve as a way to 

- Learn how to use GitHub
- Learn how to use Git, a version control management
- Learn how to host in GitHub pages or host a website 

<br/>

The drawback is that it is limited to **one** site per GitHub account/organization. In which kind of is making [GitHub pages](https://pages.github.com/) purpose to be leaning towards showing personal resume or 1-page portfolio. 

<br/>

## What is GitHub pages?

[GitHub pages](https://pages.github.com/) is a static site that takes HTML, CSS, and JavaScript files straight directly from a repository on GitHub, optionally runs the files through a build process, and publishes a website.

To publish a user site, user needs to create a repository that is named `<username>.github.io`. 

I decided to use Pelican as I am familiar with Python. In order to set up Pelican to publish, there needs to be a branch aside from `main` to expose the HTML static page output. I chose to have `gh-pages` branch that is dedicated to publish.

<br/>

## Prohibited uses of GitHub pages

- Not intended for or allowed to be used as a free web-hosting service to run online business, e-commerce, or any other website that is primarily directed at either facilitating commercial transactions or providing commercial software as a service (SaaS)
- Should not be used for sensitive transactions like sending passwords or credit card numbers
- Recommended limit no larger than 1 GB
- GitHub pages deployments will timeout if they take longer than 10 minutes 
- Soft bandwidth limit of 100 GB per month 
- Soft limit of 10 builds per hour. Limit does not apply if you build and publish your site with custom GitHub Actions workflow
- [GitHub terms of service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service)

<br/>

Cheers!
