# grpc-basic

ini merupakan contoh penggunaan grpc di Go

terdapat 2 service yaitu auth dan product

service auth digunakan untuk register dan login
service product digunakan untuk mengolah product seperti create product dan get product

berikut contoh APIs dalam collection go-grpc-api-gateway
https://www.postman.com/dark-escape-687754/workspace/local-project/collection/18271860-dfe9d211-4461-4806-a085-6e913034b718?action=share&creator=18271860


note
1. cek goroot dengan command line go env
2. download protoc https://github.com/protocolbuffers/protobuf (pilih Go)
3. setelah download, ekstrak filenya
4. lalu copy protoc.exe di dalam folder bin ke dalam folder bin pada point 1 $(GOROOT)/bin
5. cek protoc dengan command line protoc, nanti muncul "-IPATH, --proto_path=PATH   Specify the directory in which to search for imports..."