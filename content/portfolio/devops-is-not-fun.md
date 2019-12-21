---
title: "Learning DevOps, Unfortunately"
draft: no
date: '2016-11-05T19:41:01+05:30'
showonlyimage: no
image: img/portfolio/devops-is-not-fun.png
weight: 2
---

Accepting my fate and building robust software.
<!--more-->

![Cloud Services][1]
Art from [Ben Adams](https://www.dribbble.com/shots/4289327-Cloud-Services)

I have said in the past that sometimes I need to learn things outside of my direct area of interest in order to get better at what does interest me. At the time it was learning web development basics (`HTML`, `CSS`) in order to share my analyses with the world and make them more attractive. I have reached another round of this process, and may have even accepted my fate less begrudgingly than previously.

I found myself stuck while working on a project for [**Code for Baltimore**](https://www.codeforbaltimore.org). The goal was to build a web application that could visualize where nonprofits operate in Baltimore City and the connections that different organizations share. I spent time learning `Shiny` and built a simple interactive web application in a short amount of time. Managing its infrastructure became a frustratingly difficult task. All I needed was to build an application, host it on a web service under a custom domain, and automatically re-deploy everytime changes were pushed to `Github`. What became complicated were all the restrictions around hosting while keeping the tool free as it was only a proof of concept.

There were several problems, but they all boiled down to `Shiny` not being an out-of-the-box solution if you don't want to host it on [**shinyapps.io**](https://www.shinyapps.io). It is simple enough to host on `Heroku`, `AWS`, `GCP`, or others but only if you are building in something like `Node.js`, `Python`, or `Go`. I wanted to continue building in `R` if possible, but more importantly I wanted to make end-to-end web app development possible to others with little DevOps knowledge even if they don't use those languages. Many in the `R` community come from a statistical background and not a CS/software background; getting stuck without experience in deployment is frustrating. 

Ultimately I built [**Shinyhero**](https://github.com/jbixon13/shinyhero) as a template for [**Code for Baltimore**](https://www.codeforbaltimore.org) developers to reduce as much friction as possible when building a solution. This could be extended to anyone interested in building production-grade web applications without experience in robust deployment solutions. It utilizes concepts like containerization, automated CI/CD, and package management; I still have a lot to learn about concepts like unit testing or load balancing. More importantly, what I built checks every box I needed and lets me focus on building.      

[1]: /img/portfolio/devops-is-not-fun.png

