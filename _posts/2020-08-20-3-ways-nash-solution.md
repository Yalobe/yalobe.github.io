---
title: 3 Ways of Approaching the Nash Bargaining Solution
date: 2020-08-27 09:00:00 -0400
categories: [Posts, Projects]
tags: [blog, project, math, game-theory]    # TAG names should always be lowercase
toc: false
math: true
---

In my senior year of college, I gave a seminar talk titled "3 Ways of Approaching the Nash Bargaining Solution."  Unfortunately, the talk was not recorded.  Here, I'll attempt to sketch the three proofs out again. I don't have all of my old notes, so this might be a bit rough around the edges!

## Introduction and Intuition

While walking down the street with a friend, you stumble upon \$100. Given that the original owner of this money is nowhere in sight, you two decide to split the cash. What split is optimal?

We can describe the options before us with the following curve:

![Fig 1](https://yalobe.github.io/assets/img/3_ways_nash_solution/optimalSplits100.jpeg)

The points above the line are inaccessible, as we would have used more than \$100 dollars. All points at or below the line are accessible, but it is unreasonable to pick them as some quantity of money would go unclaimed. Assuming you and your friend are both greedy, why would you leave some cash when you both could have it yourself?

Quite reasonably, you might expect the solution to be a point like the one demonstrated below

![Fig 1](https://yalobe.github.io/assets/img/3_ways_nash_solution/optimalPoint100.jpeg)

We will demonstrate why this *has* to be the solution in the section below.
