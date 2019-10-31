---
title: JAMStack
subtitle: >-
  JAMstack is a new approach of building websites and apps that are fast,
  secure, have a lower cost of scaling and delivers a better developer
  experience.  
date: 2019-10-30T18:30:00.000Z
thumb_img_path: /images/avatar.png
excerpt: >-
  The way I spend time out in nature can affect how much my physical and mental
  health will recharge and how I benefit from it.
hide_header: true
template: post
---
JAMstack is a new approach of building websites and apps that are fast, secure, have a lower cost of scaling and delivers a better developer experience.  

JAM stands for JavaScript, API & Markup.





JavaScript: It runs on the client-side and handles any dynamic request or response. Any frontend framework, library or playing JavaScript can be used.  

APIs: Reusable APIs are used to abstract all database actions and server-side logic. These APIs can be accessed over HTTPS with JavaScript. These APIs can be third party services or custom functions.

Markups: Websites are served as static HTML Files. These can be generated from source files, such as Markdown, using a Static Site Generator or Build Tools. 



Best Practices



According to Netlify Co-Founder Mathias Biilmann, following are the Best Practices :

Entire site/app on a CDN

Atomic deploys

Instant cache invalidation

Everything lives in the Version Control System

Automated builds



Content delivery network

All the markup and assets are pre-built which are served via CDN. A Geographically Distributed group of servers working together to provide fast delivery of content on the internet can be referred to as a Content Delivery Network(CDN).



Atomic deploys

A major goal of atomic deployment is to drop the maintenance window so that the app/website is always up and running for the user. Each deploy is a wholesome snapshot of the site. This helps in providing a steady version of the site globally.



Cache invalidation

A traditional dynamic site is hosted over a single server, whereas a modern static site is hosted over a Content Delivery Network(CDN). Once the new changes are done and build is uploaded, CDN invalidates its cache, and the new build is life in an instant. 



Automated Builds

Your server is notified when a new build is required, typically via webhooks. The server builds the project, updates the CDNs and the site is live.



Traditional Website vs. JAM Stack Website

Following are the Key Differences:

Traditional

JAM Stack 

Development and Hosting are integrated

Development and Hosting are segregated

Major Updates are pushed to production servers

Static Site Generators along with a Version Control System are used for pushing major updates

Traditional CMS like WordPress or Drupal are used for Content Updates

Static Site CMS are being used for Content Updates

When a user requests a page, After a long series of interactions between database, backend code, server, browser and layers of caching the file gets processed and served to the user.

When a user requests a page, file is already compiled and gets served to the browser from a CDN.



Development



Most common approaches to generate HTML assets are the following, however, there is no restriction :



Hand Coding: Simple and Ideal for basic pages

Static Site Generator: Static Site Generator is used to power JAMstack sites. There's no restriction on which SSG you decide to use. Some popular SSGs are 

Gatsby

Next.js 

Hugo

See more SSGs

Frontend Framework: It is possible in some Frameworks to output static HTML files. Eg: React, Next.js, Vue.js, Preact



Deployment



The built site needs to be hosted over a CDN. Check deployment services from here:

Netlify 

Zeit 

Github Pages 

Stackbit

See more deployment services



Deployment



There are great services available to make a JAMstack website dynamic. Here is a curated list of Services for static websites.

Custom Functions: Reusable APIs can abstract custom functions. For this AWS lambda functions or Netlify Functions can be used.

Custom Data:   FaunaDB Serverless GraphQL can be used to add features to the site. One may want to store user profiles, shopping cart data, or other dynamic data. 

Comments, Forms, E-commerce, Search and other dynamic features can be added in a JAMStack site static services. 

CMS



A Headless Content Management System can be used to manage the content of a JAMstack website. The new build of the site will be triggered and then deployed as static assets once a change in the CMS is made. 



Netlify CMS

Contentful

Headless WordPress

Ghost

Strapi

Forestry

Sanity.io

See more CMS services
