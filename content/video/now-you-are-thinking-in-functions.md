---
title: "Now you're thinking in functions"
date: 2018-10-22T17:22:57+05:30
categories: ["Functional Programming", "Elm"]
tags: ["Elm Europe", "OO->FP"]
youtube: "F4fuVJNnQoo"
author: "Ian Mackenzie"
---

This talk will look at some of the lessons learned from migrating the codebase of the elm-geometry package from its object-oriented origins in C++ and Scala to its current implementation in Elm.

We’ll show how to take code that depends on various features found in object-oriented languages and rewrite that code in idiomatic Elm. For example, in a language without overloading or implicit conversions, how do you write functions that work with both vectors and unit vectors? Without inheritance, how do you share 3D transformation functionality between different types of geometry? Answering these questions carefully can require some significant “conceptual refactoring”, but often results in Elm code that is simpler, clearer and more flexible than the original! We’ll show how to take code that depends on various features found in object-oriented languages and rewrite that code in idiomatic Elm. For example, in a language without overloading or implicit conversions, how do you write functions that work with both vectors and unit vectors? Without inheritance, how do you share 3D transformation functionality between different types of geometry? Answering these questions carefully can require some significant “conceptual refactoring”, but often results in Elm code that is simpler, clearer and more flexible than the original!


Note(s):

* is v/s can - Separate what a domain type `is` & what it `can` do.