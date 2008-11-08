        --------         --------  |\        /|
        |                |         | \      / |
        --------  |---|  --------  |  \    /  |
               |  |   |         |  |   \  /   |
        --------  |___|\ --------  |    \/    |
    S t a c k  a n d  S i m p l e  M e s s e n g i n g

What is SaSM?
-------------
SaSM is a programming language that is designed not to be easy to read, but to be compact.

Okay, how does it work?
-----------------------
Consider the following example:

    'hello ' > 'world\n' >
    < concat print --> hello world

What does this all mean? Well,

* 'hello ' and 'world\n' are strings.
* The > operator means to push to the stack.
* The < operator means to pull everything from the stack onto the immediate.
* Then, the 'concat' verb is operated on the immediate, which concatenates the immediate
* The 'print' verb is operated on the immediate, sending the contents of the immediate to STDOUT.
* Everything after the '--' operator is treated as a comment.

It's still not quite clear...
-----------------------------
Well, then three things to remember:

* Verbs are the words that act on things, just like in most real languages.
* The 'immediate' is the term used to describe an object passed along a chain of verbs.
* The 'stack' is like a stack of papers. When you 'push' onto the stack, you put another piece of paper, say, a report, on. But when you 'pull' from the stack, you take everything off of it and give it to someone.

Still confused? Leave a comment at this README file on GitHub (http://github.com/devyn/sasm/tree/master/README.markdown)

~ That's all folks! ~
