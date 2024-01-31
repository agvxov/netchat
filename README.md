# Netc(h)at
> minimalist webchat where the client is any generic netcat implementation

I saw someone posting about a program like this one,
I wondered how hard could it be.
Apparently,
too easy,
so I started pushing for the minimun number of characters
with which all initial features keep working.
Hence `net_chat.full.py` & `net\_chat.min.py`.

To run the server:
```Bash
$ python3 net_chat.min.py 12345
```

To join:
```Bash
$ nc 127.0.0.1 12345
```

That, or have more fun using Tor tunneling.
