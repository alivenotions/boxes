# Event Sourcing

* Event sourcing is the practice of modeling the system as a sequence of events.
* To adhere to the business rules, the event subset can be replayed to check if it occurred or not. This is called a projection. \(Makes sense as the actual events are not being replayed but are just being projected for checking\)
* Projection is generally done in-memory to ensure that it is not expensive.
* Building the shape that needs to be sent for the end-user is done in the background. This allows for more flexibility as the sequence can be shaped in a desired structure with less delay than fetching it from a store.

### Links

* [https://dev.to/barryosull/event-sourcing-what-it-is-and-why-its-awesome](https://dev.to/barryosull/event-sourcing-what-it-is-and-why-its-awesome)



