---
title: "Hello"
date: 2021-11-30T00:35:34+05:30
draft: false
---
Hi! This is supposed to be the first of (hopefully) many posts to come. I've been putting off starting a blog for a long time - Google Keep/Joplin isn't the best place to document technical learnings. With this, I hope to organize and reflect on whatever I learn during my development journey that I feel is worth documenting. Maybe throw in some rants as well. 

## Just use Medium?

I intended to start writing on Medium initially until it occurred to me that it wouldn't allow me to customize my blog. I wanted to have control over *my* blog which means control over -  

* **Appearance**  
From basic things like changing fonts and tweaking margins to building the main page from scratch.
* **Analytics**  
Being able to run my own analytics.
* **Miscalleanous**  
Customizing OpenGraph embeds, showing popups, adding animations, embedding more than just tweets etc.

It was clear that I wanted to do more than what Medium allowed. Medium is great, but as a developer I want to be able to tweak almost everything on my page because I can (and because I enjoy it 😬)

## Build Your Own Blog?

The next idea which occurred to me was building my own blog in React. I looked around and eventually found [GatsbyJS](https://www.gatsbyjs.com/), a framework built on top of React for [static site generation](https://www.cloudflare.com/en-in/learning/performance/static-site-generator/).  

This seemed like the perfect idea. I know a bit of React so I could get started with it quickly.  

Having spent a day playing with GatsbyJS, it hit me that this would turn into another project that would suck a lot of my time. I felt that my focus would shift from writing blog posts to writing the blog itself. Did I need a whole JS framework with its bells and whistles for a simple blog?

I didn't want to *over-engineer*, and going down the GatsbyJS rabbit hole taught me that. I started looking looking for other static site generators until I came across [Hugo](https://gohugo.io/).

## Enter Hugo
Hugo is what this page was built with. It's a **very fast** static site generator written in Go.
{{<figure src="/img/hugo-speed.png" title="Very fast indeed">}}
Hugo doesn't require a JS framework to run in the browser nor does it compromise on control.  
There are tons of themes on [themes.gohugo.io](https://themes.gohugo.io) to start with,
I'm using the [PaperMod](https://adityatelange.github.io/hugo-PaperMod/) theme for now but I can always fork it (and I will, soon🙂).