---
layout: post
title:  "Investigating Primes: Variations in Ulam Spirals"
date:   2024-1-1 18:04:00 -0700
categories: jekyll update
---

<!-- You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets: -->

<!-- {% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %} -->

## Introduction

*"Out of an infinity of designs a mathematician chooses one pattern for beauty's
sake and pulls it down to earth." - Marston Morse, American Mathematician*

This project is an introduction to prime numbers (don't worry, we define these soon!)
through a rather artistic lens; instead of jumping straight into algebraic work,
we look at numbers via the patterns they make in $$2$$-dimensional space. We start
by considering Ulam spirals initially, and then branch specifics such as Archimedean
spirals, and from there we branch further into prime spirals and visualizations
of Gaussian and Eisenstein primes (once again, all of this will be defined shortly).

The visualizations made in this project are via python, and all code used will be provided
inline with the project, and so if you wish to play around with the code and parameter
sizes on your own machine, you can easily do so!

## Mathematical Background

To avoid overwhelming the layman reader, we introduce each mathematical concept
quite carefully.

### What are prime numbers?
