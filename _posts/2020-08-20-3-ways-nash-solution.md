---
title: 3 Ways of Approaching the Nash Bargaining Solution
date: 2020-08-27 09:00:00 -0400
categories: [Posts, Projects]
tags: [blog, project, math, game-theory]    # TAG names should always be lowercase
toc: true
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

Next, we will demonstrate why this *has* to be the solution.

## Formalizing our Intuition

Let make the scenario a bit more rigorous.  In a Nash Bargaining Game, there are two actors and there is a pot of money with $$T$$ dollars (or euro, or whatever) in it. Both players submit requests, $$r_1$$ and $$r_2$$, representing a portion of the total.  If $$r_1 +r_2 \leq T$$, both walk away with what they asked for. However, if $$r_1 + r_2 > T$$, both players get nothing. In our scenario above, $$T = 100$$ and we expected $$r_1 = r_2 = 50$$.

In conjunction with assuming that our actors are rational, Nash identified four axioms that a solution to a game of this type should satisfy:

1. Invariance to transformations
2. Pareto Optimality
3. Independence of Irrelevant Alternatives
4. Symmetry

Let's take a look at each one in more depth.

### Invariance to Transformations

This captures the idea that we can transform the plane, but the relations between our points are maintained. Say point $$(a, b)$$ is such that $$a \leq a'$$ and $$b \leq b'$$. Then any transformation of the plane that maintains this relationship will result in the same solution. 

![Fig 3](https://yalobe.github.io/assets/img/3_ways_nash_solution/affineTransforms.jpeg)


Why do we want to resist these transformations of the plane? It comes back to the idea of transitivity and relations between outcomes. As these are order preserving changes to the plane, they are unable to affect the ordered relations between outcomes. If $$t \ in T$$ is preferred to $$t' \in T$$, then under any affine transformation this relationship is preserved.

### Independence of Irrelevant Alternatives

### Symmetry