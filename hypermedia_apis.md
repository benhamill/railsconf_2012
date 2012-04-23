# Hypermedia APIs
## Steve Klabnik
Slides: https://github.com/steveklabnik/hypermedia-presentation

Steve is a very smelly, very thirsty REST Jesus from just come from the desert.
;)

To change opinions, don't be aggressive. People will dig in and fight.

"Hypermedia APIs" is the new buzzword. Allows for separation between people's
idea of REST and whatever and well as having a term that actually holds meaning.

Hypermedia designs scale better and better allow change: Change a link,
consumers use the new link. Better decoupling.

Hypermedia APIs can have latency issues. Also, text-based replies can be bigger
binary replies.

Hypermedia APIs value long term good over short term efficiency. People tend to
be good at the short term and less at the long term.

'Longevity and independent evolution'

"All the ricketiness of all these things built on top of each other? ... It's
intense." -- Steve Klabnik

### HypermMedia APIs:
  * Use HTTP Properly
  * Use Hypermedia to guide folks through the business process.

### 5 Steps of Hypermedia API design
  * Evaluate business process
  * Create a state machine
  * Evaluate media types
  * Create media types
  * ???

Check out W3CLove - Validates entire sites.

### Evaluate Business Process:

* individual pages
* whole sites

### State Machine

* Some stuff. Look at the slides.

### Media Types

* JSON can't drive a Hypermedia API.
* JSON can be the basis for the format you build, though.
* Ideally, use a type that already exists. Collection+JSON is a good one.
* For a definition, you need:
  * the data
  * the hypermedia controls
* application/vnd.w3clove.validation+json (Contrived, could be
  collection+json ?)
* data elements: timestamps, what comes back, etc. Language like MAY contain,
  etc.
* Hypermedia controls: related URLs, etc. How the links are formatted. Also MAY
  contain, etc.

### Implement (Magic Step)

Check slides for response examples.
