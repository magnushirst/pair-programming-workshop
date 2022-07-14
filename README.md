# Pair Programming
A repo to assist in the practice of pair programming 


## What Is Pair Programming

A great explanation of Pair Programming from [Uncle Bob](https://blog.cleancoder.com/uncle-bob/2021/01/17/Pairing.html)
> Everybody pairs from time to time. It is a rare programmer who has not sat down with another programmer to look something over or help find a bug.
 
> Deep problems, that require much heavy thinking, do not often lend themselves to pairing. The interaction between the programmers tends to disrupt the necessary concentration.

> On the other hand, it is not uncommon for programmers to get caught in a problem that they think is deep, but for which there is a much simpler solution that another programmer could quickly see. So it is wise to start deep problems with a pair, or even a mob, but then break it up when it becomes clear that the problem is irreducible.

> On the other side of the spectrum, there is no good reason to pair on trivial matters. Fleshing out a list of error messages, or loading fifty fields into a form are relatively mindless activities that do not require the scrutiny afforded by pairing.

> Then there is the vast middle. This is where pairing/mobbing are most valuable. These are problems that are non-trivial, but also not particularly deep. This is 90% of all programming. Pairing on this type of code keeps that code well tested, well structured, and as simple as possible.

> Pairing should always be voluntary, never be forced, never be scheduled by a manager, and never tracked. It is an informal process that is entirely under the control of the individual programmers.

> Some people can’t, or won’t do it. That’s ok; but it may require that their participation in certain projects be curtailed.

> Pairing sessions should be short-ish. 20-40 minutes at a time. With no more than three or four consecutive sessions of that length. This is not a rule, just an informal guideline.

> Not all code that would benefit from pairing, should be written by pairs. A mature team might pair 50% of the time, or even less. During the pairing sessions, a large amount of code will be reviewed; far more than the pair is actively writing; and thus the benefits of pairing will be seen in very large swathes of non-paired code.

> Bottom line: Don’t be a jerk. Pair sometimes, don’t pair other times. Pair enough so that you have a good grasp of the overall system, and know enough of what your teammates are doing that you could step into their roles if the need arose. Don’t pair so much that you hate your job, and your teammates.


## Techniques
### The Driver-Navigator Style 
     
**The Driver** is the person at the keyboard doing the coding. Their objective is to focus on completing the small milestones and talk through what they are doing.

**The Navigator** is in the observer position, while the driver is typing, they review the code as they go, giving directions and helping. As they are not coding, they can spend time also thinking about the larger solution, the architecture, potential bugs and issues that may arise.

The purpose of this technique is to have each contributor focussed on the short term tactical solution of the code and also the strategic e2e solution.

An example of the technique would be to:

  * Start with a well enough defined task.  
  * Agree on one goal/objective at a time. This can be done by writing a unit test, thinking of the commit message or a jira subtask.
  * Switch up the roles regularly. The goal is not to have the same person in the role. You should be switching so you find a rythem and have a shared contribution.
  * As navigator, your role isn't to be worrying as much about the details of the code, but to be able to take a step back and complement your pair's more tactical mode with medium-term thinking. ALlow them to focus on coding while you keep track of next steps, potential obstacles and ideas on sticky notes and discuss them after the tiny goal is done, so as not to interrupt the driver's flow.

### The Unstructured Pair Style

### The Strong Style Pairing

### Ping-Pong Pairing
This technique embraces Test-Driven Development (TDD) and is perfect when you have a clearly defined task that can be implemented in a test-driven way. It uses the Red, Green Blue technique of TDD and splits it between 2 engineers.

* "Ping": Developer A writes a failing test
* "Pong": Developer B writes the implementation to make it pass.
* Developer B then starts the next "Ping", i.e. the next failing test.

Each "Pong" can also be followed by refactoring the code together, before you move on to the next failing test.

### Backseat Navigator Style


## Tools
 * [Intellij](https://www.jetbrains.com/help/idea/code-with-me.html)
 * [VS Code](https://code.visualstudio.com/learn/collaboration/live-share)
 * [Tuple](https://tuple.app/downloads/)

## Bad Practices
 * Feeling pressured to not allow for breaks
 * Staying silent and letting one engineer contribute 
 * Not being aligned on the pairing style

## Exercise
Splitting up into groups of 2 or 3, pick a kata to work on. Some have been provided in `/katas` but feel free to use others if you'd like. As a group, agree on a pair programming style that you want to try and hop on a call to start the coding! Try and keep a consious effort to stick to your technique and not fall into the trap of 1 contributing more than another. Contributing doesn't just mean coding, it also includes questioning and suggesting improvements throughout the session.
