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

## Functions

This is some piece of a program that does something specific. They should have some notably action-y kinda names

    sayStuff()

or

    useFlextape()

Note how the words were smushed together with the next word beginning with a capital letter. This is called 'camel casing'. There's
LOTS of variations of this in programming languages. Basically its because you can't use any white space and you want some way to
show the different words (and you want to be _specific_ remember). Some languages may want you to start your function names with 
an upper case

    UseFlexTape()

This is called many things: 'Pascal' casing (for us old school dudes), 'proper' casing, 'class' casing, etc... Doesn't really matter what
you call it you just have to know which you are supposed to do. Again, this may be 'style' as the language may not care. 

Python and Ruby languages will often use 'snake' casing - that is, use underscores to seperate words and don't use any caps

    use_flex_tape()

### About those parenthesis

Since functions do something specific, sometimes you need to give them some piece of data. Inside the parens is where you give it to them. Think of 
the space inside the parens like an envelope that you can mail shit to the function with. We call the stuff you put in there 'arguments'

    sayStuff(sentence)

You'll see more about how this works in the code examples

## Methods

Methods are just functions that belong to some object. We haven't really discussed objects yet but it's a pretty easy concept to grok 
(grok is prog talk for understand).

You know how functions are pieces of a program that do specific things? Well, you way want to group some functions together inside an 'object'
(like a class - there are many kinds of 'objects') that does a few specific things. For example, the methods

    meow() {
      return 'RAWRRRRRRRR!!!!';
    }

and

    tripMyMom() {...}

could make more sense if they were contained within an object that they described, like:

    class BlueTheCat {
      meow() { ... }
      tripMyMom() {...}
    }

It makes sense that those methods belong to BlueTheCat cuz _he does them_. This is called *Encapsulation*. Since that function now belongs to
something it is called a *method* of that *object* and would be `called` by

    BlueTheCat.meow()

and of course,

    BlueTheCat.tripMyMom()
