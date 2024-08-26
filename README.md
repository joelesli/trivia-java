# Software Design Kata

## Introduction: Surviving Legacy Code
We all have legacy code, meaning profitable code that we’re afraid to change. It doesn’t matter who wrote it, in which language, nor when. It matters that we feel the fear now and need to deal with it. Rewrite or refactor? How do we write useful tests? There’s so much to change; how do we get started? When do we stop? Will it ever get any easier?

In the typical programmer’s day job, there’s no time to learn how to do this. We’re already behind schedule and the cost of fixing the legacy code is crushing us. We need a way to learn how to do this safely, correctly, and eventually, even quickly. That’s what Surviving Legacy Code is about.

## What is the task?

Trivia from the [legacy code retreat](https://www.jbrains.ca/training/course/surviving-legacy-code) is a good codebase to start this with. There are a few bugs in the code and a few weaknesses in the design to fix. By a weakness we mean that it’d be easy for a developer to introduce a certain type of bug while working with the code. Your job is to change the design so that it is either impossible or at least much less likely that that kind of bug would be introduced.

## Things to improve

1. A game could have less than two players. 
2. A Game could have 7 players, make it have at most 6.
3. A player that get’s into prison always stays there
4. The deck could run out of questions
5. Introducing new categories of questions seems like tricky business.
6. Similarly changing the board size greatly affects the questions distribution


## Additional Resources

* [5 steps to mistake-proof software design](http://mozaicworks.com/blog/5-steps-to-mistake-proof-software-design/)
* [It's not a configuration issue. It’s a design issue](http://martinsson-johan.blogspot.fr/2016/06/its-not-configuration-issue-its-design.html)
* [Presentation by Arlo Belshee on YouTube](https://www.youtube.com/watch?v=gQR1NlkgLZU)