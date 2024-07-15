# ddev golang Test Project

This project starts a simple web server that listens on localhost port 3000 in the container.

The Nginx config routes to the webserver on port 3000.

## Usage

```bash
ddev start

# Check if golang is installed
ddev exec go version

# Build and start the server
ddev exec go run main.go

# Open the browser
ddev launch
```

## TODO

gopath is not configured. This requires to download all dependencies
after each `ddev start`.
