Regex.sugar
===========
A Sugar for the [Espresso text editor][espresso] to develop complicated
[Regular Expressions][regex].

[espresso]: <http://macrabbit.com/espresso/> "The Espresso text editor, by MacRabbit"
[regex]: <http://en.wikipedia.org/wiki/Regular_Expression> "Regular Expression as defined by Wikipedia"

Using
-----
Clone this project somewhere, with the following:
    
    git clone git://github.com/elliottcable/regex.sugar.git ./Regex.sugar
    
And then link it to your syntaxes directory:
    
    mkdir -p "~/Library/Application Support/Espresso/Sugars/"
    ln -s "$(pwd)/Regex.sugar" "/Users/$(whoami)/Library/Application Support/Espresso/Sugars/"
    
