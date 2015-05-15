# Devops katas

A kata is an exercise performed repeatedly with deliberate intent to improve with each iteration.

A DevOps kata is an exercise designed to make you think deeply about problems and patterns
that occur repeatedly in the world of DevOps.

## List of katas

- [Etched In Stone](katas/etched-in-stone.md)

# FAQs

## Where are the katas?

Katas are located in the [katas](katas/) directory. They all have unique names.
They are not in any particular order, feel free to start with any that you find interesting.

You can contribute your own katas. To know how, look at the [Contributing](#contributing) section.

## What is a kata?

A kata is an exercise performed repeatedly with deliberate intent to improve with each iteration.

To paraphrase from the [Wikipedia entry on kata](http://en.wikipedia.org/wiki/kata):

The basic goal of kata is to preserve and transmit proven patterns and techniques.
By practicing in a repetitive manner the learner develops the ability to execute those patterns and techniques in a natural, reflex-like manner. Systematic practice does not mean permanently rigid. The goal is to internalize the patterns and techniques of a kata so they can be executed and adapted under different circumstances, without thought or hesitation.

## What is a DevOps kata?

In order to define a DevOps kata, we must first define DevOps. The philosophy is that you want to adopt practices that enable you to build quality and flexibility into your software. You also want to adopt a culture that enables members of your team to collaborate effectively.

Coming back to DevOps kata, perhaps it is best to start with an example:

Make a change to a web application without taking it down. Users must not be interrupted at any time during the change.

This can be solved in different ways - for example perform rolling restarts on your application server, OR
provision an entirely new server and switch over your load balancer. Each approach
has costs and benefits. Practicing them both will let you make a better informed decision the next
time such a requirement comes up.

We do these things regularly, but a kata would let you take a more systematic approach to things,
by writing down what you did and sharing it with a wider audience for feedback.

## Contributing

A good DevOps kata:

- has a tangible objective
- is a common problem/pattern addressed by DevOps
- is solvable in more than one way

Please share your experiences by adding a kata and sending a pull request. This repository is built by
and for you.

## See also

[CodeKata](http://codekata.com/)

## License

CC0 1.0 Universal
