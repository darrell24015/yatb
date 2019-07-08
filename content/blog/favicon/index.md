---
title: Change Your Favicon in Gatsby
date: "2019-07-06T19:16:37.121Z"
---

In one of the (many) posts and articles I've read about getting started with Gatsby, one author adamantly exclaimed "Don't forget to change your favicon!" This refers to the tiny little icon for your site that shows up in the browser tab. I suppose it could be a bit embarassing to use a Gatsby starter all customized to your own liking but still sport the purple Gatsby logo.

So, with this site being an adapted [Gatsby Starter Blog](https://www.gatsbyjs.org/starters/gatsbyjs/gatsby-starter-blog/), I didn't want to be derelict in my duties. I began my quest to pop in my own favicon by looking in the more obvious places (the root folder of the site when doing it the old fashioned way).  Hmmm, nope. Wait, there's a sub-directory called /static with a favicon.ico and robots.txt - maybe I drop it in there. Shucks, nope, that's not it either.

So, turn to some Google-fu and see what I can find. There's an [issue on Github](https://github.com/gatsbyjs/gatsby/issues/2987) about adding a favicon. Naw, that doesn't look like that's my solution. Then there's [this article](https://www.atrost.com/posts/add-favicon-gatsby/) about importing in multiple sizes of your icon and using Helmet.  Well, this Starter doesn't seem to be working that way either.  

Like Goldilocks, I finally find a post that is [just right](https://medium.com/@itguymax/add-a-custom-icon-to-your-gatsby-site-in-just-a-few-a-minute-4e5b5f12ca40)! I placed my icon in the src/images folder and edited the gatsby-config.js file to point to that location.  Upon build, Gatsby creates the favicon.ico file and places it in the correct location for you.  **Success!** 

![Website](./undraw_website.png)