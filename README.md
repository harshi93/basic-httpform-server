# basic-httpform-server

This is a basic httpform server using golang 

## Building Webserver
`git clone the repo`

`cd into the cloned repository`

`mkdir static` 

`mv form.html && index.html ./static`

Run to build server binary
```go
go build
```

## Starting Webserver

Run to start webserver
```go
./go-server
```

### Accessing Webserver 

#### Home page route
`localhost:8080/`

#### Hello Page route
`localhost:8080/hello`

#### Basic Input Form route
`localhost:8080/form.html`
