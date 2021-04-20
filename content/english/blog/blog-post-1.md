---
title: "As a dev, you should know ops"
date: 2019-06-04T11:07:10+06:00
author: Lucas Severo Alves
image : "images/blog/mini-as-dev.jpeg"
bg_image: "images/feature-bg.jpg"
categories: ["Career"]
tags: ["Advice","Technology", "Career"]
description: "This is a repost of a blog from one of our Founders"
draft: false
type: "post"
---

<em> This is a repost of a blog from one of our Founders: https://dev.to/canelasevero/as-a-dev-you-should-know-ops-3bkh/edit </em>

## Cause DevOps

.

.

.

...

![Thats all gif](/images/blog/thatsall-folks.gif)

Some would say that you should learn it simply because you should, end of story. But it’s not that simple. Regardless of your reasons, I think that you should learn it to be a better dev and to boost your technical career.

## Lets quickly look at DevOps

Think about the traditional Dev vs Ops goals that existed “long ago” (Hopefully, you’re past dealing with this today): Devs were rewarded for shipping features and making changes, while Ops were rewarded by keeping things stable, and thus change was an enemy.

A massive number of methodologies were created, or borrowed, to get rid of this conflict, like [Blameless Postmortems](https://landing.google.com/sre/sre-book/chapters/postmortem-culture/) and [Just Culture](https://books.google.com.br/books/about/Just_Culture.html?id=ZA0uXmtR96MC&redir_esc=y). Another example is error-budgeting, in which SLAs and SLOs define how stable something has to be, and also how unstable it 'must' be. This is done to cut costs while encouraging change.

These things, paired with the LEAN practices, reflect the cultural and organizational pillars of DevOps. They are crucial, but often disregarded by some people. The other pillars use automation to cut down on repetitive tasks, and improve intelligent decision making with better data through monitoring, observing, and using this data as a guide.

With all that in mind, I would say that there is a lot more about DevOps than just Devs knowing Ops.

So, why would you, as a Dev, need to know some Ops, if not because of DevOps ? I’ll now try to give you four reasons that answer this question in a more career-oriented vibe. Maybe your company or your current position doesn’t require this knowledge, but knowing it will make you a better Dev overall, helping you write better services and giving you more “power”.

## 1- You can be part of important technical decisions/discussions

![](https://thepracticaldev.s3.amazonaws.com/i/7uks54hbzkl1925o05br.jpg)

Ops knowledge can open many doors for you. If your company has an architecture-steering committee or something similar, having such knowledge may play a big role in you becoming part of it, or even in bringing things for the committee to discuss. You may have a say in decisions related to stack, architecture, and even business.

Let’s say your company has a bit of a delay when it comes to response in some situations and in some services. One possible solution is to re-implement some of these services and part of the architecture. However, this could be very time consuming and demand a lot of effort. A better option might be to do a mix of software and infrastructure architecture change, hopefully with less effort. You might arrive at this solution by yourself from having a “mixed bag” of knowledge. You can then bring more people in for discussion on the topic.

## 2- You can write better services

![](https://thepracticaldev.s3.amazonaws.com/i/libbz51il7t24wqb94p6.png)

In the same way that you can provide better answers to problems that emerge in your services regarding its architecture and code, Ops knowledge may allow you to foresee problems that are bound to happen.

Your development can be really modular and focused on the thing your service is solving. But the ability to visualize problems regarding how your service interacts with other services and with the systems holding it is crucial for applications with really high SLOs and SLAs. This makes your services both reliable and available.

Hopefully, with some Ops or System Administrator experience under your belt, you will also feel the need to keep your services observable. With operability and observability you make possible to have people on call with less stress. 

## 3- Being on call can make you foolproof when coding 

![](https://thepracticaldev.s3.amazonaws.com/i/ya0vj3lqvidkbe24k0an.jpg)

Here I am not talking about just Ops knowledge, but also Ops experience with being on call. With enough of it, you start to see the weak links and parts most prone to failure in your system. This gets to you, you start feeling it under your skin, and when you go back to coding , it should influence you to write better code.

This one is almost the same as the second item, but I believe that the experience of being on call brings something that only it can bring: empathy for service operability. The second item refers to Ops knowledge you can acquire by reading or listening to people. This one refers to the knowledge acquired by your own experience and how this can later be used in writing code.

## 4- You can be part of all the life cycle of your code

![](https://thepracticaldev.s3.amazonaws.com/i/p4n6j67cqq1vayl3k8af.png)

You can write your code, and [test it](https://medium.com/@copyconstruct/testing-microservices-the-sane-way-9bb31d158c16); you know how to CI/CD it, and you know how to operate it in the production. You also know how to [observe](https://twitter.com/mipsytipsy/status/1086366949682995200) everything. I’m not saying you will be doing all these things every time, but you have the know-how, and may have done it before.

Your company shouldn’t expect everyone to know all of these things. But knowing them might reward you greatly. And thus, this pursuit should be encouraged by your company.

# So, how do we go about this?

I hope I have convinced you to learn some Ops. If you don’t know how, here are some options:

### References

I like the [opsschool readthedocs](https://www.opsschool.org/). There are a lot of topics missing content, but you can still use it as a list of topics to further research on the internet, and maybe get some books and articles on.

There are lots of specific tools-focused books that I could suggest, but you’d be better off looking for them based on what your company uses and what you want to learn.

For more general learning you could get [The Practice of Cloud System Administration](https://www.amazon.com/Practice-Cloud-System-Administration-Practices/dp/032194318X) and [UNIX Linux System Administration Handbook](https://www.amazon.com/UNIX-Linux-System-Administration-Handbook/dp/0134277554).

For Linux, [Linux Programming Interface System Handbook](https://www.amazon.com/Linux-Programming-Interface-System-Handbook/dp/1593272200/ref=sr_1_1?crid=VX920BJV6BJ2&keywords=linux+programming+interface&qid=1559098222&s=gateway&sprefix=linux+pro%2Caps%2C311&sr=8-1) is a great book. Mostly to be used as reference.

For networking you can read [Computer Networks by Tanenbaum](https://www.amazon.com/Computer-Networks-Tanenbaum-International-Economy/dp/9332518742).

You can read this references about observability: [Honeycombio Guide to Achieving Observability](https://www.honeycomb.io/resources/guide-achieving-observability/) and [Distributed Systems Observability](https://www.oreilly.com/library/view/distributed-systems-observability/9781492033431/ch01.html).

I know this seems like a lot, but don’t be intimidated by it all! Remember, there’s no need to read all of it. And here’s the actual best way to learn Ops:

### Just do it!

![](https://media.giphy.com/media/TCaq4FekwSV5m/giphy.gif)

See if your company gives you the option to try other positions and go for it. Ask for guidance and try to stay on call sometimes. If you have people around you who know something, talking to them and sharing what you know might be the best way to learn. So long as you have solid development skills, the addition of Ops experience could help you achieve even greater things!