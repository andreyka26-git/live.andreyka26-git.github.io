---
layout: post
title: "Interview experience at AWS in 2021"
date: 2021-02-01 18:56:09 -0000
category: Software Engineering Life
tags: [softwareengineeringlife]
description: "Real AWS interview experience 2021: detailed coding questions, system design tasks, behavioral interviews, and leadership principles. Learn from actual HackerRank problems, notification system design, and 40+ behavioral questions across 5 interview rounds. Complete breakdown of Amazon's interview process, what they asked, why I failed, and lessons learned for FAANG interviews."
thumbnail: /assets/2026-02-01-interview-experience-at-aws-in-2021/logo.png
thumbnailwide: /assets/2026-02-01-interview-experience-at-aws-in-2021/logo-wide.png
---

* TOC
{:toc}

<!-- You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see useful information and inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 12 -->




<br>

# **What this article is about**

This is not a success story, because I didn't pass the Amazon interview.

This is a story about my Amazon interview experience and why I didn't like it compared to other FAANG companies. I will also answer questions like: **what exactly they asked, what were the coding tasks, what was the system design question**.

In general, this article is about my experience: what the interviews were like, what was hard, what was not, how I prepared, and how much luck matters.




<br>

# **Start - Amazon offer**

One day, on September 6, I received this message on LinkedIn.


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image1.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image1.png "image_tooltip"){:target="_blank"}


I agreed to an interview. At that time, the Amazon interview process had three stages:



1. Online coding tasks without interviewer
2. 1-hour interview with one interviewer
3. Final round with 5 interviews, 1 hour each


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image7.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image7.png "image_tooltip"){:target="_blank"}





<br>

# **Interviewing at Amazon**

From the moment I understood that I would interview at Amazon, I started grinding LeetCode, because it was my weakest part in interviews (at least I thought so). It was not going great, but was slowly improving.

All interviews were online because of COVID.

Now about the first stage.




<br>

# **First stage (done)**

On HackerRank I got 2 tasks, I solved only one. Important note: for each task I had to **explain the solution**.

Sorry for the bad screenshots, I was afraid Amazon could detect screenshots 😅 Next ones are better.




<br>

### **First problem**


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image8.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image8.png "image_tooltip"){:target="_blank"}





<br>

### **Second problem**

I didn't solve it, my brute force solution timed out, I needed dynamic programming.


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image11.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image11.png "image_tooltip"){:target="_blank"}





<br>

# **Second stage (first try)**

I thought if I didn't solve all the tasks - I'd be rejected. But then I got this email.


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image3.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image3.png "image_tooltip"){:target="_blank"}


I was surprised but happy.

After some time, they scheduled a second stage: 1-hour interview. I googled and understood Amazon loves **Leadership Principles** questions. So I learned all the principles, prepared examples from my small experience (3 years), and continued grinding LeetCode.

The interview day came (early October). We started talking, the interviewer explained the interview, and I realized I prepared for **completely wrong things**.

The interview was about **behavioral questions, Linux, and networking**. 
I'd been a Windows user since I was 4 years old. My Linux experience was minimal, only some on-prem stuff for pet projects. Networking knowledge - only theoretical from books.

I didn't record the interview, but wrote down some questions:



* How to delete a file in Linux?
* You deleted a file but disk space is not freed, what to do?
* You see there is no internet on the machine, what to do?
* How to find the biggest file in Linux?
* How to pipe output from one command to another?
* The disk is full on the server, how to troubleshoot?
* In one region the latency increased, others are fine, how to fix and troubleshoot?

Behavioral question I remember: 
**Tell me about a situation when you had an uncomfortable task and how you overcame it.**

After a few days, I got a rejection email.


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image10.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image10.png "image_tooltip"){:target="_blank"}


But then I got another email.


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image6.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image6.png "image_tooltip"){:target="_blank"}


Of course I agreed. My top career ambition is to be in FAANG.




<br>

# **Second stage (second try, done)**

This time the interview was mostly behavioral questions like: 
"Tell me about a situation when you had a conflict with a colleague and how you resolved it and what impact it had on the project."

I exaggerate, but in all interviews there were like **40-50 behavioral questions** (see stage 3). For me, it's too much.

Luckily, the feedback was positive and I moved to stage 3.




<br>

# **Preparation - LeetCode, books**

I won't write much here, because nobody cares how a rejected guy prepared.
More details are in my Microsoft/Google/Snowflake interview articles.

Shortly: I solved **114 LeetCode problems** and even recorded this moment.

I read **"System Design Interview"** (didn't like it much) and reread **"Designing Data-Intensive Applications"** by Kleppmann (as always, amazing).




<br>

# **Third stage (reject)**

Amazon gives the final round feedback by phone, which surprised me. I'll describe all 5 interviews based on the feedback analysis.




<br>

## **1 System design**

The first interview was system design. I liked it. Not many behavioral questions (3-4), the task was reasonable, the interviewer was nice.

Later I found him on LinkedIn: 14 years at IBM and many years at Amazon. It was an honor to interview with him, especially on system design.

Task: design a **notification system** that sends notifications when requested by external services.

My solution (not perfect but meets requirements):


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image4.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image4.png "image_tooltip"){:target="_blank"}


Later from the feedback I understood that my system design was **better than expected**. But the good news ended there.




<br>

## **2 Coding**

5-6 behavioral questions and a trivial task: 
**find files with specific extension and size.**

Problem: I had no idea how to get the file size from code, never did it before. I didn't understand what the interviewer expected.

My solution:


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image12.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image12.png "image_tooltip"){:target="_blank"}


Actually, I should have assumed there are system calls returning file/directory objects. But they said the solution was OK.




<br>

## **3 Behavioral**

Yes, a full hour of questions like: 
"Tell me about a situation when you had a conflict and how you solved it and what impact it had."

They ask **8-13 questions per hour**.

I had 3 years of experience and ~10 prepared stories for leadership principles. I quickly ran out of stories and started reusing the same stories from different angles. It was annoying. Too much focus on this, in my opinion.

But the feedback was OK.




<br>

## **4 Coding (or how an Irish guy destroyed me)**

From the start, the interviewer wasn't happy. I asked "how are you", and got an answer like: 
"as usual, no time for anything, but okay".

The first question was an OOP task for Amazon lockers. Frankly I didn't know this concept in real life, there were no Amazon lockers in Ukraine back then. I didn't understand the requirements and asked clarifying questions for ~20 minutes.


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image5.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image5.png "image_tooltip"){:target="_blank"}


By his tone, I felt he was doing his other work in parallel. Probably the "rejection" decision was made during the first 10 minutes already.

After 20 minutes he stopped me: **"unfortunately we ran out of time"**. Then 3-4 behavioral questions.

Then, 20 minutes before the end, he gave another coding problem.


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image2.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image2.png "image_tooltip"){:target="_blank"}


Later I found out it was similar to LeetCode, but harder. 
Here's the [discussion on the Leetcode](https://leetcode.com/discuss/post/545748/amazon-subsidiary-phone-concatenated-wor-uajg/) created by a guy who got exactly the same problem, and [variation of the problem on the Leetcode](https://leetcode.com/problems/concatenated-words/description/).

 
I had 20 minutes left. I panicked and couldn't solve it.


[![alt_text](/assets/2026-02-01-interview-experience-at-aws-in-2021/image9.png "image_tooltip")](/assets/2026-02-01-interview-experience-at-aws-in-2021/image9.png "image_tooltip"){:target="_blank"}


This is what I wrote (wrong solution). He asked for the complexity, but interrupted again with **"unfortunately we ran out of time"**.

Honestly, if this was expected, I'm not on that level to solve it in 20 minutes with clarifying, coding, and complexity analysis.




<br>

## **5 Behavioral**

Very nice person. The first half was relaxed, like chatting. In the second half he drilled into details so deeply that I felt like a murder suspect and he was a detective.

Leadership principles questions are exhausting. I'm fine with them, but not so many.




<br>

# **Feedback**

Feedback was given by phone, no proof. Short version:


    You are a great guy, exceeded expectations in system design, but coding was very bad. So no, come back in 12 months.




<br>

# **Conclusions**

I read a lot about Amazon interview loops. People say luck matters a lot. Looks like I was unlucky, but I got experience.

Everything here I also told in my [video](https://www.youtube.com/watch?v=PGh4fNp6Y18), if you don't want to read.

Thanks for reading, waiting for feedback!

