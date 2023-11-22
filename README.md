**Protobuff**

U need to run this command in cli

- protoc -I proto proto/sso/\*.proto --go_out=./gen/go/ --go_opt=paths=source_relative --go-grpc_out=./gen/go/ --go-grpc_opt=paths=source_relative

Or if u have **Task** manager, u can run this command -
task generate
