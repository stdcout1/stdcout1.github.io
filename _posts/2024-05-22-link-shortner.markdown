---
layout: post
title:  "Adventures of Link Shortning"
date:   2024-05-22 10:54:11
categories: tech
---

Recently I need to shorten some links to send to some people.
So I did what any normal person would do; I went to google.
But oh my god, do they suck.
They are riddled with ads and random ass expiry dates.
So I decided to make a better one.

## Design

Lets first talk about the stack.
I decided to use Elm for the front-end and Rust for the back-end.
You may be wondering what the heck is Elm?

### Elm

Elm is a functional language part of the Erlang family.
It is pretty fun to use for anything front-end based.
It integrates well with existing HTML and JavaScript and it has a cool pipe operator aswell: 
```elm
list |> foldl ++ "" |> length -- pipe list into the fold function then into the length function 
```

It has easy to use HTML library and easy enough web requests.

For the back-end I opted for Rust.
This language is safe and has my *favorite* web server library, Axum.
For the database, I used a simple key-value store for Rust called jammydb.

Tech-stack aside, 
