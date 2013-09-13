This is an experiment with multithreading in Python to provide a command line (main thread),
perform network communications (commo thread), and do some kind of computing (effort thread). The
purpose of the experiment is to consider a possible design for a game server keeping state between
several clients synchronized, and providing a canonical simulation for clients to display.

There is no intent to use the code directly in a "real" application, but the design and part of the
implementations may be taken freely. All code is intended to be in the public domain, as detailed
below under "License". You are asked to judge carefully whether the part you intend to use fits
your intended application -- no guarantees of any kind are made, and I will not be responsible if
it blows up your kitten.

License
=======

You are fully encouraged to consider this work Public Domain, or otherwise under the least strict
licensing terms available in your legal area. Do what you want with it, I'm just writing the thing
(and if you feel like letting me know it was useful to you, I'd love to hear from you).
