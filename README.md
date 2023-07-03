This is my written response to a question I'm very often asked- "What programming languages should I learn?" and also "How many programming language should I learn?" I've settled a while ago on 5 _groups_ of languages that I believe are essential to getting a full view of the software engineering landscape.

1. Something in the LISP Family

You are spoiled for choice here. Common Lisp, Clojure, and Racket are good. 
LISP will teach you the "Code as Data" paradigm which will in turn teach you
macros in languages that have them and how to create good patterns/conventions 
in languages that don't. Like everything else in this list, once you learn
one member of this category, the rest sort of come to you for free. 

2. A _pure_ functional language.

The "pure" part is important here- Scala and F# won't cut it here. This really reduces your choices largely to Haskell, Elm or PureScript.
Pure functional languages have a tendency to re-wire our brains in a very eye opening way. In many ways, pure functional programming is
the platonic ideal of programming. Many other categories trend towards borrowing from this one for that reason.

3. A language without garbage collection

This used to be quite a hurdle but now options like Rust and Zig mean you have comfortable and modern ways to become familiar with a language
that is close to the metal. But also there's a ton of really great C tutorials out there. Languages without garbage collection necessarily surface
alot of things that other languages pave over with abstractions. But these details inevitably poke their head out of those abstractions, and knowing
a language in this category will help you deal with that when it happens.

4. Shitty scripting languages that companies will pay you to use

Ruby, Python, JavaScript, TypeScript, Java, the list goes on. These are all
very similar languages at the conceptual level, are all bad, some have type systems, none have _good_ type systems, and all of them will get you a job because companies want you to write them.

5. "Not a language" language

Get _really good_ at a DSL that is too narrow to really do an entire software project in. Maybe it's _technically_ turing complete
but you certainly wouldn't want to use it that way. Query languages like SQL, markup laguages like HTML/CSS, configuration and project setup like
Docker, Make. You will constantly be bombarded by having to quickly pick up these single-or-narrow purpose skills in software engineering, so it's
actually a good idea to have several of these in your back pocket- but at the very least get _really good_ with one.

BONUS:

A language that you enjoy using. Knowing something from every category above, the language that really delights becomes a true window into your thought process as a software engineer.
