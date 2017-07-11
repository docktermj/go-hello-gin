# go-hello-gin

Part of a comparision of [Go HTTP routers](https://github.com/avelino/awesome-go/blob/master/README.md#routers).

1. https://gin-gonic.github.io/gin/
1. https://github.com/gin-gonic/gin

## Usage

### Invocation

```console
go-hello-gin
```

In a web browser, visit http://localhost:8080/

## Development

### Dependencies

#### Set environment variables

```console
export GOPATH="${HOME}/go"
export PATH="${PATH}:${GOPATH}/bin:/usr/local/go/bin"
export PROJECT_DIR=${GOPATH}/src/github.com/docktermj
```

#### Download project

```console
mkdir -p ${PROJECT_DIR}
cd ${PROJECT_DIR}
git clone git@github.com:docktermj/go-hello-gin.git
```

#### Download dependencies

```console
cd ${PROJECT_DIR}/go-hello-gin
make dependencies
```

### Build

#### Local build

```console
cd ${PROJECT_DIR}/go-hello-gin
make
```

The results will be in the `${GOPATH}/bin` directory.
