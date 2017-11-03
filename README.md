These were created by installing Protocol Buffers (protobuf), which is a compiler or sorts, from https://github.com/google/protobuf/releases and then following the below commands:
Extract .tar.gz file:
```
tar -xzf protobuf-cpp-x.x.x.tar.gz
```
cd into the extracted directory:
```
cd protobuf-x.x.x
```
Build the code:
```
./configure
make
make check
sudo make install
```
Verify that the installation was successful:
```
protoc --version
```
You may need to load it up!
```
sudo ldconfig
protoc --version
```
