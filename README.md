# xuuid -- Extended Universally Unique Identifiers

**_Extremely_** large UUIDs that are:

* more certainly unique,
* descriptive,
* supported by tooling for short local reference.

There is a distinction made between "hard" and "soft" data for an identifier.

"Hard" data is all of the data required for a specific identifier, -- it's unique signature.

* the type of the identifier
* identifying information
* time of creation of the identifier
* random data to ensure uniqueness

"Soft" data is supporting data such as:

* sourcing information -- a URL where information associated with the identifier can be found
* authentication information -- for verifying identity and correctness of some assertion
* "AKA"s -- information about what other identifiers are asserted to be equivalent to this identifier
* suggested short-naming
* additional descriptive information -- additional information about the thing described
* additional general information -- for example, suggestions on how to configure a system for use of the thing identified

## similar work

XUUIDs are closest to the "Tag URI" scheme.

See:

* [Wikipedia: Tag URI Scheme](https://en.wikipedia.org/wiki/Tag_URI_scheme)
* [RFC 4151](https://datatracker.ietf.org/doc/html/rfc4151)
* [Tag URI website](http://www.taguri.org/)

For example, Tim Kindberg [identifies himself](https://champignon.net/about/) as "tag:champignon.net,2000:humans:TimKindberg".  Here you can see a type ("humans"), identifying information ("TimKindberg"), and a time of creation identifier ("2000").  The tag system uses authority ("champignon.net") combined with the time to ensure uniqueness, rather than random information, though it can use random information as well.

## about the project

This is a long-term background research project of Lion Kimbro's, and has no particular timeline.

Information about the project is presently kept in a TreeLine document.  That could change with time and interest of participants.

Please contact me, or visit me on discord (["Lion's Internet Office"](https://discord.gg/QA3qFgx)) in the #programming channel if you would like to discuss this.
