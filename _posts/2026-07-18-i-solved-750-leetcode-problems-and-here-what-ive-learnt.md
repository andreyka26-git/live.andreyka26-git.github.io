---
layout: post
title: "I solved 750 Leetcode problems and here's what I've learnt"
date: 2026-07-18 20:25:57 -0000
category: Software Engineering Life
tags: [leetcode]
description: "I solved 750 LeetCode problems and got Google, Microsoft & Snowflake offers. Here are the patterns, strategies, and lessons for FAANG interview prep."
thumbnail: /assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/logo.png
thumbnailwide: /assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/logo-wide.png
---

* TOC
{:toc}


<br>

## **Why you may want to read this article**

When I was preparing for all my Big Tech interviews - the first thing I was doing was Leetcode, as this part exists almost everywhere for software engineers.

I have been doing Leetcode since 2020, solved 750 problems, got a Leetcode cap, and landed 3 big tech offers (Google, Microsoft, Snowflake), and today we will talk about how you should approach Leetcode for interview preparation, the tricks and lessons I learnt over the course of these years.




<br>

## **Chronology**




<br>

### **2020**

I had just got the fake Senior role at Epam Systems, and was thinking about what’s next. The answer automatically came to my mind: Big Tech. I still know my tech lead from the first company, who got a few offers from Microsoft and AWS (but rejected them).

His advice was simple: do Leetcode. And I started doing Leetcode.


[![alt_text](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image1.png "image_tooltip")](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image1.png "image_tooltip"){:target="_blank"}


After writing enterprise C# code for 2-3 years in outsourcing companies and matrix multiplication in uni - Leetcode problems seemed to be EXTREMELY hard to me, which is expected. I was never a smart guy.

At that time it was a fight for my EGO; I generally couldn’t believe I couldn’t solve some mid problem. So I kept being stuck on the same problems for 2-3 days, blindly trying to come up with the solution.

It was a strong ego hit. But it was even stronger when I eventually gave up and checked the solution, thus realizing - there was no way in the universe I could have come up with that on my own.

I was demoralized and stopped doing Leetcode after a few months.




<br>

### **2021**


[![alt_text](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image5.png "image_tooltip")](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image5.png "image_tooltip"){:target="_blank"}


One recruiter from AWS contacted me for the interviews in September 2021. A Microsoft recruiter contacted me in October. I realized this was my chance. Of course I agreed and started preparing again. 
 
This time, if I couldn’t solve the problem in 2-3 hours - I looked for a solution. Mainly because I had a tight deadline, so ego was a lower priority. I decided to do lists, and the choice landed on “[Top 100 Liked](https://leetcode.com/studyplan/top-100-liked/)”.

My learning though was pretty random, so I was confusing dp with divide and conquer and with general recursive problems, for example, as I was learning via practice only. But I definitely saw the progress.

Before the interview I had solved all easy/mid problems from there and a couple of random questions on Leetcode.

On my Instagram, I posted a [story on the 8th of Dec 2021 ](https://www.instagram.com/stories/highlights/17939340292663489/)6 mins before the interview showing I had **147 solved problems**.

Spoiler: I failed the AWS interview and passed the Microsoft one.




<br>

### **2022, 2023, 2024**

Didn’t do any Leetcode, as I was busy with relocating, keeping up with Microsoft stock, a bunch of surgeries, and promotions.




<br>

### **2025 Prime**

I was pretty pissed with the Visa I had, and with on-hire stocks about to run out soon, so I started looking for other opportunities.


[![alt_text](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image4.png "image_tooltip")](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image4.png "image_tooltip"){:target="_blank"}


After 3 years of rest, I had forgotten almost everything. So I started from scratch with lists:



* [Leetcode 75](https://leetcode.com/studyplan/leetcode-75/)
* [Top Interview 150](https://leetcode.com/studyplan/top-interview-150/)
* [Top 100 Liked](https://leetcode.com/studyplan/top-100-liked/)

Besides that, I started streaming on the Microsoft terrace, solving Leetcode live so that I would feel the exact same stress of another human being watching me do and explain things.


[![alt_text](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image3.png "image_tooltip")](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image3.png "image_tooltip"){:target="_blank"}


In July/August I finished interviews, got offers from Google and Snowflake, so it was done.

Now I just wanted to have some merch from Leetcode, as some of my colleagues had T-shirts, and I didn’t. So I decided I would continue doing Leetcode Daily, collecting coins and getting the Leetcode cap (6500 coins).




<br>

### **2026**

Recently I got a Leetcode cap. To be fully honest, my friend just ordered it for me because he can. Thanks to this generous man. But that does not count, right? So I grinded all these coins anyway, and now I’m eligible to wear it.


[![alt_text](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image6.png "image_tooltip")](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image6.png "image_tooltip"){:target="_blank"}


For now I only keep doing that because:



* I am just used to
* It is a good “keeping me warm” thing, so I’m less stressed about layoffs, etc
* It is some “glue” content for social media
* At some point I want to get a leetcode hoodie for 16000 coins.

Right now I have 750 problems solved, 343 days of Leetcode daily streak.




<br>

## **Key takeaways / Advice**

Now let me share what I have learnt during these years, and what I have done differently.




<br>

### **Run in your mind**

If you are preparing for an interview specifically - this is the most important advice for you.

This should be your plan for a specific problem:



1. Before you start writing code - have a fully compiled mental model of your solution; you should “see” your array/graph or hashmap, what will be happening to it, and how the solution will return the correct answer.
2. Only after having a very specific mental model of the solution do you implement it, following a specific plan.
3. Before clicking “Run” or “Submit”, you should debug your code line by line on the example input and be 100% confident it will work. Being able to do this fast is probably one of the most important skills.
4. When you click Run and Submit, you should 100% pass the first 3 given examples that you have debugged in your mind, plus preferably all test cases along with the edge cases that you have anticipated and run against in your mind as well.

Just writing code as you go, aka “playing around” with the code, is very counterproductive, and you learn nothing by doing that at all.

Keep in mind - drawing while thinking about a solution and when you are debugging is good - but typically you won’t have access to drawing. It is better to learn drawing and debugging via comments in the code.




<br>

### **Up to 2 hours per problem**

Beware that it means 2 hours for thinking about a potential solution, maybe trying it out. If you are stuck after 2 hours - check the solution. Everything after that is counterproductive. Typically, with 70-80% confidence, the solution that you would see is never the solution you can come up with on your own. 
 
The flow:



* read problem and examples
* focus on how you can solve input from “examples”
* after 20-30 mins, if you are stuck - start reading hints, one every 10-20 mins
* if you don’t have any idea about the solution - just go to the solution tab

Note though - usually the “solution” tab by Leetcode is much harder to understand than solutions posted by people.

Sometimes Neetcode posts good solutions on Youtube.




<br>

### **How to learn a new pattern**

In general, the majority of the problems have some specific pattern. Usually it is not something that you can come up with on your own (at least not come up with fast). Initially you don’t know any of the patterns.

Specifically for that reason, you take ONLY A SINGLE pattern a day. Don’t solve problems involving 5 different patterns the same day, as it is harder to memorize and learn them.

Keep notes with the patterns and code snippets along with the canonical problem for that pattern. Believe me you will thank me later. I can recall everything in 30-60 minutes before the interview now.


[![alt_text](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image2.png "image_tooltip")](/assets/2026-07-18-i-solved-750-leetcode-problems-and-here-what-ive-learnt/image2.png "image_tooltip"){:target="_blank"}


There are simple patterns that you must know at some point: sliding window, DP, dijkstra, union find, 2 pointers, binary search, etc.

There are some advanced ones that you usually don’t want to focus on, as they are rarely asked: segment tree, fenwick tree, binary lifting, kmp, etc.

When to stop? Just cover all the patterns you encounter while solving problems from the lists.


<br>

### **You don’t need premium**

Maybe you do, but I personally never used premium at all.

If you want to solve specific problems for a specific company you are preparing for -> ask somebody with premium to send a screenshot; however, for me it worked 0 times, and I never got any of those problems on a real interview.

If some problems are “locked” - try to find them here: [https://www.lintcode.com/](https://www.lintcode.com/)

Lintcode has some “leaked” problems as far as I know, never used it myself though.




<br>

### **Do only lists**

As I've been solving Daily Leetcode for one year already - I can say that 60-70% of all the problems there are bad problems that don’t have a specific pattern to learn/recall. Some of them are very hard problems that you will never be asked on a real interview unless you are interviewing for hedge funds.

The same I can say about doing random questions - a very high chance that you’ll get a bad problem.

A few years ago, every leetcode problem had a like/dislike ratio - it was a very good indicator back then, but not anymore, as they did the same thing YouTube did.

Now you should focus on lists only; you have the 3 that I mentioned. By solving all 3 of them, you’ll have 200-300 solved problems, which is enough for an average FAANG big tech interview.




<br>

### **Can I solve any problem after 750 solved ones?**

After all this Leetcode experience, I have the following confidence / probability of being able to solve a given random (potentially bad) problem:



* easy - 99% I will solve it
* mid - 50-60% I will solve it
* hard - 20-30% I will solve it

However, for a good problem from the list it looks like this:



* easy - 100% I will solve it
* mid - 70-90% I will solve it
* hard - 50-60% I will solve it

Interesting takeaway - you cannot do better than your genetics allow. It is about general cleverness / IQ (fluid intelligence) and is capped by your genes and brain. You can do nothing about it.

I’m not that clever person (the one who comes up with solutions to unknown problems) - therefore I upscaled my potential via discipline and crystallized intelligence. But now I’m 100% sure I cannot be in the top 1-2% of these algorithm competitions, and I cannot pass hedge funds for sure with my algo skills.

But the average engineer is definitely able to reach a level that will allow them to pass up to senior positions in big tech - this is for sure true.




<br>

## **Conclusion**

I really hope you got some inspiration and useful information from the article. Please follow me on social media, as I’m solving and discussing daily leetcode there - so you’ll know which problems are bad and won’t waste your time: [Telegram](https://t.me/programming_space), [Instagram](https://www.instagram.com/andreyka26_se/), [Threads](https://www.threads.com/@andreyka26_se), [X](https://x.com/andreyka26_).

Share your tips/tricks/takeaways in the comment section as well.

