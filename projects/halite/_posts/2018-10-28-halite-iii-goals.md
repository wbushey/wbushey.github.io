---
layout: post
title: Halite III Goals
tags:
  - ai
  - ml
  - kotlin
author: Bill
---


This week I joined a few co-workers in entering the [Halite III ][1] AI competition. While I have not
participated in previous Halite competitions, I'm very excited to take part this year in what
appears to be a fun opportunity to experiment with artificial intelligence.

What I find most exciting about the Halite competition is the opportunity to reconnect
with an interest that I largely abandoned ten years ago. I focused a lot of my undergrad
studies on AI. I was fascinated by the magic that leads some probability and graph searches to
produce 'intelligence'. A part of me wondered what, if anything, this reveals about human
intelligence. But for the most part, I was amazed that software could adapt and handle unforeseen
situations. This fascination lead me to a lot of projects and course work covering math, data
structures, algorithms, and AI; culminating in a senior research project to create a generalized
planning agent.

After college I went to policy school, dove into civic tech, and spent much of my software
development time on web applications. I drifted away form AI, but I never stopped being amazed
and fascinated by it. And by how it has evolved in the last ten years.

So, I intend to use the Halite competition as a way to reacquaint myself with this exciting field.
In particular, my goals for this competition are:

 1. Use Kotlin. This is a new-to-me language that I have started to use at work. I've enjoyed my
    time with it so far and have been impressed with how it carefully builds upon the strengths of
    Java while adding functional elements that feel right at home. This is a powerful language that
    I want to gain some more experience with.
 2. Recall what I learned in college. Ten years is a long time, and I'm sure I'll need some
    refreshers. Working on a game like this is a great reason for me to go back to revive some of
    what I learned about writing AI agents.
 3. Experience machine learning. I learned some of the foundations of how automated learning works,
    but the machine learning boom really started after I graduated. A lot of knowledge and tools
    have been created in the last ten years, and I'd like to play with some of that.

With these goals in mind, I'm also outlining a few milestones that I hope to achieve during this
competition:

 1. Setup a Kotlin development environment for Halite. [A Kotlin starter pack][2] already exists, which
    is tremendously helpful. To this I'd like to add tooling that I often use when developing,
    including library management, testing, and work flow tooling.
 2. Create a rule-based agent. Agents in the Halite game have a limited set of actions to choose
    from each turn. Agents are also provided with quiet a bit of information about the current state
    of the game. I hope to create an agent that selects actions based on a mix of this available
    current state, some measure of expected value, and some adjustable policy.
 3. Make use of a machine learning library. The Java ecosystem includes a few ML libraries, and
    I would really like to experiment with at least one of them. While I do not yet know how I
    will make use of ML, one possibility is to use ML to adjust a policy for the rule based agent.

 [1]: https://www.technology.org/2018/10/17/two-sigma-launches-halite-iii-the-open-source-competition-for-artificial-intelligence-experimentation/
 [2]: https://halite.io/learn-programming-challenge/downloads
