# DocDrafts Locations

```shell
protoc --proto_path=. \
  --go_out=./doc_drafts --go_opt=paths=source_relative \
  --go-grpc_out=./doc_drafts --go-grpc_opt=paths=source_relative \
  doc_drafts.proto
```