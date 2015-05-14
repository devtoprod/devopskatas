## What is a kata?

A kata is an exercise performed repeatedly with deliberate intent to improve with each iteration.

To paraphrase from the [Wikipedia entry on kata](http://en.wikipedia.org/wiki/kata):

The basic goal of kata is to preserve and transmit proven patterns and techniques.
By practicing in a repetitive manner the learner develops the ability to execute those patterns and techniques in a natural, reflex-like manner. Systematic practice does not mean permanently rigid. The goal is to internalize the patterns and techniques of a kata so they can be executed and adapted under different circumstances, without thought or hesitation.

## What is a DevOps kata?

In order to define a DevOps kata, we must first define DevOps. The philosophy is that you want to adopt practices that enable you to build quality and flexibility into your software. You also want to adopt a culture that enables members of your team to collaborate effectively.

Coming back to DevOps kata, perhaps it is best to start with an example:

```
Make a change to a web application without taking it down. Users must not be interrupted at any time during the change.
```

This can be solved in different ways - for example perform rolling restarts on your application server, OR
provision an entirely new server and switch over your load balancer. Each approach
has costs and benefits. Practicing them both will let you make a better informed decision the next
time such a requirement comes up.

We do these things regularly, but a kata would let you take a more systematic approach to things,
by writing down what you did and sharing it with a wider audience for feedback.

Which brings us to our next question:

## How is this different from a code kata?

## How do you specify a DevOps kata?

## How do you write about solving/practicing a DevOps kata?


## Another kata example ##

How do you ensure that your software is of high quality, when you have a large number of developers
making frequent changes to the same codebase?

The answer would be some combination of source control and continuous integration. Now there are many
concrete answers possible. Git + TravisCI, or SVN and Jenkins, or Mercurial and your homegrown CI service.
Each answer would throw up some interesting perspective on what works and what doesn't - should we use
feature branches or not, should we add code review, what kind of tests should we write and when?
