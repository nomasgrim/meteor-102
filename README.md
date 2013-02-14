##### _Cliff Notes, VML COE_
## [Meteor @github](https://github.com/meteor/meteor/blob/master/README.md)
> You can build a complete application in a weekend, or a sufficiently caffeinated hackathon. No longer do you need to provision server resources, or deploy API endpoints in the cloud, or manage a database, or wrangle an ORM layer, or swap back and forth between JavaScript and Ruby, or broadcast data invalidations to clients.

##### [documentation](http://docs.meteor.com/)

#### Pros
* Easy environment setup, pick and use packages as you want on the fly with easy command line 
* Live page updates. Just write your templates. They automatically update when data in the database changes. No more boilerplate redraw code to write. Supports any templating language.
* Latency compensation.
* Clean, powerful data synchronization.
* Interoperability. You can connect anything to Meteor, from native mobile apps to legacy databases to Arduinos. Just implement the simple DDP protocol.

#### Cons 
* [Meteor Packaging Issue](https://github.com/meteor/meteor/pull/516#issuecomment-12919473 "Title")
* Security
* Still hasn't release v 1.0 but neither has backbone ...

#### FAQ
* Crawlable by search engines?
> Yes. Add the "spiderable" smart package to include support for emitting static HTML to search engines, complete with valid links. The spiderable package implements Google's AJAX Crawling Specification. See the spiderable documentation for details.

#### Deploying to heroku
* [It's easy](https://github.com/jordansissel/heroku-buildpack-meteor/blob/master/README.md)

### [Meteorite](https://github.com/oortcloud/meteorite/blob/master/README.md "Title") ###
###### https://github.com/oortcloud/meteorite/blob/master/README.md
> Meteorite is a Meteor version manager and package manager. It provides an easy way to run different versions of meteor, use non-core packages, and to install packages from the [Atmosphere package repository](https://atmosphere.meteor.com/). Meteorite provides the mrt command that wraps the meteor command, and should be used in its place.

### So Why bother with Meteor?
* Beginning developers get a chance to get their hands dirty very simply.
* Great for hackathons setting a quick environment
* Running local environment just as easy, from command line w/ desired dir of app, type meteor the should be able to run from localhost:3000 by default

[Follow on meteor on Trello](https://trello.com/card/package-system-overhaul-officially-open-package-system-up-to-community/508721606e02bb9d570016ae/9)