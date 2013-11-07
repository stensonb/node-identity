[![Build Status](https://travis-ci.org/stensonb/node-identity.png?branch=master)](https://travis-ci.org/stensonb/node-identity)

node-identity
=============

A node/redis based HTTP identity server, providing a Token API to manage tokens in a SOA solution.

The Token API uses JSON for all messaging, and HTTP verbs to manage tokens. 

Furthermore, this project provides a client to interface with the identity server (though, being a REST API, any HTTP client will do). 

----
# Server

----
## Usage

### GET /token
#### required params
username
password

### DELETE /token/{token_id}
#### required params
<none>
