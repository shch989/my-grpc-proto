```
protoc --go_opt=module=my-grpc-proto --go_out=. --go-grpc_out=. ./proto/hello/*.proto
```

protoc --go_opt=module=my-protobuf --go_out=. ./proto/basic/*.proto


protoc --go_opt=module=my-protobuf --go_out=. --go-grpc_out=. ./proto/basic/*.proto