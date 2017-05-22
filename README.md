# TSDL language definition for Sublime Text 3

This is a language definition for Sublime Text 3 to support TSDL,
[CTF](http://diamon.org/ctf)'s metadata language.

This is a `.sublime-syntax` file, so make sure your version of Sublime
Text 3 supports this format.


## Installation

Copy `TSDL.sublime-syntax` to `Packages/User` from your Sublime Text 3
configuration directory.


## Screenshots

![](http://ss.0x3b.org/daggy760.png)

![](http://ss.0x3b.org/unecstatically57.png)

![](http://ss.0x3b.org/overdrawing448.png)


## Features

* Language is automatically set with `.tsdl` files and files of which
  the first line is `/* CTF 1.` followed by a number (TSDL's signature).
* Smart syntax definition which is always aware of the current context.
* Character escaping in string literals:

  ![](http://ss.0x3b.org/acetolytic473.png)

* Specific scope for field names (different style):

  ![](http://ss.0x3b.org/cardiographs190.png)

* Specific scope for special keywords in references to fields:

  ![](http://ss.0x3b.org/spruceness335.png)

* Specific scope for the value of a `map` attribute, which is
  only recognized within an `integer` type:

  ![](http://ss.0x3b.org/polyribosome308.png)

* `typealias` and `typedef` support:

  ![](http://ss.0x3b.org/arseniosiderite103.png)

* Lots of illegal scopes to spot mistakes quickly:

  ![](http://ss.0x3b.org/openhandedness936.png)

  ![](http://ss.0x3b.org/nonphotographical504.png)

  ![](http://ss.0x3b.org/unadjunctively37.png)

  ![](http://ss.0x3b.org/undisproving660.png)
