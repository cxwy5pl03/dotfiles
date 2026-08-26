# Go Notes

Useful aliases and environment variables for Go development.

## Environment

- `GOPATH=$HOME/go`
- `GOBIN=$GOPATH/bin`
- Add `$GOBIN` to `PATH`.

## Aliases

- `alias gob='go build ./...'`
- `alias got='go test ./...'`
- `alias gof='gofmt -w .'`
- `alias gor='go run .'`

## Tools

Install common Go tools:

```sh
go install golang.org/x/tools/cmd/goimports@latest
go install github.com/golangci/golangci-lint/cmd/golangci-lint@latest
```

## Tips

- Use `go env -w` to set persistent environment variables.
- Keep `$GOBIN` in your `PATH` for installed binaries.
