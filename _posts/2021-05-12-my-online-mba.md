---
bg: "infographic.jpg"
layout: post
title:  "My Online MBA Experience"
crawlertitle: "Online MBA"
summary: "Choosing an online MBA over a traditional MBA."
date:   2021-05-12 19:00:47 +0100
categories: posts
tags: ['MBA', 'Education']
author: Andrew
---


[![Infographic]({{ site.images | relative_url }}/infographic.jpg)]({{ site.images | relative_url }}/infographic.jpg) 

**Choosing an online MBA over a traditional MBA.**

Let’s start with my motivation for doing an MBA.

I have lots of expertise and skills related to my role, product management, IT and development. I started my career as a Travel Agent and moved onto to the IT side with the leading travel technology provider in the world. While I have extensive experience in finance, marketing and even law, I wanted to understand more from an executive point of view in a global business environment that has changed significantly since I did my tertiary education. (think how much the business landscape has changed just in the last 10 to 15 years). I didn’t want a view from the lens of your typical organisation but agile, startup and digital organisations.

I researched a number of traditional online institutions and very few had online programs and those that had still had a part of the course that needed some kind of physical attendance.

Eventually I discovered some online ads and articles about the PowerMBA, so I did my research as I normally do, and I found a winner.

(The infographic was conceptualised by me and I did the design brief to the last detail. I just had to get a freelance designer that was good with hand-drawn personas to actually do the design and make it look good).

1. **Democratizing Education**
This is their catch-phrase I didn’t come up with it. But it’s an accurate description of what they stand for. It’s available to everyone there are no regulations or entry barriers. All MBA programs have strict requirements for entry including work experience and/or educational qualifications.
There is also a lot less flexibility in the programs offered as they need to adhere to ridiculous educational regulations that are not really applicable to today’s business practices.

2. **Affordable**
Less than $1000 and under €900 (approximately) and if you keep an eye out for early-bird specials you can shave even more off that modest price. This is around 10% of the next most affordable, reputable online MBA program.

3. **Time**
You only need 15 minutes a day! We all know that time is one of the most valuable things and something you never get back. Time is even more precious when you have a demanding job or career and want to spend more time with your family and friends. The typical MBA is also infamously know as the “divorce course’.

4. **Easy**
The course content is delivered as micro-learning bit sized chunks, with no heavy-reading and the majority of the content delivered as video content.

5. **No Exams**
Stress free and no studying! Only quizzies that you need to pass at the end of each section to make sure you understand the syllabus.

6. **Relevant**
The content and case-studies are framed around companies that you know, and can relate to. (like Netflix, AirBnB, Waze, YouTube, and more)

7. **Perspective**
Great insights into leadership and tips from successful leaders.
One session in particular was on the topic of mindfulness and how top execs use meditation or similar practices to take mental breaks and just unwind.

8. **Network**
Reading the reviews on Trust Pilot, and from comments from many of the people I have interacted with, this is one of the main reasons why a lot of people join. There are forums on the student portal for work related topics like , as well as networking events that are normally in person (online during COVID) in cities around the world, bookclubs, and “PowerTalks” webinars with guest presenters that are specialists in their field dealing with a wealth of different topics.

9. **Overview**
In general it provides a great understanding of the whole business landscape. It’s a great way to update your knowledge and help with think out-of-the box.

**Dis-Advantages**

**Detail** — there isn’t a lot of detail, summaries are provided for each section but it’s limited. For those that are detail oriented you’ll need to do more in depth research on the topics you’re interested in.

**Masters** — as it’s not a recognised MBA program with the associated degree. They are also adamant that they don’t plan on doing this any time in the future.

**UI** — trying not to be too much of a stickler and taking my product manager hat off, they use the Typeform platform, which I’m a HUGE fan of and use their surveys all the time, it’s just not great as an education platform, the UI/UX is a little buggy and the navigation needs work.




Before you dive into this book, you should have a solid working proficiency over JavaScript up to the most recent standard (at the time of this writing), which is commonly called ES5 (technically ES 5.1). Here, we plan to talk squarely about the upcoming ES6, as well as cast our vision beyond to understand how JS will evolve moving forward.

If you are still looking for confidence with JavaScript, I highly recommend you read the other titles in this series first:

Up & Going: Are you new to programming and JS? This is the roadmap you need to consult as you start your learning journey.

- Up & Going
- Scope & Closures
- this & Object Prototypes
- Types & Grammar
- Async & Performance

[![railroad]({{ site.images | relative_url }}/rails.jpg)]({{ site.images | relative_url }}/rails.jpg)

If you've already read all those titles and you feel pretty comfortable with the topics they cover, it's time we dive into the evolution of JS to explore all the changes coming not only soon but farther over the horizon.

## `let` Declarations

However, we can now create declarations that are bound to any block, called (unsurprisingly) *block scoping*. This means all we need is a pair of `{ .. }` to create a scope. Instead of using var, which always declares variables attached to the enclosing function (or global, if top level) scope, use `let`:

{% highlight js %}
var a = 2;

{
    let a = 3;
    console.log( a );   // 3
}

console.log( a );       // 2
{% endhighlight %}
