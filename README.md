```
protoc --go_out=module=github.com/shch989/my-grpc-proto:. --go-grpc_out=module=github.com/shch989/my-grpc-proto:. ./proto/bank/type/*.proto
```

```
protoc --go_out=module=github.com/shch989/my-grpc-proto:. --go-grpc_out=module=github.com/shch989/my-grpc-proto:. ./proto/hello/*.proto
```