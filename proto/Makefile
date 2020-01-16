codegen: add.pb.go

add.pb.go: add.proto
	protoc --go_out=plugins=grpc:. add.proto

clean:
	-rm -rf add.pb.go