Regex.sugar
===========
A Sugar for the [Espresso text editor][espresso] to develop complicated
[Regular Expressions][regex]. It should support anything described in the
[reference][] provided by <http://regular-expressions.info>. In cases where a
feature is only supported by a subset of the available regular expression
engines, I attempt to support it as well as possible without conflicting with
any alternatives provided by other engines.

  [espresso]: <http://macrabbit.com/espresso/>
    "The Espresso text editor, by MacRabbit"
  [regex]: <http://en.wikipedia.org/wiki/Regular_Expression>
    "Regular Expression as defined by Wikipedia"
  [reference]: <http://regular-expressions.info/reference.html>
    "Regular Expression Reference"

Using
-----
Clone this project somewhere, with the following:

    git clone git://github.com/elliottcable/regex.sugar.git ./Regex.sugar

And then link it to your syntaxes directory:

    mkdir -p "$HOME/Library/Application Support/Espresso/Sugars/"
    ln -s "$(pwd)/Regex.sugar" "/Users/$(whoami)/Library/Application Support/Espresso/Sugars/"

This project is released for public usage under the terms of the very-permissive [ISC license][] (a
modern evolution of the MIT / BSD licenses); more information is available in [COPYING][].

   [ISC license]: <http://choosealicense.com/licenses/isc/> "Information about the ISC license"
   [COPYING]: <./COPYING.text>

TODO
----
- Write a custom Itemizer class so that capture groups can show their capture
  number in the Navigator, just like how named capture groups will be capable
  of doing.
- [Conditionals](http://regular-expressions.info/conditional.html
  "Regular Expression Conditionals")

More information
----------------
You can reach me (elliottcable, the author of this project) in the Espresso
IRC channel almost 24/7:

> [##Espresso](irc://chat.freenode.net/##Espresso) on [Freenode](http://freenode.net/ "Freenode IRC network") ([open in browser](http://widget.mibbit.com/?settings=54db06d9920299f628121bb397aaa524&server=chat.freenode.net&channel=%23%23Espresso&noServerNotices=true&noServerMotd=true&autoConnect=true "Mibbit IRC gateway for ##Espresso"))
