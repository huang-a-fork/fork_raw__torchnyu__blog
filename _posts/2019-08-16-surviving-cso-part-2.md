---
title:  "Surviving NYU's Hardest CS Class: Part II"
date:   2019-08-19 9:14:36 -0700
---


## Assembly

If you're lucky, your professor won't do a lot of assembly. However,
sometimes [you pull the short
straw](https://www.youtube.com/watch?v=kVHJc26t3Gc&feature=youtu.be&t=40). Fortunately
even when professors do cover assembly, it's not in a whole lot of
depth.

When I had to learn assembly, what I figured out was to not think of
assembly as a high level language that you can just skim and
understand the gist. Instead, it's kinda like a really complicated
version of the cups and the balls. You have to keep track of how the
memory is flowing and which register has which variable. Sometimes the
compiler does some tricky sleight of hand and you have to puzzle out
what just happened.

Another important thing to remember is that assembly is just another
programming language. You can run it, you can generate it, you can
debug it, etc. A good way to read assembly is to write some C, compile
it with the `-S` flag and look at the assembly. The [Godbolt compiler
explorer](https://godbolt.org/) is a nice interactive tool for this as
well.


## Misc

Start the labs early. I definitely had to use some grace days to
submit some of my labs. Even if just the thought of the labs stresses
you out, just try to take the smallest peek at the problem
statement. Even if it's just looking at the README and jotting down a
couple notes, that'll go a long long way.

Depending on your professor and their views on collaboration, you
might want to work with a partner. Even if your professor doesn't look
kindly on collaborating on code, you can still talk to each other
about techniques and ideas.

All the standard advice for hard courses applies. Talk to your
professor. Go to tutoring. Go to office hours. Find a study buddy.

Buy a print copy of the textbook. Yeah, it's likely you won't read it,
but it's even less likely that you'd read the PDF version. You can't
flip through a PDF and print books don't have Facebook or Reddit on
them to distract you. A good trick is to find international editions
of the book. I usually try to find the Indian version, as it's
significantly cheaper (under 20 dollars) and the same exact material.

This is extremely optional and not recommended unless you have the
free time, but I'd consider learning a little Rust. Rust is a very
interesting systems language that enforces a lot of rules about memory
at compile time. It's kind of like working with an extremely anal
programmer who forces you to follow the rules with memory. If you can
pick up some Rust, I guarantee you'll get better at thinking about
memory and how to manage it. Plus it's just a fun language.

Congratulate yourself: you've read this advice and are now on the path
to passing CSO! Good luck!


--- Nicholas Yang
