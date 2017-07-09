---
layout: post
title: «99 Bottles of OOP» book review
date:   2017-07-08 12:00:00
categories: en books ruby
---

"99 bottles of oop" is the second Sandy Metz's book, co-authoring Katrina Owen.
I was interested in this book for several reasons: first of all, I like the authors and their activities, secondly, I like the topic and the name of the book is awesome.
I believe that writing the solid book based on the discussions about one kata, especially the one about "99 bottles of beer" is an outstanding idea by itself.

The authors recommend spending a half an hour on solving the "99 bottles of beer" kata before reading the book.

In the beginning of the book, there are several solutions which are evaluated with the help of metrics and common sense.
When the best solution (for now) is chosen, the new requirements appear.
Now you have to adapt your code so that it would become open for the easy change. In the following chapters, you'll find the refactoring steps with the detailed descriptions and rationales.

> Make the change easy (warning: this may be hard), then make the easy change  
[Kent Beck](https://twitter.com/KentBeck/status/250733358307500032)

This book was written as the alternative to visiting a workshop, so it's important to reproduce all steps and imagine that you are at the event :)

The authors imply, that "99 bottles" may totally change your assumptions on TDD. The code is changed by very small steps, and after each change, you must run the tests and they should remain green. If not, revert and make another change.

If you are an experienced programmer and haven't used such approach before, it may be hard for you to use it. It's not easy to me to use all rules, especially when I work on large projects, that contain legacy code.
But it's useful to explore this approach: e.g. sometimes the right abstractions will "appear" after you make several small steps. It may be easier to try this approach while solving katas first.

According to the authors, the book has 2 goals:
- supply you with the concrete refactoring techniques for everyday use
- make you fall in love with polymorphism

I guess we shouldn't think of "99 bottles" as finding the right solution for the specific task. It's more of a demonstration of refactoring rules and oop principles, using this example.

Refactoring is one of my favorite topics, so I liked the book. It helped me to organize my knowledge, look at TDD from a different angle and use this approach more often.

[My notes on the book](https://github.com/lightalloy/books-notes/blob/master/ruby/99_bottles_of_oop.md)

Podcasts:
- [Why are computers? «Ways to Be Less Clever»](http://whyarecomputers.com/3)
- [Greater Than Code](https://www.greaterthancode.com/podcast/008-sandi-metz-and-katrina-owen/)
- [POODR And Beyond](http://www.codenewbie.org/podcast/poodr-and-beyond-part-i)
- [Ruby Book Club](http://rubybookclub.com/episodes/2016/7/31/99-bottles-ep-1-preface-11-intro)

[Alternative point of view and discussion on reddit](https://www.reddit.com/r/ruby/comments/5uul3y/99_bottles_of_oop/)
