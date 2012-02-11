#Studio History

<i>By Hunter Dolan (<a href="http://twitter.com/hunterhdolan">@hunterhdolan</a>) & Pablo Merino (<a href="http://twitter.com/zad0xsis">@zad0xsis</a>)</i>

## What?

Studio History is a revision control system written in pure javascript. It can be used for numerous things. The basic idea of Studio History is to track changes of strings over time.

## Studio History + Delta
Studio History uses delta to keep track of string changes. This means that if I have a string that says

	Hello

and I change it to

	Hello Humans

all Studio History adds to it's history tree is

	+Humans

<i>(Note that this example has be prettified. In reality Studio History uses patch data. But the concept is the same)</i>


##Why?

We needed it for one of our upcoming applications. And we couldn't find any alternatives that we liked.

##How do I use it!!

Please read our guide in our wiki.