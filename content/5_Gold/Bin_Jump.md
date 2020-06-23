---
id: bin-jump
title: "Binary Jumping"
author: Benjamin Qi
description: Introduces the problems of finding level ancestors in a tree and computing the lowest common ancestors.
---

## Binary Jumping

  - CSES
    - [Planet Queries I](https://cses.fi/problemset/task/1750)
    - [Company Queries I](https://cses.fi/problemset/task/1687)

## Lowest Common Ancestor

 - [CSES Company Queries II](https://cses.fi/problemset/task/1688)

### Tutorial

 - CPH 18.1, 18.3
 - [cp-algorithms: Lowest Common Ancestor](https://cp-algorithms.com/)
 - [Binary Jumping w/ O(N) Memory](https://codeforces.com/blog/entry/74847)
   - you shouldn't actually need this, but maybe interesting

### Problems

 - CSES
   - [Distance Queries](https://cses.fi/problemset/task/1135/)
   - [Planets Queries II](https://cses.fi/problemset/task/1160)
 - USACO
   - Gold
     - [USACO Gold Milk Visits](http://www.usaco.org/index.php?page=viewproblem2&cpid=970)
     - [USACO Gold Cow Land](http://www.usaco.org/index.php?page=viewproblem2&cpid=921)
       - LCA + BIT
   - Plat
     - [USACO Plat Newbarns](http://www.usaco.org/index.php?page=viewproblem2&cpid=817)
       - online tree diameter
       - Copy of [CF Brain Network "Hard"](https://codeforces.com/contest/690/problem/C3)
     - [Max Flow](http://www.usaco.org/index.php?page=viewproblem2&cpid=576)
     - [Promote](http://www.usaco.org/index.php?page=viewproblem2&cpid=696)
       - Subtree + BIT
     - [Disrupt](http://www.usaco.org/index.php?page=viewproblem2&cpid=842)
       - HLD is possible, but just do binary jumps
     - [Tree Boxes](http://www.usaco.org/index.php?page=viewproblem2&cpid=948)
       - interactive!!
     - [Gathering](http://www.usaco.org/index.php?page=viewproblem2&cpid=866)
     - [Exercise](http://www.usaco.org/index.php?page=viewproblem2&cpid=901)
       - tricky
 - Other
   - [Hot & Cold](https://dmoj.ca/problem/bts17p7) [](105)
   - [Root LCA Queries](https://csacademy.com/contest/archive/task/root-lca-queries/) [](107)