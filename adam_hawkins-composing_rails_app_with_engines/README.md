# Composing Rails Apps with Engines

This talks covers implementing a module service layer for Rail
applications. Each service is separated into it's own engine.
Example services: Email & SMS delivery, Email import, VOIP, among
others. The services designed to be accessed over HTTP, but since they
are engines they can be mounted inside your own application or as a
separate running application. The talk also covers TDD development and
creating a generator for more components.

Important Points:

* Composable Rails applications through rails engines
* Integrating engines with other engines
* Testing engines in isolation

## Notes

We faced a problem in a previous version of our product. We had many
tightly coupled dependencies to external services. This made it a pain
to switch services and hampered our development. We ended up splitting
all these components up into different engines and running them in a
completely separate app. The architecture of our service layer allows us
to mount the engines in our own application or separately like we
decided. The talk generally covers why we made this decision and how it
turned out. It is an overview of the entire process.


## Adam Hawkins

My name is Adam Hawkins. I'm a rubyist, rails guy, and general
open source nerd. I love to contribute to open source projects I use as
well as write my own. I scratch my own itches through my open source
work. When I'm not coding I travel and enjoy trance in very heavy doses.


(Me)[https://raw.github.com/twinturbo/talks/master/headshot1.jpeg]

## On the web

- [Blog](http://broadcastingadam.com)
- [Twitter](https://twitter.com/adman65)
- [Speakerdeck](https://speakerdeck.com/u/twinturbo)


