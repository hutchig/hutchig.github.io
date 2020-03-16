# Summary

This a page of notes about the idea of integrating a SmallRye;Vert.x;Netty stack
into OpenLiberty.

# Motivation

In OpenLiberty we get a lot of benefit from reusing existing software compoments where we can find
high quality implementations. 
For MicroProfile specifications a good resource is the [SmallRye project](https://smallrye.io/) which
OpenLiberty uses to implement a number of features. SmallRye Reactive Messaging is looking to make more use of
[Vert.x](https://vertx.io/) via [#423](https://github.com/smallrye/smallrye-reactive-messaging/issues/423) and
OpenLiberty is looking to make more use of SmallRye via [#10813](https://github.com/OpenLiberty/open-liberty/issues/10813)

If we want to explore converging OpenLiberty towards a common codebase with SmallRye, Quarkus and Vert.x/Netty then
we need to take a close look at what this means in detail and what actions, if any, we want to take
towards it in OpenLiberty.
