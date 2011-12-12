Tim's Queue Server (Release Management)
=======================================

This is where we generate releases for Tim's Queue Server.

To generate a release:

    $ ./rebar get-deps
    $ ./rebar compile
    $ ./rebar generate

Your release will be located in rel/tqserver/.  Tar this up and put it
where you need it.

You can customize the listening port and SASL properties by editing
etc/app.config inside of the release directory.
