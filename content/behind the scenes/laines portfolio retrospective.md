---
title: Laine's Portfolio Retrospective
description: a reflection on what it was like to build laine's portfolio as a first-time user of webflow and figma.
permalink: 
draft: 
date: 2025-03-20
tags:
  - web-design
---
A few weeks ago, [Laine](https://bsky.app/profile/lainesdesigned.com) and I finalized work on [her portfolio site](https://lainesdesigned.com/). For this project, I was tasked with rebuilding her Figma mockups in Webflow. This project took around 4 months to complete, and I'm incredibly grateful that I had the opportunity to learn Webflow to build such an amazing site.

Now that the site is done, I wanted to reflect on my experiences, and share my journey with others who are curious! I will be using this post to share:

- a list of resources that helped me bring this project to life
- things that i would have told myself at the start of the project
- lessons from this project that i hope to carry in my future endeavors

Whether you're someone who has an interest in web design and development, or someone who wants to know how to commit to long-term projects, I hope this can be of some use to you and help you in your own personal journey!

## Background Information
By technicality, Laine's portfolio was 2 years in the making!

Back in April 2023, Laine built the first iteration of her portfolio site on WIX. During the building process, Laine expressed frustration at how cumbersome it was to navigate the editor. Though she "finished" her site, she felt unsatisfied with the end product.

Laine would eventually revisit her portfolio as a part of the (SCHOOL PROGRAM NAME). She was tasked with creating page mockups using Figma. It was here when Laine's site started to closely resemble what it looks like now! The layouts she created for that class was much more in-line with her sensibilities as a designer, and she wasn't held back by the confines of the WIX editor.

Unfortunately, static mockups on their own do not constitute a website; you need to build the site and find a host for these files. Throughout our friendship, Laine has repeatedly expressed her grievances with web design, specifically, the responsive aspect. And that's where I come in, because I love web design!

My love for web design started when I took a semester of web design while I was at university. As part of my classes, I built two static sites using Wordpress and Elementor (now defunct/offline) after making mockups in Adobe XD. My instructor also shared information on how to navigate domain and hosting services.

In early 2024, I borrowed [a book on HTML and CSS](https://www.peachpit.com/store/html-and-css-visual-quickstart-guide-9780136702566) from my public library on a whim. After Twitter (X) made some harmful policy changes in 2023, there was a push from some circles on Tumblr for people to start making websites again. [Guides on how to use Neocities](https://crescentfool.tumblr.com/post/722774758797787136) would be thrown around, and sometime later one of my friends coded [a website dedicated to one of her favorite ships](https://souyoarchive.neocities.org/). Truthfully, I don't think I would have borrowed this book without being inspired by her site, or my past experiences in university!

All of this combined made a good foundation for me to help Laine with her portfolio.

Throughout 2024, Laine would "jokingly" point to the service Webflow, telling me that I should learn it so that she could pay me to build her portfolio and make it real. I didn't take her up on the offer until late November 2024, after watching this tutorial video from [Flux Academy](https://www.youtube.com/@FluxAcademy):

![Learn Webflow: Ultimate Beginner Crash Course - YouTube](https://www.youtube.com/watch?v=RXdH2H01P88&list=PLXC_gcsKLD6nseaESIeQemeJn6SG0-Xbn&index=1&pp=iAQB)

Funnily enough, I distinctly remember checking this out ONLY because I had free time after playing Splatoon. I originally intended to spend most of my time that day grinding for the golden badge on Spawning Grounds, so when I got the badge earlier than expected, a lot of free time opened up. Since I had nothing else planned, I let my curiosity take me to Webflow tutorial land. I mention this little anecdote because I believe that it's important to have spurts of free time to spontaneously pursue things you're curious about; you never know where it'll take you!

## List of Resources
**General Resources for HTML, CSS, JS**
- [MDN Web Docs](https://developer.mozilla.org/en-US/)
- [W3Schools Online Web Tutorials](https://www.w3schools.com/)
- [Stack Overflow](https://stackoverflow.com/)

**Hosts we considered using throughout the project:**
- [Neocities](https://neocities.org/)
- [nekoweb](https://nekoweb.org/)
- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Cloudflare](https://www.cloudflare.com/)

### Webflow-Specific Information
**General Tutorials**
great places to start your learning journey!
- (OFFICIAL) [Webflow 101 - YouTube](https://www.youtube.com/playlist?list=PLPmnoMVpkxfj-DzMkYNf7LM3ebjwoY6b2)
- (OFFICIAL) [Webflow Help Center](https://help.webflow.com/hc/en-us)
- [Webflow Tutorials YouTube Playlist by FluxAcademy](https://www.youtube.com/playlist?list=PLXC_gcsKLD6nseaESIeQemeJn6SG0-Xbn) These are great introductions to Webflow! I think that Flux Academy provides some clarity and insight that is not always given from the official Webflow YouTube channel. These are the specific videos I watched to familiarize myself with Webflow's interface:
	- [Learn Webflow in 16 Minutes (Crash Course) - YouTube](https://www.youtube.com/watch?v=vvyPj5bTcgQ&list=PLXC_gcsKLD6nseaESIeQemeJn6SG0-Xbn&index=3&pp=iAQB)
	- [Learn Webflow: Ultimate Beginner Crash Course - YouTube](https://youtu.be/RXdH2H01P88?si=6vLSBbDiCjfDLej7)
	- [Responsive Website In Webflow (Step By Step) - YouTube](https://www.youtube.com/watch?v=4k6zqNvYX-c)

**Specific**
- [How to Remove MADE IN WEBFLOW Badge with Custom Code - YouTube](https://www.youtube.com/watch?v=3M83d4wMeJE)
- [How To Build A Responsive Website In Webflow - YouTube](https://www.youtube.com/watch?v=WEy7xssGv9s) - this video explains the difference between the different units of measurement that you can use when coding your site, such as PX, REM, %, VH, and VW.
- [Sticky Navigation and Progress Bar with Webflow - YouTube](https://www.youtube.com/watch?v=_k4iTbcqPf8) - I watched this because I was looking for tutorials on how to do a navigation bar. While I didn't follow this specific tutorial, it's great seeing what's possible!
- ⭐[Basic Custom Navbar tutorial in Webflow - YouTube](https://www.youtube.com/watch?v=vHHXUE0wJio) - This one is really thorough, I highly recommend it because the decision making behind the HTML and CSS choices is clearly articulated. The menu is made responsive on all four viewports, which is great!
- ⭐[How to Make Custom Bullet Points in Webflow - YouTube](https://www.youtube.com/watch?v=CJyBK0L0X-U) a visual demonstration of [this webflow forum thread](https://discourse.webflow.com/t/how-to-replace-list-bullets-to-custom-icons-svg/89820)

**MISC**
[Lottieflow - Lottie icon animations for Webflow](https://finsweet.com/lottieflow)