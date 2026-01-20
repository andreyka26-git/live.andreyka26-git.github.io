---
layout: post
title: "I left Microsoft after 4 years"
date: 2026-01-19 07:17:02 -0000
category: Software Engineering Life
tags: [softwareengineeringlife]
description: "Why I left Microsoft after 4 years: honest insights on FAANG compensation, stock vesting, promotion paradox, and career growth. From Dynamics 365 to Teams Presence Service, getting offers from Google and Snowflake, and the real reasons software engineers leave big tech companies."
thumbnail: /assets/2026-01-20-i-left-microsoft-after-4-years/logo.png
thumbnailwide: /assets/2026-01-20-i-left-microsoft-after-4-years/logo-wide.png
---

* TOC
{:toc}

<!-- You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see useful information and inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 1 -->




<br>

## **Quick Intro**

I have been working for Microsoft for 4 years, starting in 2022. As of 2026, I left Microsoft and secured offers from Google and Snowflake, currently working for Snowflake.

This article outlines the reasons for leaving (no one leaves without a reason), what happened during these 4 years: getting into Dynamics 365, then switching to Presence in Teams, interviewing, life in Prague, etc.




<br>

### **Disclaimer**

Sometimes, for a bunch of reasons, I will be using the word FAANG instead of Microsoft, representing tier1 and most of the tier2 companies, as most of them share the same problems.




<br>

## **The life at Microsoft**




<br>

### **First Project D365**

I joined the project called Dynamics 365 in April 2022. Basically, it is a CRM for businesses, something like Salesforce. 

I need to mention that I got a bit lied to by Microsoft, as initially it was a position for multiple locations (Czech Republic, Ireland, Germany and Poland) and for multiple projects - it turned out to be a single offer for a single project in a single location.

Having purely backend experience (in .NET) and switching to CRM frontend was not that great. My expectations from Microsoft were fully ruined, because I ended up mostly working on Customer’s issues, most of which are just about them setting up the system incorrectly, moving/fixing button positions and tasks like that.

Don’t get me wrong, it would be perfect chill work, but at 22 I was way more ambitious and passionate about engineering. I made a decision: either I’m leaving Microsoft or switching projects within the company. I got lucky to be introduced to my Ukrainian friend, who later saved my life (see [appendicitis experience in CZ](https://live.andreyka26.com/surgery-healthcare-experience-prague-pt1-appendecitis)). 

He was working in Presence Service - the yellow-green-red button in Teams that tells your status: online, in a meeting, offline, etc. This was exactly the project I was dreaming about when joining Microsoft - so I immediately contacted the manager and again got lucky - they had an open position.




<br>

### **Moving from Dynamics to Presence**

When you switch projects, you might have an extremely polar interview experience in FAANG. If you are joining a different org, usually you will need to have an interview loop. Sometimes, you might negotiate with the manager and have just one interview. It really depends. In my case, I got lucky again - I just had an interview with my future teammates. Mainly talking about distributed systems, sharding, networking, etc.

Since this is exactly what I’m good at, there was a collective decision to accept my candidacy straight away during the interview - and it was my 4th luck.




<br>

### **Second Project Presence**

As I already mentioned - Presence was exactly my dream project, I encountered pretty much half of the concepts I was learning in the so famous “Designing Data Intensive Applications” by Martin Kleppmann:



* highly distributed service
* millions of requests per second
* consensus, consistency, replication and sharding

One of the most important things - I got an AMAZING team and an AMAZING manager. We became friends as most of us relocated at the same time and colleagues were the only “people” around.  I got promoted twice during my 3 years there, reaching level 62.

It seemed to be an ideal place. There was really no reason to look around, because the probability that it could be better is very low.




<br>

## **Reasons to leave**

Many of you might ask - why then?




<br>

### **Money**

What a surprise, right? As a person who came to Microsoft from Ukrainian outsourcing companies, I was very surprised by how FAANGs pay you.

*Disclaimer: I am NOT talking about Microsoft, but rather about the general approach in all tier1/tier2 companies.*

Total compensation = base salary + on-hire stocks + yearly stock bonus + yearly cash bonus (optional)




<br>

#### **Base salary**

Pretty simple - you are getting some amount of money and paying local country taxes for it. Microsoft mostly works with you as an employee (not self-employed), so taxes are pretty high.




<br>

#### **On-hire stock**

This is the tastiest piece of cake. How it works:



* company is “buying” you stock for some static amount of money, let’s say they bought you 100 shares and paid 2k EUR according to the current stock price. You don’t own stocks yet.
* The company starts transferring you these 100 shares part by part over a 4-year period, usually. This process is called vesting. Typically they divide 100 by quarters and pay you some part each quarter. Some companies might delay the first vesting by one year or so - to keep an incentive for you to stay.

The main benefit here is that stock might grow while it is not yours still. Let’s say the original 100 shares increased in price 3 times. By the end of 4 years, you will have 6k EUR instead of the initial 2k.




<br>

#### **Yearly bonus**

It sounds like most people would just go, work for 4 years and leave, no?

Actually, no. There is another incentive for the company to keep you.

Typically FAANGs have yearly bonuses based on your performance. It works exactly like an on-hire stock bonus. Some people call it “stock refresher”. The company assigns another portion of stock for you for the next 4 years. The only difference is that this bonus depends on your performance and it is bounded by the range that is defined by your level.

 
Let’s say, juniors have range 0-500 EUR stock award, mids 0-1000, seniors 0-2000. The higher level you have, the better stock you get.

During your 4 years of on-hire stocks, you accumulate these yearly stocks in such a way that by the end of on-hire stocks, you kind of stay with the same amount of money.


[![alt_text](/assets/2026-01-20-i-left-microsoft-after-4-years/image1.png "image_tooltip")](/assets/2026-01-20-i-left-microsoft-after-4-years/image1.png "image_tooltip"){:target="_blank"}


Note that the most “profitable” is actually your last on-hire stocks bonus. After that, you lower stock compensation by two.

Why do people in general stay longer? Because of promotion. In 4 years you will get much better stocks if you go up 2-3 levels, so the result won’t be 1k as in the picture.

For me, junior vs mid-level stocks were not that big of a difference.




<br>

#### **FAANGs reinforce leaving over giving promotion**

I still don’t understand why. The general rule in FAANGs is that if you are growing within the company, you are getting paid less compared to people on your level who just joined.

Consider an example:



* A junior who over 4 years grew to senior
* A recently joined senior

Typically it works in the way that a new hire senior will make much more than you. He would have a higher base most probably, and higher stocks.

From a company perspective, a junior who grows to senior has MUCH MORE value than just joining one, as he knows how everything works and is familiar with the project, team, and processes.

But still FAANG will pay the new hire more. This works like that as the more you get promoted, the closer you get to the median on your level.

That’s why it is VERY bad to join as a bit overqualified junior compared to an underqualified mid.

Besides that, the promotion process in FAANGs is quite interesting and based on your impact rather than on your real growth. I shared more details in [this article](https://live.andreyka26.com/promotion-process-at-microsoft-faang): 




<br>

### **Documents**

Since I relocated to the Czech Republic a few days before Russia invaded Ukraine, I was not able to get a proper visa, so I was staying on a protection visa for a very long time, not leading to a proper status and future in the country. This was also one of the reasons to start looking for something else.




<br>

### **Location**

I hope you still remember that the location is Prague in the Czech Republic. I like Prague as a city, but I wouldn't say it is good for Software Engineers. Apart from the big Microsoft dev center, there is no FAANG around. For sure, it is worse for employees as employers don’t compete with each other (big fish).

It is very funny that most of the employees at MS are ex/future Pure Storage, ex/future Barclays or ex/future Oracle engineers. Common scenario:



* You have a hard time getting a promotion, on-hire stocks are done, you feel poor
* You go to Pure Storage for one year
* After one year, you return back to Microsoft with a new on-hire stock package and potentially higher level
* Profit.

 
Smaller companies require B2 Czech language, which is not a big deal for me as a Slavic man, but it will still require around 1 year of effort.

Given the situation in the IT market, worth to say - the situation with investments and startups isn’t better, from the experience of my close friend (also ex-Microsoft) who has been running a startup for almost 3 years.




<br>

## **Interviews / leaving Microsoft**

Based on the reasons above, I decided to move out of the Czech Republic. I wanted another tier1/tier2 company, not in the Czech Republic, but in Europe. It deserves a separate article, but long story short: I started preparing in February 2025, and in mid-Summer 2025 I got offers from Snowflake and from Google. In the end, I decided to proceed with Snowflake.

To be continued…

