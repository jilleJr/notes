---
date: 2021-01-30T16:29
tags: 
  - book
---

# Righting software

A famous series of courses, workshops, podcast episodes, and books created by
the system architect #[[juval-lowy]], all carrying the same name and teaching
on the same topic: To teach the software architects of the world how to
*properly* design software systems.

The name is a pun on the phrase *"Writing software"*.

## Promises

Breaking the common misconceptions that today have become the norm:

- *"Software must have bugs"*
- *"Software always misses its deadlines"*

> "[When I'm the architect for a project] we deliver **on time** and with
> **zero defects**"
>
> J. Löwy, January 27, 2021.

## Key observations

- Features is an abstract construct that is the result from the integration, not
  from implementation.

- A software architect is a human with the same components as a hunter/gatherer
  from 10,000 years ago, and yet it works fine.

## Core concepts

Löwys proposed methods breaks down into two main categories:

1. ***How not to*** design software: [[functional-decomposition]]#
2. ***How to*** design software: [[volatility-decomposition]]#

Important to get what's wrong with today's way of designing software before
digging into how to do it properly, as it's a total shift in procedures and
mixing them does not end well.

The design is of utter most importance. But to survive the brigade of
"inevidable" bugs you need testing.

- **Unit testing**: Requirement of any project.
- **Regression testing**: Requirement to deliver zero defects.

The latter, regression testing, is not feasible nor fully achievable when
desiging by [[functional-decomposition]]#.

## Learn more

- Righting Software, <https://rightingsoftware.org/>

## References

- J. Löwy (January 27, 2021), *"Righting Software - System Design"* [Workshop],
  NDC London 2021.
