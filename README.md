# cljgae-template

A Leiningen template for creating useful and productive GAE apps in Clojure using the GAE Java SDK.

## Usage

    lein new cljgae-template <project name>

Creates a new appengine project on disk under dir <project name> that should run on the latest GAE. It has a few routes 
with corresponding tests which show the usage of a few appengine APIs such as 

* Google Cloud Storage (via file upload example)
* The datastore (as above)
* The cloud project API (via "/" route) 
* Asyncronous task queues / AKA appengine"push queues" (via a JSON request of a "large" list of data points)

With unit tests for each. All examples also run on the dev appserver.

## Future directions

* More comprehensive examples of task queues
* Complete Clojure idiomatic query-builder for Datastore example
* More comprehensive use of cloud storage
* Examples of other commonly used GAE apis
* ???

## License

Copyright © 2016 Peter Schwarz and Nick Bauman

Distributed under the Eclipse Public License either version 1.0 or (at your option) any later version.
