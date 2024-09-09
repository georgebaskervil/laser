Laser
====

About
-----

Laser is a continuation of reia that aims to shape it into a concurrent-by-default superset of ruby. At the moment, it's mostly just the reia codebase. The focus at the moment is on upgrading the code to erlang 27.

Compiling Laser
--------------

Laser requires Erlang version R12B-3 (5.6.3) or later (changing soon). The latest version of 
Erlang is available here:

[https://www.erlang.org](erlang.org)

You'll also need Ruby and Rake installed.  To compile Laser, simply type:

   rake

After compilation is complete, you'll see the test suite run and if everything
went well it should hopefully pass.

Implementation
--------------

Here's some thoroughly interesting implementation trivia about Reia:

* Leex-based scanner
* Yecc-based grammar (a Neotoma-based branch is also available)
* Successive parse transforms convert Reia parse trees into the Erlang abstract
  format, then into BEAM/HiPE bytecode

Links
-----

* Reia Author's Blog: [http://unlimitednovelty.com/](http://unlimitednovelty.com/)
* Reia Author's Twitter: [http://twitter.com/bascule](http://twitter.com/bascule)

About the Reia Author
----------------

Reia was created by Tony Arcieri, a programmer from Denver, Colorado, USA.
Tony has a background in network services and distributed peer-to-peer 
systems. His favorite programming languages are Ruby and Erlang.
