---
layout: post
title: 4 Ways to Stop Bugs from Eating Your Software Budget
date: 2014-06-04
description: Developing custom software is expensive and risky. In fact, 60% of all software projects end in failure. Bugs account for 80% of nationwide software costs and those bugs will present themselves slowly, over time.
author: Byron Sommardahl 
excerpt: Developing custom software is expensive and risky. In fact, 60% of all software projects end in failure. Bugs account for 80% of nationwide software costs and those bugs will present themselves slowly, over time.
image: https://acklenavenue.com/img/posts/bugs-eating-software.png
thumbnail: https://acklenavenue.com/img/posts/bugs-eating-software.png
ImageCredit: Thumbnail Photo by [Parvana Praveen](https://unsplash.com/@parvana_praveen) on [Unsplash](https://unsplash.com/)
type: article
keywords: custom software development, agile, TDD, Pair Programming, Clean Code, QA Testers, Bugs, development 
tags: tips_,_tricks_&_secrets
---

People who complain about paying $149 for a shrink wrapped copy of Quickbooks Pro have obviously never been in charge of a custom software development project. Developing custom software is expensive and risky. In fact, 60% of all software projects end in failure. But why so expensive? Well, for one thing, custom software doesn't build itself. Software developers are some of the highest paid folks in the workforce. For another thing, those highly-paid software developers don't just create software. They create bugs.

Bugs account for 80% of nationwide software costs according to [Initial State](https://initialstate.com), a company that specializes in providing log analysis tools to debug products. They also claim that development teams DELIVER, on average, 15 bugs per 1000 lines of code. To give you some perspective, a medium sized software project might be around 50,000 lines of code. So, on delivery day, when everyone feels really good about the software going live, there are somewhere around 750 unknown bugs hidden in those 50,000 lines. Those bugs will present themselves slowly, over time.

**Bugs are harder to fix as they age.** The longer we wait, the more developer time it takes. Why is that? It happens because developers are human beings with finite memories. As days go by, they forget how a piece of code works internally, constantly going on to focus on the next section of code. Or worse, the original developer is not on the team anymore. This is especially a problem when the software developer who introduced the bug was using non-standard (or clever) techniques, poor naming conventions, or low/no test coverage.

Another reason bugs are harder to fix as they age is similar to the roots of a tree. Over time, a trees roots grow, stretch, wind, and meander farther and farther out. Suppose there is a tennis ball nestled in there amongst the roots. The longer we wait to remove the tennis ball, the harder it will be (and the more damage we will do) to remove it. The same is true for bugs in code. The code base around the bug grows and the bug actually starts becomming an almost inseparable part of the application.

**Bug are expensive today and more expensive next month.** So, what can we do? Well, Acklen Avenue has been answering this question for a few years with quite a bit of success. Here's what we do:

### 1. Entire Team Focused On Delivery
Software developers have a tendency of focusing so intently on a problem to solve that they lose the big picture. It's important to help them stay cognizant of the overall goal which is "delivery of working software". We do this by keeping the concept of "delivery" in front of the entire team in all our information radiators. We talk about "delivery" in our daily meetings. We have made "delivery" an integral part of our team culture. By keeping "delivery" at the forefront, every part of our development team is focused on getting the product ready to ship. This results in less bugs on delivery day because everyone has been working together to eradicate them.

### 2. QA Testers Run With Developers
QA is essential to finding bugs as quickly as possible. It's not enough to test things at the end of a cycle. We need to find them sooner. Instead of a separate department or outside group, our QA testers are bona fide members of our development team. When a feature is finished, it goes to the QA testers who have been looking at the feature and writing test cases for it since before it went to development. It gets tested in minutes, not days. Any bugs found go back to the developer(s) who worked on it. The feedback loop is as tight as possible to minimize the time between bug creation and fix. This makes bug fixes very fast  since developers have the benefit of recollection.

### 3. Clean Code Means Faster Bug Fixes
I have a friend who keeps the books for a non-profit. Her office is something really amazing to see. There are boxes full of loose papers and receipts all over the place. There are more loose papers covering the floor. There are printers, computers, wires, and more equipment everywhere you turn. She has a desk chair at the far side of her office with some space on the desk so she can work. There's a little path cleared from the office entrance to her office chair. Although I have my doubts, she says she knows where everything is, and, in her own way, her office is organized. Now, I've been called into a number of "rescue operations", asked to help save software projects from failure. Most of the time, what I find are code bases that are organized about like my friend's office. The problem with "organizing in your own way" is that it depends on you and your memory. If you go away from your code (or your office) for a month and have to come back to fix something, it will take you twice as much time (or more) to find the problem and fix it. Then, what if you win the lottery, get hit by a bus, or just go work somewhere else? Good for you, bad for the next developer, and even worse for the software budget. At Acklen Avenue, we practice "Clean Code" techniques to ensure that our code works like most developers would expect it should. We organize sections of code in industry-standard, logical, understandable ways. We name our classes, methods, and variables with expressive names so that any developer can understand how things work. Clean code makes bug fixes faster because the bug fixer doesn't have to scratch his head so much.

### 4. Prevention is Worth a Pound of Cure
What's better than fixing bugs as soon as they are created? Never creating them in the first place! Traditional programming practices fail in this area. The "hubris-driven" way of powering through code problems as fast as possible is the primary culprit for the majority of bugs in software around the world. We have found great value in slowing down, taking the time to solve problems in understandable ways, asking lots of questions, and utilizing industry-proven bug prevention programming practices like Test-Driven Development, Pair Programming, Code Inspection and the use of SOLID Principles. The result is less bugs at delivery because they were never created!

Are software bugs expensive? You bet they are. Five minutes [googling that question](https://www.google.com/search?btnG=1&pws=0&q=are+software+bugs+expensive%3F&gws_rd=ssl) will reveal pages and pages of horror stories, statistics, white papers, and university studies.  The verdict is that bugs are a reality and an expected part of software development. But, if you are embarking on a new custom software development project, you really should consider what it takes to reduce the impact of bugs on your budget. My team has discovered that bugs, though ever present, don't have to be so numerous and destructive. Focus your team on delivery, embed QA testers alongside your developers, use techniques like TDD and Pair Programming, and get your team educated in the "art" of clean code... And you'll be well on your way to software success.

If you’d like to learn more about how Acklen Avenue can help you reduce bugs in your software projects, <a href="#contact-us">contact us today.</a>

**Sources:**

- Initial State Info Graphic - [https://initialstate.com/info](https://initialstate.com/info)
- Software Defect Reduction Top 10 List, Barry Boehn & Victor R. Basili - [http://www.cs.umd.edu/projects/SoftEng/ESEG/papers/82.78.pdf](http://www.cs.umd.edu/projects/SoftEng/ESEG/papers/82.78.pdf)
