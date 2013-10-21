nock.jl
=======

A Nock interpreter written in Julia.

Nock is a stateless virtual machine defined in 200 words. Nock is a part of
Urbit. For more information, see the
[Urbit documentation](http://www.urbit.org/2013/08/22/Chapter-0-intro.html)
and the [formal Nock specs](http://www.urbit.org/2013/08/22/Chapter-2-nock.html).

Usage
-----

```
using Nock
nock(parse_nockdata("[42 [8 [1 0] 8 [1 6 [5 [0 7] 4 0 6] [0 6] 9 2 [0 2] [4 0 6] 0 7] 9 2 0 1]]"))
# => 41
```
