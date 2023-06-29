---
layout: page
title: QuickReads
description: A mobile app that allows you to read chat-gpt summarized news articles of your interest.
img:
importance: 1
category: work
---

For my final project for my software engineering class, me and a group of classmates created a mobile application that allowed users to look for news articles they're interested in, and read chat-gpt summarized versions of those news articles.

Essentially, users would be able to enter a keyword which we would then pass on to an API that scraped the web for news articles containing that keyword. Then, we would pass the URL of those news articles to chat-gpt which we would use to summarize those news articles.

The frontend of the app was coded mainly in React native, while the backend used Amazon Elastic Beanstalk and was coded mainly in python. Overall, the app was fully functional and allowed users to login with their Google account, as well as bookmark certain articles for future reading.

You can check out the project <a href="https://github.com/stgandham1/QuickReads">here</a>.