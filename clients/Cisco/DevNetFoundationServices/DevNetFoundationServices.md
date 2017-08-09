# DevNet Foundation Services

## Summary

The DevNet Foundation Services are a collection of microservices developed by MustWin to support the internal developer web portals within Cisco.
All of the microservices are developed with Go and rely on Cassandra for data storage.

The services provide various features including a generic data store with optional schema validation and custom indexing per generic data type, a metadata service for storing and managing hierarchical data, a state service for user definable custom state machine workflow, and an authentication service for federated OAuth2 and soon SAML authentication.

All of the services use attribute based access control (ABAC) for the authorization and access control of creating, reading, updating, and deleting of data.

The primary development is done with Go, and the front end is built with React.
Kubernetes is the primary deployment target, although any container based environment can be used.


Microservices:
 - Authentication
 - Blob
 - Metadata
 - State



## Technologies

### Frontend

* React
* HTML5
* CSS3


### Backend

* Go
* ABAC [Attribute Based Access Control](https://en.wikipedia.org/wiki/Attribute-based_access_control)

### Databases / Infrastructure

* Cassandra
* Vault

### Tools/Frameworks:

* Docker
* Kubernetes





## Contributors

 - [Mike Ihbe](https://github.com/mikejihbe) [li](https://www.linkedin.com/in/mike-ihbe-a356694)
 - [Dan Eloff](https://github.com/eloff) [li]((https://www.linkedin.com/in/daniel-eloff-b0118495)
 - [Dosty Everts](https://github.com/evertsd) [li]((https://www.linkedin.com/in/dosty-everts-2616a678)
 - [John Weldon](https://github.com/johnweldon) [li]((https://www.linkedin.com/in/johnweldon)
