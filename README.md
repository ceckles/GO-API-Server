## Setup
```bash
> go mod init example/GO-API-Tutorial

```
## Dep install
```bash
> go get github.com/gin-gonic/gin
```

## Run
```bash
> go run main.go
```
## Test
```bash
> curl localhost:8080/books
> curl localhost:8080/books/1
> curl localhost:8080/books --include --header "Content-Type: application/json" -d "@body.json" --request "POST"
```