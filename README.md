nosudo is a simple bash script that mimics some of sudo's features.

## Features

* Supports some sudo options:
  * b,E,e,H,h,i,n,u should act approximately the same way as with sudo
  * -l always acts as if the user can run any command
  * K,k,p,U,V,v are ignored
  * A,C,g,L,P,r,S,s,t aren't implemented, nosudo exits if it encounters them
* Resolves aliases (the real sudo doesn't do it), tested in bash and zsh.
* Has a debug mode:
  * activated by setting the $DEBUG environment variable
  * logs to ~/nosudo-debug

## License

[CC0 Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/)
