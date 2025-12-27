## generar modelos
~~~
protoc --proto_path=proto --go_out=pb --go_opt=paths=source_relative --go-grpc_out=pb --go-grpc_opt=paths=source_relative proto/product.proto proto/tenant.proto proto/category.proto
~~~