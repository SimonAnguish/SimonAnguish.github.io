---
layout: post
title: Branching Out II
date: 2016-08-11 16:15:00
categories: algorithms git blog
---
Yesterday I intended to talk about branching in git, but that got a little off track. I finally discovered the secret to succesfully using git, and I suddenly have even more respect for git.

~~~ shell
> git checkout -b Branch_name
*** Make Edits ***
> git add .
> git commit -m "Make Changes"
> git checkout master
> git merge Branch_name
> git push
> git branch -d Branch_name
~~~

It's so clean to make edits like this now, and I love it. I never really looked much into branching, but now I feel like I'm not going to be able to do anything without it. It saves me from messing up, since I can just abandon that branch if need be. I think the next thing I'll really want to experiment with, after I work through all the other deadlines I have coming up, will be reverting back to older commits.

---
I added a handful of other algorithms to the repo today, including Kruskal's and Knapsack. I was explaining git to Jenn last night, which is why there's an empty Heap Sort folder there, but it's being worked on. I'll also need to work on Dijkstra, which I could have sworn I had finished. I would love to work on getting a successful un/directed graph setup, which I might work on while I'm studying about git some more. I feel like having one of those that I can implement whenever I wanted would be invaluable.

I'm also working on a new project that I got the idea for, where it parses through all of the classes for next semester and documents any changes that were made. If I could find out where the .csv files for the semesters are, that would make this a thousand times easier. One of the issues I see with this is that the line numbers change, and it very well may be showing everything as having changed. I'll be sure to check that out when I have more time, possibly next week. Tomorrow I will need to do a lot of work related "programming", but with the summer wrapping up hopefully that will slow down and I can focus on side-projects that I'm actually devoted to. Also big news hopefully in the next few weeks, we'll see!