## nicedecimal (v1.0) ##

shortest string representations of erlang floats

copyright 2010 alisdair sullivan

nicedecimal is released under the terms of the [MIT][MIT] license

to build nicedecimal, use [rebar][rebar]


### api ###

nicedecimal only exports one function. `format/1` takes an erlang float as an argument and returns a printable string representation of that float that, when intepreted by another erlang process (via list_to_float, most likely), returns the same float

[rebar]: https://github.com/basho/rebar