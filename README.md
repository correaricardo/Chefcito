Chefcito
==========
Chefcito is a simple
interpreter of the [Chef programming language](http://www.dangermouse.net/esoteric/chef.html) designed by
David Morgan-Mar, with slight modifications.

What's new?
------------

#### Simple conditional statement
    Compare *ingredient* adjective-ly [into [nth] mixing bowl].
      //Block of statement
    End compare adjective-ly.

#### Show contents of the mixing bowl, any time
    Show [nth] mixing bowl.

#### Commenting
    //This is a comment.

Installation
------------
To install this module type the following:

    perl Build.PL
    ./Build
    ./Build install

On platforms that don't support the "./" notation, that would be:

    perl Build.PL
    perl Build
    perl Build install

On windows you can just open compile.bat ;)

Dependencies
------------
This module requires these other modules and libraries:

* File::Temp
* Test::More

Acknowledgments
------------
Chefcito is based on this interpreter: http://search.cpan.org/~wernermp/Acme-Chef/
