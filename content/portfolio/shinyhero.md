---
date: "2016-11-05T19:41:01+05:30"
draft: false
image: img/portfolio/shinyhero.gif
showonlyimage: false
title: Shinyhero
weight: 2
---

An end-to-end Shiny pipeline for the DevOps-illiterate.
<!--more-->

![Heroku][1]  
Art from [Nick Tassone](https://dribbble.com/shots/2679711-Heroku-Kafka)

<h2>
    <a href='https://shinyhero-test.herokuapp.com/' target='_blank'>
    See an example
    </a>
    |
    <a href='https://github.com/jbixon13/shinyhero' target='_blank'>
    See the code
    </a>
</h2>

#### What it is:  
* A template for building Shiny applications and hosting them on Heroku (or other PaaS)
* An automated pipeline for the development lifecyle of an application

#### What I did:  
* Created a minimal example of a Shiny application locally
* Set up [**renv**](https://github.com/rstudio/renv) to responsibly handle package dependencies 
* Wrote a `Dockerfile` to containerize the app for hosting
* Wrote a `.travis.yml` to automate the CI/CD process to Heroku on each push to Github

#### What I learned:  
* PaaS
  + Heroku
* DevOps
  + Docker
  + Travis CI
  + CI/CD pipeline
  + Container Registries
* Package management
  + Renv

#### Why it interests me:  
* Shiny applications are not necessarily written by people with experience in DevOps or web infrastructure
* [**Shinyapps.io**](https://www.shinyapps.io/) allows Shiny developers to deploy easily, but with many restrictions at the free tier
* Rather than learning another language or framework, this tool allows R users more freedom in deployment
* I struggled to understand how to get these tools to work together and want to contribute my solution to the R ecosystem 

[1]: /img/portfolio/shinyhero.gif
