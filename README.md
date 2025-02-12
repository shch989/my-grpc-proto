```
protoc --go_opt=module=my-grpc-proto --go_out=. --go-grpc_out=. ./proto/hello/*.proto
```