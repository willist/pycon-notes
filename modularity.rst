The End of Object Inheritance and the Beginning of a New Modularity
===================================================================

by Augie Fackler & Nathaniel Manista

Three Premises About Software

#. We use types for nouns
#. We express ourselves structurally
#. Most programming is parametric programming

    Modules take input that changes it's behavior in some valuable way.


Make Illegal States Unrepresentable
Make Illegal Behavioral Interactions Impossible

The right way to break code into small methods and small objects

#. Break it so that relationships are minimazed among the resulting pieces.
#. Break it so that unidirectional relationships dominate your codebase.

Do one thing and do it well.

Define types everywhere - abstract types, abstract clases

Constructors will turn into factory functions.

Module becomes responsible for instantiation

Modules will transofrm in to collections of types and functions.

Don't be afraid of winding up with a few very powerful functions.

Value types will peak out of the interface - dumb data types.

Assemble simple behaviors to get complex behaviors

"You go to war with the army you have, not the army you wish you had." - Rummy

Stateless adapters are cheap and provide clearer higher level code.

"And that's great"

If you can't define the translation leyer, defer.  You don't understand the poblem well enough.


http://code.google.com/a/google.com/p/end-of-object-inheritance/
