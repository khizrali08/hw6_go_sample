# Status of last deployment:<br>
<img src="https://github.com/khizrali08/hw6_go_sample/workflows/CI/badge.svg?branch=main"><br>
<img src="https://github.com/khizrali08/hw6_go_sample/workflows/CD/badge.svg?branch=main"><br>

# go_sample

## Command list

### Fetch required Go modules

```
go mod download
```

### Build

```
go build -v ./...
```

### Run tests

```
go test -v ./...
```

### Docker build

```
docker build -t go-sample .
```

### Docker build multistage

```
docker build -t go-sample -f  Dockerfile.multistage .
```
