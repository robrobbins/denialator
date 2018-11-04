# Meme Text Generator project

We are going to learn about a few concepts while creating a program to make or recite your favorite meme texts, or maybe
make up new ones...

First we are going to learn about:

## String Type

No, not the thing you tie your shoe with or get your cat to chase - this is a computer science string. A
string to us is a series of characters contained inside a pair of quotes. It may be single quotes or
double quotes. In some languages it does not matter, in others it does. Javascript for example doesn't care if you use

    'kerfluffle'
or

    "kerfluffle"

they just have to match on each side of the word or sentence.

### Which do I use?

Depends. If the language doesn't care it's up to the progammers to decide. We refer to this as a 'style'. Companies may
have a 'style guide' that says the kind of quote to use. In our examples we will use single quotes whenever possible.

## Constants and Variables

Our program will likely have to remember stuff. Programs can remember some things by assigning them to constants or variables.
A constant represents some value that is _immutable_. That is, a value that cannot be changed once set.

    const sentence = 'I liek turtles';

now your program can repeat that sentence from memory by just asking it what the value of the constant `sentence` is. Remember,
it can't be changed though.

    sentence = '...awkward silence...'
    -> produces an error: constant value cannot be reassigned

If you think you may want to change it, use a variable

    var doge = 'Much fun, such wow...'

then

    doge = 'Much wow, such fun...'

