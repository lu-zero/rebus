rebus
=====

message bus experiment

## Dependencies

[nanomsg](http://nanomsg.org)


## Structure

ReBus is leveraging nanomsg to provide an quite portable and decently performing messaging system similar to
dbus.

Ideally a shell library will be provided to have the dbus integrations present use rebus instead of dbus.

Given that most of the heavy lifting is done by nanomsg, there is plenty of space to play with the serialization
models such as bson.
