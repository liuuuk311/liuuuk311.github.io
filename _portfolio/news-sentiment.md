---
title: "News Sentiment Bot"
excerpt: "A Telegram bot that analyzes the new sentiment for a given newspaper article"
permalink: "/portfolio/sentiment-bot/"
date: '2018-04-01'
header:
  teaser: /assets/images/portfolio/sentiment_bot/logo.png
sidebar:
  - title: "Role"
    image: /assets/images/portfolio/sentiment_bot/logo.png
    image_alt: "logo"
    text: "Developer"
  - title: "Technology used"
    text: "Python, IBM Watson, Telegram APIs"
gallery:
  - url: /assets/images/portfolio/sentiment_bot/Screenshot_1.jpg
    image_path: /assets/images/portfolio/sentiment_bot/Screenshot_1.jpg
    alt: "News Sentiment Bot Screenshot 1"
  - url: /assets/images/portfolio/sentiment_bot/Screenshot_2.jpg
    image_path: /assets/images/portfolio/sentiment_bot/Screenshot_2.jpg
    alt: "News Sentiment Bot Screenshot 2"
---

*Warning: This is project is not public available anymore.* 

In April, I developed a Telegram bot to experiment with the IBM Watson AI platform. This project is just a proof of concept and is not available at the moment. 

For this project, I used Python to develop the server. Using a library, I could access at IBM's AI platform. It offers a lot of options; I choose to use the sentiment classifier and the entity extractor.

You can send any link to the bot; it will parse it, and IBM Watson will tell the sentiment prediction. Then the bot will wrap the outcome in a nice message.  

{% include gallery caption="These are some screenshot of the bot." %}

## Features
* It parses any website
* Sentiment analysis available in different languages
* Summary through entity extraction
