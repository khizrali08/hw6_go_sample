# go_sample

## Command list

### Fetch required Go modules

`
go mod download
`

### Build

`
go build -v ./...
`

### Run tests

`
go test -v ./...
`

### Docker build

`
docker build -t go-sample .
`

### Docker build multistage

`
docker build -t go-sample -f  Dockerfile.multistage .
`
