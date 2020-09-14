# LibreSSL XCFramework for iOS, macOS & Catalyst
A script to compile LibreSSL to an XCFramework supporting the latest OS versions

Instructions:
1. Clone:
```
git clone https://github.com/build-xcframeworks/libressl
cd libressl
```
2. Build:
```
bash libressl.sh
```

The resulting directory "output" will contain two XCFrameworks
- libssl.xcframework
- libcrypto.xcframework
