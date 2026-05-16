---
title: "My Third Week in the World of IT"
date: 2026-04-04
draft: false
authors:
  - admin
tags:
  - personal
  - study
  - RUDN
categories:
  - Blog
summary: "How my third week of studying Computer Science at RUDN went"

featured: true
---

## Week Summary

This week was dedicated to **Object-Oriented Programming** in C++. The main character — the **class**. Before, I only wrote functions and structures, but now I've learned how to create my own data types that combine data and methods to work with them.

I figured out:

- how to declare a class (`class`), how it differs from `struct` (everything is `private` by default);
- what a **constructor** is (called when an object is created) and a **destructor** (called when an object is destroyed);
- why **class methods** (member functions) are needed;
- what **encapsulation** is — hiding internal details using `private` and providing access through `public`.

I also learned about the **copy constructor** and **assignment operator** — so far at the level of "they exist and can be overridden."

## Practice

I wrote a `Student` class that stores a name, age, and an array of grades. I added:

- a constructor with parameters;
- a `printInfo()` method;
- an `addGrade()` method;
- a destructor that outputs a message when an object is deleted (very useful for debugging).

Then I created several objects, put them into a vector, and sorted them by age. Everything worked — it was an amazing feeling!

We also covered **static fields** — a counter of created objects. I confirmed that it's shared across all instances.

## Impressions

At first, classes seemed like magic. Why do we need this if we have structures? But when I wrote my own small hierarchy `Shape` → `Circle`, `Rectangle` and overrode virtual methods, it clicked: OOP allows you to write **flexible and reusable code**.

The hardest part was understanding where to put `&` and where to put `*` so as not to lose the object. But by the end of the week, I was calmly passing objects by reference to methods.

I'm very happy that at RUDN, the lab sessions are structured like this: theory first, then immediately a practical task. The teacher explains not only the syntax but also why it's needed in real projects.

## Plans for Next Week

- Master **inheritance** (so far I only know the basics) and **polymorphism**.
- Understand **virtual functions** and **abstract classes**.
- Write a small project — for example, a library management system or an animal catalog.
- Solidify working with **dynamic memory** inside classes (copy constructor, destructor, assignment operator — the rule of three).

See you next week!