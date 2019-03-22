---
layout: post
title:  "Machine Learning from a Bayesian perspective"
date:   2019-03-21 00:28:14 +0000
categories: jekyll update
mathjax: true
---

A model is a simplified framework of the real-world, with layers of abstraction to only account for the relevant; limiting the uncertainty around. Much as how humans learn, machines learn the same way. We make assumptions and build models of how the world works based on our beliefs of how it should be, but as we see new information our beliefs can change; adjusting our perspective - such is the process of learning. From a Bayesian point of view we can interpret probabilities as beliefs in a variable, allowing us to define probabilities over things that have not been observed. This interpretation allows us to put semantics onto the terms in Baye's Rule as *Posterior*, *Likelihood*, *Prior*, and *Evidence*.

$$ P(\mathbf{\Theta}|\mathbf{X}) = \frac{P(\mathbf{X}|\mathbf{\Theta})P(\mathbf{\Theta})}{\mathbf{X}} $$

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
