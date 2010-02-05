Erlang/OTP
==========

**Erlang** is a programming language used to build massively scalable soft
real-time systems with requirements on high availability. Some of its
uses are in telecoms, banking, e-commerce, computer telephony and
instant messaging. Erlang's runtime system has built-in support for
concurrency, distribution and fault tolerance.

**OTP** is set of Erlang libraries and design principles providing
middle-ware to develop these systems. It includes its own distributed
database, applications to interface towards other languages, debugging
and release handling tools.


You can find more information here:

[erlang.org](http://erlang.org)

Contributing to Erlang/OTP
--------------------------

Here are the [instructions for submitting patches](http://wiki.github.com/erlang/otp/submitting-patches).

In short:

* We prefer to receive proposed updates via email rather than
through a pull request. Pull requests are not practical because
we have a strict policy never to merge any untested changes to
the development branch (the only exception being **obviously** correct
changes, such as corrections of typos).

* We merge all proposed updates to the **pu** (*proposed updates*) branch,
typically within one working day.

* At least once a day, the contents of the **pu** branch will be built on
several platforms (Linux, Solaris, Mac OS X, Windows, and so on) and
automatic test suites will be run. We will email you if any problems are
found.

* If a proposed change builds and passes the tests, it will be reviewed
by one or more members of the Erlang/OTP team at Ericsson. The reviewer
may suggest improvements that are needed before the change can be accepted
and merged.

* Once or twice a week, an status email called "What's cooking in Erlang/OTP"
will be sent to the mailing list.
