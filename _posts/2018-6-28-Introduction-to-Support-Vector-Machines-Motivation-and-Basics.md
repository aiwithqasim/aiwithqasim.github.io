---
layout: post
type: blog
title: Introduction to Support Vector Machines
excerpt: Motivation and Basics
comments: true
mathjax: true
---

In this post, you will learn about the basics of Support Vector Machines (SVM), which is a well-regarded supervised machine learning algorithm. This technique needs to be in everyone's tool-bag especially people who aspire to be a data scientist one day. Since there's a lot to learn about, I'll introduce SVM to you across two posts so that you can have a coffee break in between :)

First, let us try to understand how SVM works in the context of a binary classification problem. In a binary classification problem, our data belong to two classes and we try to find a decision boundary that splits the data into those two classes while making minimum mistakes. Consider the diagram below which represents our (hypothetical) data on a 2-d plane. As we can see, the data is divided into two classes: Pluses and Stars.

$$\begin{aligned} \dot{x} & = \sigma(y-x) \ \dot{y} & = \rho x - y - xz \ \dot{z} & = -\beta z + xy \end{aligned}$$