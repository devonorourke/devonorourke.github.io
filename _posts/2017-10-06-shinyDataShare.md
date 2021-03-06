---
layout: post
title:  "Shiny guano"
date:   2017-10-06
categories: posts
author: devonorourke
tags: 'computery'
---

# The motivation
One big focus of my research involves collecting samples of bat guano and identifying the insects in bat poop. Why do this? Two pretty straightforward reasons:  
- 1) I wanted to design a method that used molecular tools to extract and isolate insect DNA from bat guano because this could possibly become a rapid and precise pest-detection strategy. We currently don't have any means in constantly surveilling for insect pests other than using traditional trapping methods and very retroactive aerial surveying. In short, bats will *always* do a better job of sampling the environment for insects, so I wanted to test whether or not the insects bats are eating **include invasive pests**.  
- 2) I wanted to provide the first temporal analysis of bat diets. Because bats generally fly at night it's really hard to identify the entirety of thier diet. While you can always tease apart the insect present in their stool with a microscope and some tweezers, it's time intensive, takes a lot of training, and you can generally only get to identifying an insect at the Family taxonomic level. In other words, you know it's a certain kind of beetle group, but have no idea which species of beetle it actually is. One reason molecular techniques are possibly more useful than traditional microscope/by-hand identification is that they can often provide you species-level resolution to what's in bat diets. In addition, you might need to spend an hour or three looking through a single guano pellet under a microscope; molecular workflows can process hundreds of samples in an hour so we can start to scale things to a degree that allows us the necessary sample size to say anything definitively about the characteritics of bat diets over time.  

This is all to say I have **thousands** of bat guano samples to analyze. But here's the key thing - these samples were collected almost entirely by volunteers, and I wanted to figure out a way to disseminate the information to the public who made this whole project possible. In addition, this project was something that involved 3 years of collaborations, and I wanted a format which I could update on the fly without having to reformat and modify everything I put together for the public. Having already started building a website, I looked for a set of tools that would allow me to essentially do a few things:  
- 1) Share real data with the public in real time  
- 2) Make the interface that data is shared interactive (ie. no spreadsheets)
- 3) Make the interface accessible through a website  

How to do this? *Shiny apps*.  

# Learning about *shiny apps*
I got started by following along [Dean Attali's excellent tutorial](http://deanattali.com/blog/building-shiny-apps-tutorial/) which introduced the concept of building a Shiny app from scratch.
