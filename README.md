# gootkit-prettyprint

1. Download protoc command line compiler from: https://github.com/protocolbuffers/protobuf/releases

2. Download from this repository config.bin and protos.txt into the same subdirectory, then launch the following command:

```.
protoc.exe --decode=SpywareConfig protos.txt < config.bin > config_decoded.txt
```
