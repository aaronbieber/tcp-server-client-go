# A TCP Server/Client in Go #

I know, I know, there are a million of these things out there now. Well, now
there are a million and one.

I've wanted to learn Go for some time now, and while on a long holiday it felt
like the right time. Because the network libraries seemed so straightforward, I
thought I'd take a crack at a legitimate TCP client/server thing.

This project is useless for anything but demonstration, so enjoy, don't consider
it to be idiomatic or well-written, but it does work. It manages error states
fairly well, which is to say it should never panic.

# Usage #

Hey, look, it uses `flag`, how quaint!

Run the server like so:

`go run server.go -port 8000`

And then connect to it with the client like so:

`go run client.go -host localhost -port 8000`

The command line arguments shown are the default values, you can omit them to
connect to localhost on port 8000. Or, of course, you can connect to some other
host where the server is running.

# License #

This is "do whatever you want with it"-ware. There is nothing here that is
particularly novel or valuable. Obviously this software comes with no warranty
of any kind. It might cause your computer to become self-aware and destroy
you. I take no responsibility for any outcomes, Skynet or otherwise.
