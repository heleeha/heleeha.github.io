---
layout: essay
type: essay
title: The Vague Concept of Design Patterns
# All dates must be YYYY-MM-DD format!
date: 2021-12-01
labels:
  - Software engineering 
  - Design patterns
---

Design patterns is a vague concept that is difficult to grasp. After watching a couple of videos and searching the internet for a while, I finally feel like 
I have an understanding of what design patterns actually are. To sum it up I would say; 
design patterns are typical and reusable solutions that can be used for commonly occuring problems in software design. 
We can say that the patterns are templates that can be costumized to solve a spesific design problem, and they are best practices for solving common problems.
Design patterns originate from Cristopher Alexander, in 1977 he wrote that a design pattern "describes a problem that occurs over and over again in our environment, and then describes the core of the solution to that problem, in such way that you can use this solution a million times over, without ever doing it the same way twice."

## Design patterns become real
When just reading about what design patterns are it can be quite difficult to understand how they work in practice. For me the lightbulb went on when I looked at how I had actually used design patterns in my existing projects.I realized that I have used design patterns sevral times without actually being aware of it. When using Javascript and Meteor a lot of times I have used design patterns without knowing it, since these design patterns are implemented into them. In javascript I have used the "Prototype" design pattern when making objects by making a kopy of a instance that is prototypical. Now that I know that by doing this I am using a design pattern, I find it even easier to understand the difference between this and making classes in object oriented languages like c++. 

I have also used design patterns in my "Bridging the Gap" project that can be found [here](https://github.com/bridging-the-gap/bridging-the-gap). The Observer pattern has an object that maintains a list of its dependents and notifies if there are changes in states. We used Meteor's own "Observer" pattern "publish-describe" in this project, here the server publishes the collections and the client subscribes to the collection that is needed to render the page.
In this project we have also used design patterns that are spesific to the project and not a part of Javascript or Meteor. We used the "Singelton" pattern that provides a global variable. The variable "Profiles" in the "Bridging the gap" project can be viewed as a sigelton instance of the ProfilesCollection.


## Easier life using design patterns
When looking at how I have used design patterns I realize that they make coding a lot easier. Instead of needing to come up with new ideas and spending a lot of time trying to figure out how to solve a problem, you can simply find the design pattern that solves your problem. In this way we can also stadarize the way of solving different problems and make it easier to collaborate and maintain code.
