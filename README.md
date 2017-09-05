# swift-android-sqlite
Prebuilt Android library extension for sqlite

To include in your project place something like the following in your project's Package.swift:

```
import PackageDescription

let package = Package(
    name: "libswifthello.so",
    targets: [
    ],
    dependencies: [
        .Package(url: "https://github.com/SwiftJava/java_swift.git", majorVersion: 2),
        .Package(url: "https://github.com/SwiftJava/swift-android-sqlite.git", majorVersion: 1),
        ]
)
```
