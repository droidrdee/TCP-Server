# TCP-Server
Multi-threaded TCP Server
===

This codebase demonstartes multi-threaded tcp server in Golang.


## How to Run

```
$ go run main.go
```

Fire the following commands on another terminal to simulate
multiple concurrent requests.

```
$ curl http://localhost:1729 &
$ curl http://localhost:1729 &
$ curl http://localhost:1729 &
```