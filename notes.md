* Back before Go 1.11 everything had to be stored in the GOPATH, now we can use Go Modules

* Go modules are just a collection of Go packages that are versioned together

* todo-service.proto file is our protobuf file similar to our thrift file (ECE454), it will be our IDL

* Proto compiler is OS specific, but it will compile the proto file into language specific class implementation

* use the keyword repeated for the array data structure

* HAVE to return something, no such thing as void like thrift, but theres an empty message type

* Need some sort of persistent storage so im going to use PostgreSQL

* Service implementation in pkg/service will query the db and handle the requests