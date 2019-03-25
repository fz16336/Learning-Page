---
layout: post
title:  "Machine Learning from a Bayesian perspective"
date:   2019-03-21 00:28:14 +0000
categories: jekyll update
mathjax: true
---
Artificial Intelligence, machine learning, and data science. All buzzwords that have seen a surge in popularity admits the turn of the 21st century. With recent advancement in big data analytics and computational power, our current understanding of how data can shape our lives have changed. From social media trends, fake news, to changes in laws concerning data privacy, it is clear that our world is changing, and at the centre of all this hype: machine learning.

But what is machine learning? To put it simply machine learning is a subset of the field of artificial intelligence (AI). It refers to the notion of being able to infer something new from recognising patterns in data. It is the idea that we can teach systems of machines the ability to automatically learn and make meaningful decisions based on said data; without being explicitly programmed. But at the end of the day, it's all just probabilities and statistics ... but also slightly more. To understand what machine learning is truly capable of, as apposed to frequentist statistics, we need to take a step back from the rigid mathematical framework that defines the algorithms, and look at the philosophical intuition behind machine learning first. To start let us ask ourselves, what is learning? How do we humans learn? And can we mimic the learning process to teach machines to do the same? If so, this may enables us to build smarter systems and computers.

## The philosophy

 I believe that the basis of learning itself comes from observing new information. As one see something new, we can infer about something new as well. This is no different than how data becomes the central focus of machine learning. There are 2 common facets in machine learning: *supervised learning* vs. *unsupervised Learning*. To give an analogy based on how we humans learn, think of supervised learning as learning from guidance. Similar to how our parents have guided as we grow, they helped us to determine what is right or wrong, and what is useful or not. We have come to learn what holds meaning in our lives through the 'labels' taught by our parents. On the other hand, unsupervised learning is like perceiving the world through our own eyes, making decisions and inference based on how we personally interpret the information around us; without the influence of anyone else.

With that being said, humans -in away- are like programmable machines too. Our personalities define who we are and yet they are subject to change, dependent on our environment and upbringing. We are programmed, be it from nature, nurture or even both. But of course, there is so much more than that to what makes one human. A whole series of unanswerable existential questions make up what it truly means to be human. Such complex ideas like emotions, consciousness, and free-will are to hard to quantify, and much less capable of being boiled down to statistics. But we don't need to model the entire human brain to create an AI. All we seek is to build smarter computers that can understand the semantics in the data they process ... to a certain extent. After all, the whole point of modelling something is to do away with all that is unnecessary or hard to grasp, and simply focus on the easy stuff.

> All models are wrong, but some are useful.
>                            – _George Box_

A model is a simplified framework of the real-world, with layers of abstraction to only account for the relevant; enabling us to limit the uncertainty around. Much as how humans learn, machines learn the same way. We make assumptions and build models of how the world works based on our beliefs of how it should be, but as we see new information our beliefs can change; adjusting our perspective - such is the process of learning.

Many of us were introduced to the concept of probabilities from a 'frequentist' perspective, i.e. we viewed probabilities as mere frequencies of events for random variables. However, this is too limited for machine learning purposes, as we want to make inference over things that we have not observe yet, and so we must now view things from the Bayesian point of view. And from a Bayesian perspective, we can interpret probabilities as **beliefs** in a variable, allowing us to put semantics onto the terms in Baye's Rule as *Posterior*, *Likelihood*, *Prior*, and *Evidence*.

$$ P(\mathbf{W}|\mathbf{X}) = \frac{P(\mathbf{X}|\mathbf{W})P(\mathbf{W})}{\mathbf{X}} $$

## The maths

<!-- {% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %} -->

Meanwhile check out my coursework report for [Bayesian Modelling][jekyll-docs] for more info Bayesian approaches to machine learning, and how we make [Inference][jekyll-gh] after building our models.

[jekyll-docs]: https://github.com/fz16336/Machine-Learning/blob/master/courseworks/Coursework1/Bayesian_modelling.pdf
[jekyll-gh]:   https://github.com/fz16336/Machine-Learning/blob/master/courseworks/Coursework2/Inference.pdf
