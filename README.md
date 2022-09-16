# Leaking Secrets on GitHub

This is just a small repository to show you something...

## I push a commit by mistake and it contains a secret

See my PR: [#1](https://github.com/Kludex/leak-secret/pull/1).

But then... I rewrote the history, and you can't see it on the interface, right?

No. You can see a message:

> Kludex force-pushed the leak-secret branch from 75bcba4 to 53178e8

If we click on 75bcba4, we are able to see: [the leaked commit](https://github.com/Kludex/leak-secret/commit/75bcba47388d6d57e6d8158bda4de28722835761).

## SOOOOO... Please, if you have leaked a secret key, token, or anything that is important...

Revoke that. Create a new one. You are not safe.
