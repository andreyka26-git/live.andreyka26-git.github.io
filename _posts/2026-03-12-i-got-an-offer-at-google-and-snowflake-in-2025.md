---
layout: post
title: "I got an offer at Google and Snowflake in 2025"
date: 2026-03-11 18:32:44 -0000
category: Software Engineering Life
tags: [softwareengineeringlife]
description: "Real Google and Snowflake interview experience 2025: LeetCode preparation, system design, CV tips, and offer results. How I got offers at Google and Snowflake after 4 years at Microsoft, plus lessons from 48 applications."
thumbnail: /assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/logo.png
thumbnailwide: /assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/logo-wide.png
---

* TOC
{:toc}

<!-- Copy and paste the converted output. -->

<!-- You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see useful information and inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 5 -->




<br>

## **Quick intro**

In the [last article](https://live.andreyka26.com/i-left-microsoft-after-4-years) we discussed the reasons to leave Microsoft after 4 years. 

As a continuation - today we are talking about my interview experience in 2025-2026 and the results: I got an offer at **Google** and **Snowflake**.




<br>

## **Preparation**

In December 2024 - January 2025 I was thinking about which country I would like to live and work in, and the top candidates were Ireland and the Netherlands. I definitely wanted to work on high-load backend projects, so again it was FAANGs and tier-2 companies with the typical interview flow: LeetCode + System Design + behavioral.

The last time I had interviewed was in 2021; since then I had done almost no LeetCode or System Design study for four years until 2025. I realized I would need at least 2-3 months 3 hours per day. I knew my system design was strong - I had always gotten positive feedback on it - but my Achilles' heel was LeetCode and algos.




<br>

### **Leetcode**


[![alt_text](/assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/image3.png "image_tooltip")](/assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/image3.png "image_tooltip"){:target="_blank"}


I started doing LeetCode in February 2025 and I still do it. 

*If you'd like to join me and my community to solve problems every day - join my [Telegram channel](https://t.me/programming_space); we solve and discuss LeetCode Daily challenges there.*




<br>

#### **Intelligence & Leetcode**

I already shared my thoughts about intelligence before. In general, I think leetcode tests the cleverness and intelligence of the candidate. By intelligence I mean the ability of a person to solve unknown problems, or speed of solving such unknown problems. In the world of IQ it is called [fluid intelligence](https://en.wikipedia.org/wiki/Fluid_and_crystallized_intelligence).

I thought I was smart because at my hometown school I was pretty good at math. All Ukrainian students had to pass national independent exams in 2016, and I got 170/200 in math, which was not bad. But I had really tried hard - studying, going to extra lessons with different teachers for two years before that exam. Then I met my university classmates who got 199/200 and had prepared for fun for two weeks. That was when I realized I'm not that smart; during our studies I was reminded of it a few times, when they grasped the material three times faster than me and solved problems and puzzles I couldn't solve at all.

What I was better at was grinding and discipline - what else could I do to compensate, right? I was able to grind for a long time and build my [crystallized intelligence](https://en.wikipedia.org/wiki/Fluid_and_crystallized_intelligence), and perform at the same level just because “I've seen this kind of problem before.” That’s how I got my first job and grew to higher positions: not because I was smart, but because I grinded a lot, Lineage2 24/7 style.

The conclusion is that I’m bad at building intuition for new problems, because that is literally the “fluid intelligence” aspect. So I need to take the “crystallized intelligence” route and grind all LeetCode patterns that exist, so that I see “known” problems in the interview.




<br>

#### **How did I prepare**

I had maybe 170-200 problems already solved before Microsoft, but after four years I didn't remember any of the solutions - so for me it was essentially the same as starting from scratch.

 
The goal was to learn different [leetcode patterns](https://leetcode.com/explore/interview/card/cheatsheets/720/resources/4723/) (don't confuse these with design patterns), because most interview problems are some variation of them - e.g. dynamic programming, graphs (BFS/DFS, Dijkstra, topological sort), sliding window, monotonic stack, etc.

Patterns are the typical approaches (literally code templates) for a type of problem to solve it optimally. You might come up with some on your own; others are better to learn beforehand.

My plan was to do the following study lists:



* [Leetcode 75](https://leetcode.com/studyplan/leetcode-75/)
* [Top 100 liked](https://leetcode.com/studyplan/top-100-liked/)
* [Top Interview 150](https://leetcode.com/studyplan/top-interview-150/)

For consistency I started doing streams ([first stream](https://www.youtube.com/watch?v=p57HDCfM9jU)) where I was solving leetcode problems in front of an audience to emulate real interview nervousness.

My personal recommendation would be TO ONLY DO LISTS, don’t even waste time on Leetcode Daily challenge. Most of the daily problems are bs, they don’t test most popular leetcode patterns, you won’t learn anything. On the other hand, lists are divided by patterns making you repeat the same topic to learn it better, and they have mostly good problems so you don’t waste your time on useless trash problems.

If you haven’t done leetcode for a long time I would suggest to do the following approach:



* first do all easy problems in these lists
* then do all medium problems in these lists
* (optionally) do all hards in these lists

While you are solving - note each pattern, the code template, and a couple of canonical problems for this pattern. Believe me it is extremely helpful to “catch up” with everything 30 minutes before your coding interview.


[![alt_text](/assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/image5.png "image_tooltip")](/assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/image5.png "image_tooltip"){:target="_blank"}


My honest opinion: you must solve all the easy and mids in the lists and feel comfortable about them to say you are “ready for an interview” = 150-200 problems at least.




<br>

### **System Design**

I would divide this into theory and practice




<br>

#### **Theory**

For System Design I always reread “Designing Data-Intensive Applications” by Martin Kleppmann (aka the boar book). A second edition is coming soon.


[![alt_text](/assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/image4.png "image_tooltip")](/assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/image4.png "image_tooltip"){:target="_blank"}


This is required to remind you of some theoretical fundamentals. Besides that, sometimes I was reading papers, e.g. Raft paper, Redis, Kafka, CockroachDb, Cassandra, DynamoDb docs/source code to recall how they work in the distributed environment, what are their consistency and availability guarantees. 
 
Besides that I have read “Distributed Systems” by Tanenbaum, but I wouldn’t recommend it for studying purposes. It is pretty hard to read, almost impossible for me to learn if this is a new concept and moderately good for recalling what you already know.

The knowledge from the above resources is required to be able to talk about non-functional requirements with your interviewer, and it is essential to know all of these. It would be a plus if you could give an example of real storage that you would use in the system design, with clarifications and proof that it will provide the necessary guarantees.




<br>

#### **Practice**

For beginners who are targeting jun/mid positions - I would recommend “Hello Interview”. It is pretty simple, but they have a lot of flaws, and bad design decisions that I would mark as red flags, for example:



* using Redis with Leader-follower replication in url shortener (data loss, wouldn’t fulfill uniqueness requirements)
* doing unnecessary idempotency techniques while Card Networks (they are not covered at all, btw) have mechanisms for idempotency already via authorize/capture steps.
* using RedLock with leader-follower for distributed lock, I mean Martin Kleppmann already explained in [this article ](https://martin.kleppmann.com/2016/02/08/how-to-do-distributed-locking.html)why this is a bad idea.

Another good resource is “[Jordan has no life](https://www.youtube.com/@jordanhasnolife5163)”. The guy is ex Google and I liked his solutions much more than those from Hello Interview. I never found any severe “red flag” there.

Besides that, during that time Vlad Ten was doing his “System Design” [courses](https://www.youtube.com/watch?v=i-FFVM4cIXQ), and he gave me an opportunity to be a lecturer for practical sessions.

From that point on I had two reasons to “redo” all top 10-15 System Design problems.

The approach: I typically followed these steps:



* Do my own system design solution, cover typical functional and non-functional requirements.
* Watch others’ solutions, and see what is the difference, what might not work here, what can be done better? Extend my solution with better parts of someone’s solution.
* Ask more senior friends that are much cleverer than me to review the solution, or ask them about a particular technical problem. Kudos to [Nazarii](https://www.npiontko.pro/), my first tech lead in the first company, as he helped with many many questions.
* Ask people who were working on a real production project that the system design topic covers; I had a bunch of people from Teams, some people from Wise to ask questions about Payment Systems, Messaging Systems, etc
* The final one - write a POC + run benchmarks. With today's AI tools it is typically a few evenings.

Yes it is time consuming and hard, but I find it extremely useful and enjoyable. I typically post my articles in [my blog](https://andreyka26.com/payment-gateway-stripe-system-design-with-microsoft-engineer), so that other people can add more technical feedback to make it better.

One important thing - typically real production systems would work quite differently than in canonical System Design Solution. The main reason is money. When you grow so big that you have distributed challenges - your product is probably making a lot of money, so it is much more beneficial to reduce cost than making a new feature.

One more “unpleasant” fact - you cannot be sure your solution is going to work, unless you did POC with benchmarks. But it does not mean you need to do a POC for all of the system designs (however you can easily do it with AI). The goal is to learn how to make it formally “scalable” and have some high degree of probability that it will work on some loads.

In my case, I did these top 10-15 System Design questions, e.g. Google Search, Uber, Ticketmaster, Stripe/Revolut, Messenger, and created a couple of [simple POCs](https://github.com/andreyka26-git/andreyka26-distributed-systems) or simulations and it was enough for me.




<br>

## **Application & Job market**

I started applying in May 2025. I created a basic CV in Canva and sent a couple of applications to **Cloudflare**, **Mastercard**, **Booking** and **Uber**.

Since I had 3+ years in Microsoft in my CV working on a large highly distributed system - I thought that I should be on the top of the pile, but it was not the case. I got a bunch of auto rejections on CV level from ALL COMPANIES, and realized I need to put in more effort than I expected. 





<br>

### **Wave 1 - Confidence**

 
I recreated the CV with a different template (still in Canva), reformatted it, added more measurable impact points, and checked it on Applicant Tracking System (ATS).

Besides that I sent it to my friends for review, fixed their comments and was ready to continue my journey.

I just opened my phone, and started applying to everything I saw there that had a dev office in the Netherlands, Ireland or England). A bunch of companies that I was applying to were not in my preferred locations, but I applied anyway, because it is good for interview experience. Besides that - it might give me additional leverage in the negotiation phase as you never know what they would propose in the offer.

I applied to the following companies:



* **Google** (referral), **AWS** and **Meta** - got online assessment for AWS, for Google and Meta - got a call with a recruiter with follow up for a technical interview.
* **Wise** - required recent Java experience that I didn’t have - so I was rejected but on recruiter call level.
* **Apple**, **Uber** (again with referral), **Bolt**, **Cloudflare**, **Mastercard**, **Visa**, **Revolut** - CV level rejection.

I knew this wasn't enough, so I had to continue.




<br>

### **Wave 2 - Uncertainty**

Given the majority of CV-level rejections, I was not that confident anymore, but I kept applying to tier-2 product companies:



* **Snowflake** - got a call with a recruiter with follow up for a technical interview
* **Stripe** - Recruiter call reject
* **Docker**, **Salesforce**, **MongoDB**, **Gitlab**, **X**, **Deepl**, **Binance**, **Spotify** - CV level rejection

This wave demoralized me a lot, let’s be honest, but I kept preparing and applying still with some feeling that I might not get an offer this season.




<br>

### **Wave 3 - Desperation**

I signed up for LinkedIn alerts and started applying on LinkedIn as well to almost all companies that provide relocation packages in Ireland (and some of the popular ones just to try myself):



* **Intercom**, **Wincent** - got a recruiter call with follow ups.
* **IKEA**, **Workday**, **Redhat**, **Miro**, **Contentful**, **DocuSign**, **Vercel**, **Playstation** - CV level rejection




<br>

## **Results**

In my previous article about Microsoft offer - I included offer email as confirmation, but unfortunately these days the offer details are mostly communicated verbally during the call, and I don’t want to be on the ban list.




<br>

### **Snowflake Offer**

After the recruiter call - I got technical screenings and an onsite interview loop (in Dublin). It was my first onsite interview and a good opportunity to see Dublin, as they pay for flying tickets and hotel. I cannot say much about the interview, but in general it is a FAANG level experience, I enjoyed it a lot.


[![alt_text](/assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/image2.png "image_tooltip")](/assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/image2.png "image_tooltip"){:target="_blank"}


In the end they sent me an offer that I accepted.




<br>

### **Google Offer**

It was a tricky one. 

I made a huge mistake - I hadn't familiarized myself with their leveling system. The position stated “**Software Engineer II, Cloud web - EU Headquarters**”. I genuinely believed it was for a mid-level software engineer, because at Microsoft Software Engineer II is level 61-62, i.e. mid-level.

But it wasn't: Software Engineer II is junior at Google.

The interview was a regular FAANG level interview, a bunch of technical screening interviews with an interview loop (but online). All of them were technical algo/ds interviews with one behavioral in the interview loop, because Google does System Design only for Senior+ positions :(

In the end I got an offer at junior level and rejected it because of that. But overall I was very happy to interview there, it was a great experience with great people.




<br>

### **Interview Rejections**

**AWS** - I didn't pass the online assessment; I solved the problems but with bad runtime.

**Meta** - got rejection after coding and Linux troubleshooting interviews (the most interesting interview type so far), however I performed well.

**Intercom** - I passed all the interviews and was “accepted” for middle level, but they closed the role, and ghosted me for 2 months, and then replied that there is another position opened, but it was too late. Technically I passed, but in reality there was no offer. This was the first company that had an “AI” interview, where you need to build the app in 2 hours by using AI.

**Wincent** - it was a DevOps position, and interviewers roasted me completely. They expected deep infra knowledge, like NUMA, Terraform, Kubernetes, and extremely deep TCP/IP stack knowledge.

All other companies rejected on CV/recruiter screening level. Overall, the statistics are pretty depressing: 2/48 offers.


[![alt_text](/assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/image1.png "image_tooltip")](/assets/2026-03-12-i-got-an-offer-at-google-and-snowflake-in-2025/image1.png "image_tooltip"){:target="_blank"}





<br>

## **Learned lessons**




<br>

### **Resume**

Put a lot of effort into making your resume look good. Run it via ATS checker. Probably companies have a “cap” of positions you can apply within a year or half a year. Once you get 2-3 rejections - probably it autorejects all subsequent ones.

Get feedback about your resume from friends or other recruiters. It will sound weird - but check it with ChatGPT as well.

Only “countable” impact points in your CV. “Worked on search engine performance improvement” -> “Improved performance by 30% on every request, thus reducing latency, and infra cost (by 5%).”




<br>

### **Preparation**

**Only Leetcode lists**. Don’t even waste your time on daily problems or random problems. Just do topic by topic in a consistent way, try to pick mostly “liked” questions. Write notes about every pattern with template and “canonical” problems.

**Only Python**. I was solving LeetCode with C# initially, then I switched to JS (because C# is cumbersome and takes longer to write the same thing), and eventually I switched to Python. Python is the best - not only does it have all the necessary data structures, it is extremely compact and has a lot of shortcuts and syntax sugar.

**More leetcode**. Even though I solved close to 200-300 problems before the interviews - I still failed some of the leetcode interviews that might not have been failed, and got stuck with problems that I might not have been stuck with.

**System Design - ideal**. I don't have much to add - I have had zero failed System Design interviews in my life so far.

**Apply on the company website directly**. It is my personal feeling, but I felt very little return from LinkedIn applications, and much more from direct ones.

**Apply with a referral**. It does not guarantee anything, but increases the chances.




<br>

## **Conclusion**

Thank you for reading. Please consider everything written here as my personal opinion/experience, and please share your recommendations and experience in the comments. Don’t forget to subscribe to social media ([Telegram](https://t.me/programming_space), [Instagram](https://www.instagram.com/andreyka26_se/), [X](https://x.com/andreyka26_), [Youtube](https://www.youtube.com/@andreyka26_se)) as we are doing leetcode, system design, talking about life in Dublin, AI, FAANGs, etc. Sharing as well my pet projects: [Pet4Pet](https://pet-4-pet.com/), [SyncSymptom](https://syncsymptom.com/).

