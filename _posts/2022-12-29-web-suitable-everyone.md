---
title: Creating a web suitable for everyone
date: 2022-12-29 12:00:00 +/-0100
categories: [Web, Accessibility]
tags: [ux]     
author: giulia
description: Responsiveness is at the core of web development— but why not accessibility?
comments: false
media_subpath: assets/img/web-suitable-everyone
image:
  path: /cover-image.webp
---
As you’ve probably already seen from my previous couple of blog posts stemming from the Content Strategy degree I’m currently undergoing, I have been thoroughly enjoying digging my teeth deep into everything content so far. One of the courses that I’ve particularly enjoyed is Digital Publishing Platforms, led by Eric Eggert, in which we dove into the history of the web, some HTML+CSS basics, and, most interestingly of all (at least to me) accessibility.

One of the assignments of this class was to select a video from a list prepared by Eric and write a blog post with our thoughts about it. As I skimmed through this list, one title, in particular, caught my eye: [Dear Developer, the Web isn’t about you.](https://www.paris-web.fr/2018/conferences/dear-developer-the-web-isnt-about-you)

## A short summary of the talk

Charlie Owen is the brain behind the aforementioned presentation and was, at the time, lead frontend developer at Springer Nature, one of the largest academic and scientific publishers on the planet (Linkedin tells me she has since switched to Platform Engineer — you go, girl!).

- In her talk at the Paris Web Conference in 2018, Charlie leads us through a very brief history of the web, “the single biggest invention in recent human history” as she names it.

- Since this blog post should focus mainly on my reflections from this talk, I will just briefly summarise some main points to give a bit of context:

- The web was built upon a simple and robust technology: HTML. But modern development is focusing on making things “fun” with JavaScript without thinking too deeply about the reliability of those websites.

- The advent of smartphones reinvigorated web development after the “Netscape vs. Internet Explorer fiasco”. Now, mobile-first and responsiveness are the name of the game.

- The average phone worldwide was a Moto G4 on 3G internet at the time of the speech (2018).

- Performance is one of the major issues facing websites. 53% of people leave a website if it takes longer than 3 seconds to load.

- We need to go away from “move fast and break stuff” and go towards “move at an appropriate speed and make things work”.

- Coding isn’t the center of the universe. Design and UX are also crucial because we aren’t developing websites for developers. We are creating websites for everyone and the most important thing is that every type of user can access and interact with them.

- When designing websites we should focus on the stress case, not the happy path. Websites should work in the worst network conditions and even be usable with defective hardware (like cracked screens).

## Web accessibility for Content Strategists

The talk was very entertaining and I learned a lot. I have always been interested in the field of usability and accessibility and having worked behind the scenes in a few software development projects, I could relate to some of the thoughts expressed by Charlie. Without a UX team, there is often no thought put behind whether designs make sense for the user. Furthermore, performance hasn’t always been the focus of developers, especially those writing bulky Java code. Software developers don’t often automatically think about the end-user and it’s arguable whether it should be part of their job description or not (but I guess this is a topic for another day).

It may be surprising to talk about web development within a degree course designed for future content strategists. However, since the vast majority of content is online nowadays, I argue it’s important to familiarise yourself with these concepts to deliver something that people will and can read/use/watch/etc.

After watching this video, I thought to myself: “As a content strategist, what could I do to contribute and make the web more accessible?”. And here are my thoughts:

### Simply start with accessibility

We are taught over and over again to create personas to figure out the target audience for the content strategies we create. However, unless a website is specifically created for people with disabilities, they would rarely be part of the array of personas. That’s why every website must be developed with accessibility first in mind. Every content strategist, designer, developer, and project manager working on a web development project should familiarise themselves with standards such as W3C and ensure that best practices are implemented.

At a deeper content level, content strategists should reflect upon the relationship between text and image and its impact on accessibility. Often images are used to support what’s written in the text, but not everyone can see images and alt-texts don’t always do a great job of describing them. Text alone should be written so that it can be understood without images.

Furthermore, images and other types of media can slow down websites by making them very heavy. If you have a 3G connection on a basic smartphone, you’re stranded somewhere, and you desperately need to know when the next bus is coming, you don’t care to see a high-definition image of a bus driver smiling at you and giving you thumbs up. It’s important to ensure that optimized media is part of your content strategy.

### Cater for the stress case

And this leads me to my next takeaway: the stress case. In my opinion content strategists, particularly content designers and information architects, have the most influence to cater for the “stress case”. Content strategy is about “putting the information there where the user needs it”, and many websites miss the mark in this aspect. Imagine being in labor and your hospital website doesn’t clearly state where the entrance to the childbearing clinic is, and it doesn’t inform you that you need your covid pass to enter. Or you’re in a foreign country and you fall ill, and you can’t find the emergency number on the hospital website. These are extreme cases that might only impact a few people, but they can severely impact those few people’s life and well-being. Content strategists should focus on catering to this need. Before thinking about adding cool animations, think first about “How can I architecture the website’s content to be able to help people?”.

### Go back to basics

Lastly, there was a section in Charlie’s talk that I did not mention in my takeaways because I thought it deserved its own little paragraph. She mentions one solution that is currently implemented by Springer Nature to ensure that websites are accessible for everyone: websites at different levels.

In a nutshell, on slow internet speed and older devices, websites are presented as a basic formatted HTML page. On faster internet, CSS is added. And on high-end devices with very fast internet speed, JavaScript is added on top.

This type of website design ensures that everyone can access the content and that websites are still very robust since they don’t rely on JavaScript to be displayed.

Deciding to build a website in this way certainly doesn’t fall directly under the scope of a Content Strategist, but we can definitely try to influence the decision of project managers and web developers by showing the benefits of this approach. It’s not only great for people with disabilities or in more adverse situations, but it could also be a personal choice for people to load a page simply in HTML, for example, to save on mobile data.

## Summary

As I’m learning more and more throughout my journey in the Content Strategy universe, accessibility is a crucial aspect of any successful content strategy. If a large part of the population is unable to access or interact with your website or application, you don’t only cut out a large part of the possible target market, but you are continuing a culture of separation that started with Netscape and Internet Explorer. I will certainly take more care to learn more about accessibility and incorporate best practices in my future work, as well as update any suboptimal past work.