# grpc_server

* 라이브러리 설치
	* https://grpc.io/docs/quickstart/cpp/ 참고
	```
	$ git clone -b $(curl -L https://grpc.io/release) https://github.com/grpc/grpc
	$ cd grpc
	$ git submodule update --init
	$ make

	$ cd third_party/protobuf
	$ make && sudo make install
	```
	* 예제 실행
		```
		$ cd examples/cpp/helloworld/
		$ make
		$ ./greeter_server
		#다른 터미널을 열고 아래를 실행
		$ ./greeter_client
		```
	