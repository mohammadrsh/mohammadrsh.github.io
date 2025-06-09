---
layout: post
title: "Architecture as Code"
date: 2025-06-09 11:52:16 +0200
categories: blog tech
---

# Architecture as Code

The traditional approach to designing a software was to first drawing the architecture of the software and then implement the code from the architechture diagram. Thus this idea is not the best because implemented code might not fully represents the diagram and and there is no control on that. Todat we want to see another code first approach which does not have these drawbacks. Le's discuss the benefits of AaC here.

## Benefits

### 1. Define in the code

One of the key benefits of defining your architecture as code is that you can define it in your code. **Architecture and code are not seperate, tho they are together and they should live together**. So imagine if you code your diagram, then you can always have it in your code as part of the code, many benefits comes from that which i will discuss later.

### 2. Version controll your architecture

Another key benefits of AaC is that you can version your architecture and see when/why and how your architecture was changed and adopted. **Remember**, _architecture is evelutionaty, it won't emerge_.

### 3.Write tests for it

Another big advantage of AaC is that it's make it easier to write tests for your architecture. Yes you read correcet **Tests**! There are lot's of benefits of writing tests for your architecture. A big one is that you can **assert if the code is following the defined architecture**! It's a big one. Another big one is you **fail fast** which is a very big benefit. As the last benefit it can **start a converstion** around architecture and desisions.

### 4.Visualize

Yes we come to visualize part, at the end all of us want to visualize our architecture and see if all components are logically conected and also to represent it to the bussiness people. I don't go deeper into visualize part.

### 5.Feeding into LLM

And the last benefit which is became more important in the last couple of years is tha you can feed your architecture into an **LLM**. This has lot's of benefits. Imagine how many questions you can ask an LLM about your architecture.
