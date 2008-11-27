Regex.sugar
===========
A Sugar for the [Espresso text editor][espresso] to develop complicated
[Regular Expressions][regex]. It should support anything described in the
[reference][] provided by <http://regular-expressions.info>.

[espresso]: <http://macrabbit.com/espresso/> "The Espresso text editor, by MacRabbit"
[regex]: <http://en.wikipedia.org/wiki/Regular_Expression> "Regular Expression as defined by Wikipedia"
[reference]: <http://regular-expressions.info/reference.html> "Regular Expression Reference"

Using
-----
Clone this project somewhere, with the following:
    
    git clone git://github.com/elliottcable/regex.sugar.git ./Regex.sugar
    
And then link it to your syntaxes directory:
    
    mkdir -p "~/Library/Application Support/Espresso/Sugars/"
    ln -s "$(pwd)/Regex.sugar" "/Users/$(whoami)/Library/Application Support/Espresso/Sugars/"
    
TODO
----
- Write a custom Itemizer class so that capture groups can show their capture
  number in the Navigator, just like how named capture groups will be capable
  of doing.
- [Conditionals](http://regular-expressions.info/conditional.html "Regular Expression Conditionals")
