---
layout: post
title:  "Check Hyperverse Status"
---

When we try to login via the Hyperverse backoffice login page (h5.thehyperverse.net), sometimes the login does not seem to work as expected, it just gets stuck after we verify the Google captcha. It seems like its trying to get us to the backoffice page, but it does not. This is a very frustrating experience. It happens because the Hyperverse server simply rejects our request to login since their system has detected frequest requests from the country you are trying to login. May be, to discourage the hackers trying to access the system but there are other smart ways of doing this. We do not know why the Hyperverse Technical team decided to do this.

In order to log in successfully, we need to turn browse via VPN. Let's say we switched to United Kingdom VPN, but still, when I try to log in, it simply does not work again! It's due to the same problem, Hyperverse servers have blocked requests from the United Kingdom too!

So to find a way around it, we decided to build an app that checks the status upfront. You simply need to open the app, then tap on "Click Status":

![Hyperverse](/blog/images/upload/post1/1.png)

These are the following steps:
1. Goto [this link] (https://hypercommunity.github.io/). When browsing via Google Chrome, you will be prompted to install the app. If you do not see the prompt, you can simply tap on the three dots on the top right corner of your browser and tap on "Add to Homescreen" to install the app.
2. Then simply tap on "Click Status". If it redirects to the official Hyperverse Login page (h5.thehyperverse.net), then you do not need to connect via a VPN. You can simply log in and get into the backoffice straight without any problems.
3. If you see the message "Not working, please use VPN to login", that means you have to activate VPN. Just activate your VPN and again tap on "Check Status". If it still throws the same message, switch to another country VPN. Do this until it redirects to the backoffice login page. 

Hope you liked the app that we built for your own convenience. 