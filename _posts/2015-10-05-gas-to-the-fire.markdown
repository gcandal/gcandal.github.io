---
layout: post
title:  "Gas to the fire"
date:   2015-10-05 23:10:45
description: Some materials I've read/watch, or plan to, when working on the dissertation.
categories:
- dissertation
- visual_programming
- probabilistic_programming
permalink: proposal
---

We all stand on the shoulders of giants, and on this post I will try to keep a list of the materials I have gone through when working on my dissertation, along with some notes here and there.

## Probabilistic Programming

### Talks

[**<s>SciPy 2013 Keynote: Trends in Machine Learning and the SciPy community</s>**](https://www.youtube.com/watch?v=S6IbD86Dbvc&index=1&list=PLWJTwh75g1Ve5pDq2OJ88o2j1tD-QtCum) - This is THE talk on this subject. Analyses the state of the art (at the time) of machine learning and elaborates on why there is a place for probabilistic programming and Bayesian reasoning, and which problems does it solve. **To be re-watched**.

[<s>Infer.py: Probabilistic Programming and Bayesian Inference from Python; SciPy 2013 Presentation</s>](https://www.youtube.com/watch?v=x2od7tsPjQE) - From a contributor to the Infer.NET port to Python, it has a very decent intro do why PPLs matter (first 5 minutes).

[An Overview of Probabilistic Programming" by Vikash K. Mansinghka](https://www.youtube.com/watch?v=-8QMqSWU76Q)

### Slides

**<s>Winn, Minka, Probabilistic programming. Machine Learning Summer School</s>** - very clear and practical slides on CSoft and Infer.NET.

<s>Deriving probability density functions from probabilistic functional programs</s> - read below.

**<s>Duvenaud, Lloyd, Introduction to probabilistic programming.</s>** - I would risk to call it the best intro to PP, as it gives some context on why it is useful, presents some examples in code and then compares different inference methods.

John Winn's Presentation on variational inference and Variational Message Passing

### Papers/Articles

[<s>Dataflow Programming Concept, Languages and Applications</s>](http://paginas.fe.up.pt/~prodei/dsie12/papers/paper_17.pdf) - generic overview of DFP, its applications and challenges.

[<s>A model-learner pattern for Bayesian reasoning</s>](http://research.microsoft.com/apps/pubs/default.aspx?id=173887) - not the most relevant one. In sum, suggests a pattern for using typed Bayesian models. Examples are in Fun (a languaged hosted in F#).

[<s>Deriving probability density functions from probabilistic functional programs</s>](http://research.microsoft.com/apps/pubs/default.aspx?id=189021) - it's about a compiler from probabilistic programs to probability density functions, with examples in Fun. Could not fully grasp the inner workings, and I find it out of scope, but it was nice remember the differences between PMF, PDF and CDF.

[**<s>Probabilistic Programming</s>**](http://msr-waypoint.com/pubs/208585/fose-icse2014.pdf) - very thorough overview of probabilistic programming which is written in way which can be easily followed by someone with a background in software engineering rather than statistics or machine learning. Has a ton of examples (in a C-like language). Makes a comparison between probabilistic programs and bayesian models/discrete time markov chains and how to convert from the latter to the former. Goes on describing applications. Compares message passing to sampling and static to dynamic inference. Ends by enumerating future work to be done in this topic.

[<s>The Principles and Practice of Probabilistic Programming</s>](https://web.stanford.edu/~ngoodman/papers/POPL2013-abstract.pdf) - introduction to probabilistic programming with examples in Church (Scheme subset). I found it both not very easy to follow nor complete.

[<s>Picture: A Probabilistic Programming Language for Scene Perception</s>](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Kulkarni_Picture_A_Probabilistic_2015_CVPR_paper.pdf) - Introduces a domain-specific PPL. Avoid this kind of papers.

[<s>The Markov Chain Monte Carlo Revolution</s>](http://math.uchicago.edu/~shmuel/Network-course-readings/MCMCRev.pdf) - Focuses on the mathematics of the Metropolis algorithm, not what I was looking for.

[<s>A Short History of Markov Chain Monte Carlo: Subjective Recollections from Incomplete Data</s>](http://arxiv.org/pdf/0808.2902.pdf) - Summarizes how MCMC algorithms evolved over time, focuses in the innovation of each of them relative to the state of the art of the time. Not very relevant to me, since it does not address applications.

[<s>Bayesian analysis and Markov chain Monte Carlo simulation</s>](https://www.jbs.cam.ac.uk/fileadmin/user_upload/research/workingpapers/wp0710.pdf) - Despite being written in Portugal Place, I didn't find it particularly useful.

[<s>An Introduction to MCMC for Machine Learning</s>](http://www.cs.ubc.ca/~arnaud/andrieu_defreitas_doucet_jordan_intromontecarlomachinelearning.pdf) - Enough to get an intuition on MC methods and dig deeper into the subject if needed. Giving up on understanding Metropolis-Hastings in greater detail.

[Markov Chain Monte Carlo for Statistical Inference](http://ecovision.mit.edu/~sai/12S990/besag.pdf)

[Variational Message Passing](http://www.johnwinn.org/Publications/papers/VMP2005.pdf)

[<s>Variational Algorithms For Approximate Bayesian Inference</s>](http://www.cse.buffalo.edu/faculty/mbeal/papers/beal03.pdf) - 300 pages long, so skipping this by now. Seems to have a nice overview over Probabilistic Programming and its inference methods (Introduction section), to be read later.

[<s>Introduction to probabilistic programming</s>](http://people.seas.harvard.edu/~dduvenaud/talks/probabilistic-programming-introduction.pdf) - An introduction like many others.

[<s>Why Probabilistic Programming Matters</s>](https://plus.google.com/u/0/+BeauCronin/posts/KpeRdJKR6Z1) - Explains why there is a place for PP. I had already read this elsewhere, nonetheless it's a great read to convert non-believers.

[Probabilistic Models of Cognition](https://probmods.org/)

[What is probabilistic programming?](http://www.pl-enthusiast.net/2014/09/08/probabilistic-programming/)

[Lightweight Implementations of Probabilistic Programming Languages Via Transformational Compilation](http://jmlr.csail.mit.edu/proceedings/papers/v15/wingate11a/wingate11a.pdf)

[Stan: A Probabilistic Programming Language](http://www.stat.columbia.edu/~gelman/research/published/stan-paper-revision-feb2015.pdf)

[WinBUGS – A Bayesian modelling framework: Concepts, structure, and extensibility](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.471.604&rep=rep1&type=pdf)

### Books

[<s>Think Bayes</s>](http://www.greenteapress.com/thinkbayes/thinkbayes.pdf) - Bayes reasoning meets real-world problems.

[Dataflow and Reactive Programming Systems](https://deepfriedcode.com/books/darps.html)

[Practical Probabilistic Programming](https://manning.com/books/practical-probabilistic-programming)

### Tutorials/Walkthroughs

[Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)

[Infer.NET](http://research.microsoft.com/en-us/um/cambridge/projects/infernet/)

[<s>The Design and Implementation of Probabilistic Programming Languages</s>](http://dippl.org/) - Walks through the inner workings of a PPL, giving an overview how its building blocks compose. Nice to understand umbilical program/model relation and how a model is built by sampling over a running program.

[<s>The State of Probabilistic Programming</s>](https://moalquraishi.wordpress.com/2015/03/29/the-state-of-probabilistic-programming/comment-page-1/#comment-1450) - Awesome report of the current state of PPLs, comparing them across several categories. Addresses the most pressing concerns as well as future challenges. Nice to read after already understanding the basics of PPLs and why do they matter.

### Yet to expand

[Probabilistic Programming Reading Group @ Oxford](http://www.robots.ox.ac.uk/~perov/reading_groups/probprob2013/)

[probabilistic-programming.org](http://probabilistic-programming.org/research/)

[Forest, a repository for generative models](http://forestdb.org/)

## Visual Programming

### Existing products

#### Data Analysis
[<s>Weka Knowledge Flow</s>](https://www.youtube.com/watch?v=yCceL6YCMn4)

[<s>RapidMiner</s>](https://www.youtube.com/watch?v=lZho66YQEIM)

#### Other
[<s>NoFlo</s>](http://noflojs.org/)

[<s>Apple Quartz Composer</s>](https://en.wikipedia.org/wiki/Quartz_Composer)

[<s>Weka Knowledge Flow</s>](https://www.youtube.com/watch?v=yCceL6YCMn4)

## Both

[Demonstration: A Visual and Interactive IDE for Probabilistic Programming](https://old.nips.cc/Conferences/2014/Program/event.php?ID=4814)
