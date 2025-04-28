---
layout: post
title: "Backend is HARDER than Frontend"
date: 2025-04-28 16:14:35 -0000
category: Software Engineering Life
tags: [softwareengineeringlife]
description: "I have seen people claiming that frontend is harder than backend, as backend engineer I will disagree, it always depends, and today I will show you why backend is actually harder and what are the backend challenges."
thumbnail: /assets/2025-04-28-backend-is-harder-than-frontend/logo.png
thumbnailwide: /assets/2025-04-28-backend-is-harder-than-frontend/logo-wide.png
---

* TOC
{:toc}

<!-- Copy and paste the converted output. -->

<!-- You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see useful information and inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 1 -->




<br>

## **Intro**

I’ve seen a few people on LinkedIn and other social media claiming that frontend development is much harder than backend development. Today I will explain why it is not true, and both of them have their own challenges, so it always DEPENDS.




<br>

## **What is backend and frontend**

Before making statements about what’s harder, it would be great to have some definitions.

There are plenty of them, but I’ll try to come up with something precise enough.

`Frontend` - is the part of an application that interacts with the user and provides a presentation layer.

`Backend` - is the part of an application that is not visible to the user. It is responsible for behavior that happens behind the scenes, such as storage management and responding to frontend requests.

Every app has state – information about its current usage. For example, in game - it is game state, progress, players; in Instagram - it is your photos, messages, feed, in Gmail it is your emails, etc.

There are a few characteristics that help you determine if something is part of the frontend:



* The frontend runs on the client: a device or browser.
* It includes functionality that works once the app is loaded and does not require an internet connection.
* It is coupled to a specific device or browser - meaning if you switch devices or browsers, you won’t retain any state from the previous one.

The backend also has some clear characteristics:



* The backend runs on a server.
* Its functionality works only when there is connectivity to the server.
* It does not rely on the client device or browser - the state is shared and persists across them.

A typical example of frontend is a React SPA (Single Page Application) client, and for the backend - a set of endpoints that provide data requested by the SPA.

There’s also a hybrid approach called SSR (Server-Side Rendering). It’s mostly considered backend, with some exceptions - but let’s leave that out of scope for today.




<br>

## **Why people think backend is easy**

I saw this post on LinkedIn weeks ago.


[![alt_text](/assets/2025-04-28-backend-is-harder-than-frontend/image1.png "image_tooltip")](/assets/2025-04-28-backend-is-harder-than-frontend/image1.png "image_tooltip"){:target="_blank"}


Unfortunately, these points are the majority: “**I AsKeD gPt and it gave me 1 endpoint and database, the bAcKeND DeVs aRe NOT Needed**”.

First, task complexity comparisons are not fair. I could compare the Google search engine and a login form in React the same way.

Usually, their apps are not famous enough yet to reach the point of backend-level challenges. 

Initially, I would say most apps are harder on the frontend side, because startups mostly need good UI to attract users and just to make things work on a small scale, without any SLA.

I completely agree; sometimes, in some systems and under certain loads, frontend might be harder.




<br>

## **Real Backend Challenges that FE does not have**

Real backend challenges start when your service has SLA, so you have to **guarantee **something.

Usually, the **guaranteed** parts are:



* **Availability** - how much time your service MUST be running.
* **Consistency** - how consistent data should be; e.g. when I send $500 to my friend, exactly $500 should be deducted from my account, and he should receive $500 or when I change my profile avatar, colleagues must see a new picture in a matter of hours.
* **Latency** - how much **response wait time** is allowed.
* **Durability **- once user added data, it must not disappear




<br>

### **CAP theorem**

Let’s not forget that you might just get overloaded if your app becomes popular - either in a good way (lots of new users) or a bad way (DDoS attacks). You need to handle it somehow.

Some of the problems are in principle unsolvable: CAP theorem, meaning you cannot guarantee both consistency and availability, so you have to find this tiny tradeoff that fits your requirements.




<br>

### **Concurrency & Race Conditions**

Another complication is concurrency (same requests are accessing the same data simultaneously) that the frontend cannot even have, because they have one threaded event loop. They are one of the hardest to debug and fix, they require deep knowledge of OS, underlying mechanisms for parallel execution on the low level.




<br>

### **Infra**

I’m not mentioning that you should know tons of infrastructure for queues, databases and how guarantees I mentioned above (availability, consistency, latency and durability) work on their side.




<br>

### **Privacy**

On top of that you have privacy problems, that include, for example, data storage constraints - e.g. you cannot store EU citizen’s data outside of the EU; customer data must be encrypted, you must provide “DELETE” functionality, logs retention and various other problems you have to deal with.




<br>

### **DevOps**

Finally, Deployment and DevOps. In addition to knowing how to design and build backend systems, you should also understand how to deploy them, be familiar with best practices for CI/CD, know which containerization mechanisms to use, and how to select deployment regions to ensure availability and reliability.




<br>

### **Why do you care?**

 
I will explain. 


If you don't think about reliability, once there is a random crash, or there is planned maintenance - you have unresponsive service for an unknown amount of time, during which you are losing money and reputation.

Or if you don’t think about consistency - your money in the bank can disappear, as well as likes count in social media. People might see different avatars on your profile.

Even worse, if there is no durability, e.g. you were using distributed cache and unlucky with a snapshot, or if it is a queue that does not persist messages - you are going to lose customer’s data.

If you miss privacy guarantee - you can be simply fined.




<br>

## **When Frontend ALWAYS harder**

I can think of only one area where frontend is **99%** always harder than the backend: GameDev. The backend is usually used there for multiplayer, and for tracking achievements, progress, etc.6

If we are talking about big projects, let’s say Battlefield, Starcraft, GTA 5, etc., where, besides achievements, you have a multiplayer part - the frontend part is INSANELY harder than the backend and takes a much bigger piece of the budget and time




<br>

## **Conclusion**

As you can see - it always depends, let’s not make any overstatements.

