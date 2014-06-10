# Bashenv
> Easy setup and management of shell environment variables

## Features

Export env files to current environment 
~~~ bash
$ \. bashenv
$ \. bashenv mac.env
~~~

Print out environment variables
~~~ bash
$ bashenv 
$ bashenv | some_script_that_reads_env
~~~

## Syntax

Syntax is very similar to bash environment syntax

~~~ bash
var_name=$(value)
~~~

## Block proposal

Would like the ability to set bashenvs based upon a block evaluation. I need to implement out some sort of syntactical sugar for this

~~~ bash

[[ $SOME_VALUE == "ASDF" ]]


~~~



