---
layout: post
title:  "Machine Learning from a Bayesian perspective"
date:   2019-03-21 00:28:14 +0000
categories: jekyll update
mathjax: true
---
Artificial Intelligence, machine learning, and robotics. All buzzwords that have seen a surge in popularity admits the turn of the 21st century. With recent advancement in big data analytics and computational power, our current understanding of how data can shape our lives have changed. From social media trends, fake news, to changes in laws concerning data privacy, it is clear that our world is changing, and at the centre of all this hype: machine learning.

![Trend](https://github.com/fz16336/Machine-Learning/blob/master/courseworks/Coursework1/Figures/Likelihood1.png)
[![Flower](/learning-page/assets/trend.png)](/learning-page/assets/trend.png)
[Flower](https://github.com/fz16336/Machine-Learning/blob/master/courseworks/Coursework1/Figures/Likelihood1.png)

<!-- <div class="embed">
  <script type="text/javascript" src="https://ssl.gstatic.com/trends_nrtr/1754_RC01/embed_loader.js"></script>
  <script type="text/javascript">
    trends.embed.renderExploreWidget("TIMESERIES", {"comparisonItem":[{"keyword":"/m/01hyh_","geo":"","time":"2004-01-01 2019-03-25"},{"keyword":"/m/0jt3_q3","geo":"","time":"2004-01-01 2019-03-25"}],"category":0,"property":""}, {"exploreQuery":"date=all&q=%2Fm%2F01hyh_,%2Fm%2F0jt3_q3","guestPath":"https://trends.google.com:443/trends/embed/"});
  </script>
</div> -->

But what is machine learning? To put it simply (albeit a bit frank), it's statistics. However, statistics have been around since the days we invented counting, then what makes machine learning different? Machine learning refers to the notion of inferring patterns in data, by making assumptions, building models based on them, and testing our hypothesis as we see new observation. To actually see the difference in machine learning as oppose to regular statistics, we need to take a step back from the rigid mathematical framework that defines the algorithms, and look at the philosophical intuition behind machine learning. To start let us ask ourselves, what is learning? How do we as humans learn? And how can we mimic the learning process so machines can do the same? Enabling us to build smarter systems and computers.

I believe that the basis of learning itself comes from observing new information. As one see something new, we can learn about something new as well. This is no different than how data is the central focus of machine learning. To give an analogy based on how we humans learn, think of supervised learning as learning from guidance. Similar to how our parents have guided us to determine what is right or wrong, and what is useful or not, we have come to learn what holds meaning in life through the 'labels' thought by our parents. Whereas unsupervised learning is perceiving the world our own eyes, and making decisions based on how we personally interpret the world. Much as machines as well, humans -in away- are programmed too. Our personalities define who we are but they can change as we grow, be it from nature, nurture or even both. But if this is true then is there possibility that we can accurately model a machine that can think and learn exactly like us? Are the movies and stories about AI taking over the world possible, or will they always be fiction? To answer that question, we must understand how machine learning models work. Many of us were introduced to the concept of probabilities from a 'frequentist' perspective, i.e. we viewed probabilities as mere frequencies of events for random variables. However, this is too limited for machine learning purposes, as we want to make inference over things that we have not observe yet, and so we must now view things from the Bayesian point of view.

A model is a simplified framework of the real-world, with layers of abstraction to only account for the relevant; enabling us to limit the uncertainty around. Much as how humans learn, machines learn the same way. We make assumptions and build models of how the world works based on our beliefs of how it should be, but as we see new information our beliefs can change; adjusting our perspective - such is the process of learning. From a Bayesian point of view we can interpret probabilities as beliefs in a variable, allowing us to define probabilities over things that have not been observed. This interpretation allows us to put semantics onto the terms in Baye's Rule as *Posterior*, *Likelihood*, *Prior*, and *Evidence*.

$$ P(\mathbf{\Theta}|\mathbf{X}) = \frac{P(\mathbf{X}|\mathbf{\Theta})P(\mathbf{\Theta})}{\mathbf{X}} $$

--UNFINISHED--

<!-- {% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %} -->

Meanwhile check out my coursework report for [Bayesian Modelling][jekyll-docs] for more info Bayesian approaches to machine learning, and how we make [inference][jekyll-gh] after building our models.

[jekyll-docs]: https://github.com/fz16336/Machine-Learning/blob/master/courseworks/Coursework1/Bayesian_modelling.pdf
[jekyll-gh]:   https://github.com/fz16336/Machine-Learning/blob/master/courseworks/Coursework2/Inference.pdf
[jekyll-talk]: https://talk.jekyllrb.com/
