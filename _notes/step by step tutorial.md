---
title: Step-by-step Tutorial
---

You can set up a [[public exocortex]] of your own in a few minutes, and have your own personal corner of the Internet where you’ll seed and grow ideas.

If you’re familiar with [[Markdown]] and/or HTML, you’ll be right at home, as that’s how your notes will be formatted.

The end result will look similar to this:

img

# Tutorial

## Introduction

Github will be used to store all your website data on the cloud; it's convenient to upload updates to, is accessible and editable from anywhere, and keeps full version history of changes as well as provides easy options for back-up.

Netlify will be used to deploy the files stored on Github as a web-server; it automatically updates whenever an update is made on your Github repository. Github does offer its own static webhost, but Netlify is necessary due to certain plugin support limitations. 

Both services are entirely free. The only cost you will see is if you choose to push your site onto a custom domain.

You may also consider [[alternative setup on Neocities]] and [[self-hosting your Exocore]].

## 1. Setup Github and Fork the Repository

The first step is to simply fork our [template repository on Github]().

If you are unfamiliar with Github and do not have an account, please first follow the [[Github Tutorial for Exocore]] where you will be handheld through the steps to [create a Github account], [install Github] and [clone the Exocore repository].

Continue below once you have forked the repository to your own account.

## 2. Connect your GitHub repository to Netlify

Netlify will serve your files onto the web and update automatically whenever an update is made to your Github repository. 

To do this, we need to connect your GitHub repository to Netlify:

1. Navigate to [Netlify](https://netlify.com)
2. Log in with your Github account
3. Once logged in, click the “New site from Git” button
4. On the next page, select GitHub as the continuous deployment provider (you may need to authorize the connection, in which case, approve it)
5. On the next page, select your digital garden repository from the list
6. On the next page, keep the default settings, and click on “Deploy site”.

Wait a couple of minutes for the initial deploy to complete.

Once that’s done, your site will be available on the Internet via a generic Netlify URL, which you can change to a custom domain later if you’d like.

## 3. Optional: Custom Domain



---

That's everything you need, your site is now live. Follow up with more details on [[writing posts]] and [[site customization]], and read about [[Updating files on Github]] if you were new to Github.