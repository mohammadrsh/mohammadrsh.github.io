---
layout: post
title: "Architecture as Code"
date: 2025-06-09 11:52:16 +0200
categories: blog tech
---

The traditional approach to designing software was to first draw the architecture of the software and then implement the code from the architecture diagram. However, this idea isn't always the best because the implemented code might not fully represent the diagram, and there's no control over that. Today, we want to look at another "code-first" approach that doesn't have these drawbacks. Let's discuss the benefits of Architecture as Code (AaC) here.

# Benefits

## 1. Define in the code

One of the key benefits of defining your architecture as code is that you can truly define it in your code. **Architecture and code are not separate; they are together, and they should live together.** So, imagine if you "code" your diagram – you can always have it in your code as part of the code. Many benefits come from that, which I will discuss later.

## 2. Version Control Your Architecture

Another key benefit of AaC is that you can version your architecture and see when, why, and how your architecture was changed and adopted. **Remember**, _architecture is evelutionaty, it won't just emerge_.

## 3.Write Tests for It

Another big advantage of AaC is that it makes it easier to write tests for your architecture. Yes, you read correctly: **Tests!** There are lots of benefits to writing tests for your architecture. A big one is that you can **assert if the code is following the defined architecture!** That's a huge one. Another major benefit is that you **fail fast**, which is incredibly valuable. As a last benefit, it can **start a conversation** around architecture and decisions.

## 4.Visualize

Yes, we come to the visualization part. In the end, all of us want to visualize our architecture and see if all components are logically connected, and also to represent it to business people. I won't go deeper into the visualization part here.

## 5.Feeding into LLM

And the last benefit, which has become more important in the last couple of years, is that you can feed your architecture into an **LLM**. This has lots of benefits. Imagine how many questions you can ask an LLM about your architecture!

In the next posts, we will discuss how we can actually define our architecture as code.
