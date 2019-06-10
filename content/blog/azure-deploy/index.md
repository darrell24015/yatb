---
title: Deploying to Azure
date: "2019-06-10T00:30:03.284Z"
---

Learning Gatsby has been going along well. I've created a really simple "Hello World" web page and a bare-bones blog page with the [Gatsby Starter Blog](https://www.gatsbyjs.org/starters/gatsbyjs/gatsby-starter-blog/).

Deploying a Gatsby site to [Surge.sh](https://surge.sh/) is insanely easy! Even posting a site to GitHub pages was not too difficult. But what about deploying to a production level cloud service like Amazon AWS or Microsoft Azure? Where Surge and GitHub are free, deploying to Azure could possibly incur charges. Luckily, I have a 12-month [free trial](https://azure.microsoft.com/en-us/free/) account with Microsoft Azure, so I was willing to give it a try. 

Deploying to Azure was not on the usual Gatsby list to [deploy and host](https://www.gatsbyjs.org/docs/deploying-and-hosting/), but there was a specific article posted on the Gatsby blog that [I found here](https://www.gatsbyjs.org/blog/2018-11-05-deploying-gatsby-to-azure/). You can read the blog post for the gritty details.

How did it go? Well, to be honest, navigating around Azure has a bit of a learning curve. Getting things configured and creating a "tenant" account with Microsoft was a bit challenging. This is a service geared towards enterprise production work and not something simple for personal/hobby/educational use. That said, I was able to get a Storage Account configured for static web hosting. Going by the excellent instructions provided on the Gatsby blog, I got the VS Code extension installed. After few more hoops to jump through, I got the Azure device linked to VS Code.

You can [view the results here](https://gatsbydemostorage.z13.web.core.windows.net/) - if I'm lucky, you should be seeing this same blog post on Azure, assuming you found this blog on Surge.sh first.

![Developer](./undraw_web_developer.png)


