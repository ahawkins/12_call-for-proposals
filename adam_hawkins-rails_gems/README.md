# Gem'ing Rails

Rails provides many integrations points. A lot of them seem like black
magic. This talk aims to clear it up. It will demonstrate that most of
what gems do is standard. However sometimes it will get fancy. This talk
will cover some edge cases and complicated integrations as well.

* Connect your gem using a Railtie
* Bundle app/controllers/views/assets
* Using `ActiveSupport.on_load` callbacks
* Generating one off rails applications for testing your rails
  independent gems
* Edge cases in the `rails plugin` generator
* Testing engines/gems
* Gemming best practices
* Integrating with other common gems (ex: Resque)

## Notes

This talk sums up my experience writing a ton of gems for business and
open source users.

Here's my list:

* Cashier (Tag based caching for Rails)
* HttpLog (Log incoming HTTP requests to MongoDB)
* Harness (Metric Logging using ActiveSupport::Notifications)
* Radium.io (Integration for our Radium.io platform)
* A ton of various gems for internal and private use


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


