# Taylor's Thread Workers

### What this is
This is an attempt to build my own slimmed down of AWS Lambda to better understand the technology. 

#### Needed Components

Running functions 

* Event Loop that runs code asynchronously in function files exports.handler
* Error detection so that the loop doesn't crash if the function throws an exception
* A way to detect how much time and resources were used by the function

Event Sources

* A way for different event sources to notify our system
* A way to add the function invokation and it's parameters to the function queue

Registering functions

* A way to subscribe to events from different sources

