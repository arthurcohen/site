---
title: The Good News Corona Virus
date: 2020-04-16T10:07:24-03:00
draft: true
description: The Good News Corona Virus
tags:
- ReactJS
- NodeJS
---

Well, this is a very delicated subject to manage.

At March 16 I started to work at a new company, in another city, 400km far from home, in the middle of the coronavirus pandemic, and, oh boy, at first, it was hard.

There was 2 friends with me living by the next door. They supported me all the times, and we were together whenever possible, respection all the social distance and self-isolation rules.

Every time that I turned my TV on there was bad news. Each one of them. It never gets better.

We knew that people become really sensitive in that situation of isolation. In that moment, a colleague invited me to participate in the project called [The Good News Coronavirus](https://thegoodnewscoronavirus.com/) (that we preferred to call it only [The Good News](https://thegoodnewscoronavirus.com/)). [Fernando](https://www.linkedin.com/in/flasfl/) is a Software Engineer and started the project with other three people: [Maciel](https://www.linkedin.com/in/macielmelo/), [Daniel](https://www.linkedin.com/in/danielnbarros/) and [Rafaela](https://www.linkedin.com/in/rafaela-fernandes/).

I believed their goal with the website, and accepted the invite. In the next morning I was working with [Felipe](https://www.linkedin.com/in/felipesafreitas) and [Barbara](https://www.linkedin.com/in/barbara-poliana-jaber-m-ferreira-193559b9) in a 'robot' capable of search the news around the web and create reports with the data needed and some other information, that we called classification.

The classification was a attrribute that helped the people who were looking for good news. It was a number that tells if the current news is a 'good', 'neutral' or 'bad' news.

To be capable of distinguishing which classification to give to each news, firstly, we created a scheme called block list and safe list. In short, it  was a series of weighted strings, that whenever one of them were found in the news, their weight were counted and, at the end, we analyzed if the news weighted more towards the safe list or block list. Simple as that.
