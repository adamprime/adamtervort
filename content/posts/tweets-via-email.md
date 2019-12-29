---
title: "Getting Tweets via Email"
slug: "tweets-via-email"
date: 2019-12-29
lastmod: 2019-12-29
draft: false
description: "I love useful tweets but hate getting on Twitter. Here's how to get a curated list of tweets in your inbox each day."
show_in_homepage: true
show_description: false

tags: [twitter, email]
categories: [productivity]

featured_image: '/images/2019-12/tweets-via-email/tweets-via-email-optimized.jpg' # 1100 px width
featured_image_preview: '/images/2019-12/tweets-via-email/tweets-via-email-optimized.jpg' # 560x170 px for preview image

comment: true
toc: false
autoCollapseToc: true
math: false
---
I really like Twitter for the way it allows you to connect with thought leaders. I don’t particularly like being on Twitter or any social media service for an extended time each day. I decided to find a way to get a digest of tweets from some thought leaders in my inbox each morning. 
<!--more-->

In this example I’m going to set up a digest of tweets from Adam Grant ([@AdamMGrant](https://twitter.com/AdamMGrant)) and James Clear ([@JamesClear](https://twitter.com/JamesClear)). These two are authors and speakers who tweet regularly and have long form writing that I enjoy. Both are also in my RSS feed, but because their writing is usually long form there’s generally a bit of time between articles. I think both are people who put effort into making their tweets valuable, which is why I’d like to still read them, but on my schedule and from my inbox.

## Preparation
1. I’m using Zapier for this. You’ll need a free Zapier account which will be connected to your Twitter account and your Gmail account. If you don’t feel comfortable giving Zapier that type of permission then this workflow won’t work for you. You can find details on how Zapier handles 3rd party account credentials [here](https://zapier.com/help/account/data-management/data-privacy-at-zapier).
2. You’ll need to create a list on Twitter of the accounts you want a digest of.

## Setting up the list 
In your Twitter account go to the Lists page. (You can find this in the sidebar or by going to https://twitter.com/YOURUSERNAME/lists.) Click the button at the top right to create a new list, then enter a name and description for the list. I always make my lists private, but both types of lists will work.

![setting up list on twitter](/images/2019-12/tweets-via-email/tweets-via-email-1.png)

Next add the accounts you want a digest from as “members” of the list. Click Done when they have been added.

![adding members to twitter list](/images/2019-12/tweets-via-email/tweets-via-email-2.png)

## Setting up Zapier’s integration
You can see an overview of how this Zap (the name Zapier gives their integrations) works [on this page](https://zapier.com/apps/gmail/integrations/twitter/14730/get-a-digest-of-tweets-from-a-list-in-gmail-on-your-own-schedule). Click the Try It button and you will be prompted to log in to your Zapier account.

Next, you’ll need to allow Zapier to connect to your Twitter account. Once that’s done, select your Twitter account from the list and click Continue. Then choose the list you created in the step above and click Continue.

![connecting zapier to twitter](/images/2019-12/tweets-via-email/tweets-via-email-3.png)

In the testing step Zapier will use the settings you specified to go out and pull some data. This allows you to be sure it’s pulling the correct information. It’s useful to have Twitter open to your list in a different tab so you can confirm that the three tweets Zapier pulls match the most recent three tweets in your list. 

If everything looks right, select the most recent tweet and click Done Editing.

You’ll want to the second step, **Append Entry and Schedule Digest**, before moving on. I gave mine a title and chose a daily frequency for 5 am. Make sure to run a test to make sure this step works correctly.

![editing zapier entry and scheduling](/images/2019-12/tweets-via-email/tweets-via-email-4.png)

Finally, you’ll need to connect your Gmail account. Zapier isn’t an email service; it needs to use your email account in order to send the email. In my case the email is sent and received using the same email address, but you could also send an email from your email address to just yourself or to a group of people. 

Here’s a look at some of my settings for the email:

![email body settings in zapier](/images/2019-12/tweets-via-email/tweets-via-email-5.png)

Once you have the settings the way you want you can send a test email. I played around with some of the settings, in particular the body type (plain vs html) before I landed on these settings. Experiment and see what works best for you. Please note that the test email you receive will only have the most recent tweet from your list! As new tweets appear they will be added to the digest and sent together as a single email in the time frame you specified in the second step.

The last step is to turn your Zap on. Congratulations! 

If you run into any issues, check out the Guide in the right sidebar of the Zap settings. It has good instructions for each step of the process.

![finding the zapier guide in the sidebar](/images/2019-12/tweets-via-email/tweets-via-email-6.png)

<center>❧</center>
<center><small> *[Photo by SOMEBODY](https://unsplash.com/linklinklink)* </small>

---
<center>
📨 Mindful content delivered to your inbox. <br>[Click here to subscribe.](https://mailchi.mp/269014a38d08/adamtervort)</center>