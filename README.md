```
protoc --go_out=module=github.com/shch989/my-grpc-proto:. --go-grpc_out=module=github.com/shch989/my-grpc-proto:. ./proto/hello/*.proto
```

protoc --go_out=. --go-grpc_out=. hello.proto
