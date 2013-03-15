Composability through Multiple Inheritence
==========================================

Goal - treat components as a black box.

Simple Input In
Simple Outout Out

Act 1
~~~~~

Composionality
    
    The meaning of a complex espression can be determined by the meaning of its components.

Unix pipes
----------

Recombinant to build complex structures.

The pipes define the rules for how things are combined.


Joe Armstrong
    
    Erlang - make components and build things by putting them together

Robert M Pirsig

    Zen and the Art of Motorcycle Maintenance


Act 2
~~~~~

Old style classes - bad

Method Resolution Order
-----------------------

Diamond Problem - which method gets resolved?

Cooperative Inheritance
-----------------------

Call init of parent

But... you have to pass arguments up the chain.  Starts to get ugly quickly.
You also need to know what happens in the base classes.
Necessary to call super in all subclasses.

Not able to use as a black box.

Mixins
------

Not meant for instantiation on their own.

Need to always add mixins first due to MRO.

.. note:
    
    Django ORM inheritance model sucks
    The Diamond Problem still exists.

.. warning:

    Django does not adhere to Liskov Substitutability Principle.

Interesting Libraries
---------------------

* dj.chain - chaining querysets
* lck.django - LSP 
