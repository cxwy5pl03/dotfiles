# Go Notes

## Workspace

- GOPATH is `~/go`
- Add `export GOPATH=$HOME/go` to shell profile

## Useful commands

- `go mod tidy` to add missing and remove unused modules
- `go test ./...` to run all tests
- `go vet` to detect suspicious constructs

## Microservices

- Use context with timeouts for HTTP handlers
- Prefer structured logging (slog) over fmt.Println
- Graceful shutdown for HTTP servers
