English | [简体中文](README-CN.md)

![](https://aliyunsdk-pages.alicdn.com/icons/AlibabaCloud.svg)

## Alibaba Cloud ImageSearch SDK for Swift

## Requirements

- iOS 13.3+ / macOS 10.15+
- Xcode 11.3+
- Swift 5.6

## Installation

### Carthage

To integrate `AlibabacloudImageSearch20201214` into your Xcode project using [Carthage](https://github.com/Carthage/Carthage), specify it in your `Cartfile`:

```ogdl
github "alibabacloud-sdk-swift/imagesearch-20201214" "1.1.2"
```

### Swift Package Manager

To integrate `AlibabacloudImageSearch20201214` into your Xcode project using [Swift Package Manager](https://swift.org/package-manager/) , adding `AlibabacloudImageSearch20201214` to the `dependencies` value of your `Package.swift`.

```swift
dependencies: [
    .package(url: "https://github.com/alibabacloud-sdk-swift/imagesearch-20201214.git", from: "1.1.2")
]
```

In addition, you also need to add `"AlibabacloudImageSearch20201214"` to the `dependencies` of the `target`, as follows:

```swift
.target(
    name: "<your-project-name>",
    dependencies: [
        "AlibabacloudImageSearch20201214",
    ])
```

## Issues

[Opening an Issue](https://github.com/alibabacloud-sdk-swift/imagesearch-20201214/issues/new), Issues not conforming to the guidelines may be closed immediately.

## Changelog

Detailed changes for each release are documented in the [release notes](./ChangeLog.txt).

## References

* [OpenAPI Developer Portal](https://next.api.alibabacloud.com/home)
- [Latest Release](https://github.com/alibabacloud-sdk-swift/imagesearch-20201214)

## License

[Apache-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Copyright (c) 2009-present, Alibaba Cloud All rights reserved.
