# YMTGetDeviceName
This framework is get device name from model number.

## Description
Standard UIDevice can only distinguish iPhone or iPad.  
This framework is get device name from model number.

## Installation
Use Swift Package Manager

- File > Swift Packages > Add Package Dependency
- Add https://github.com/MasamiYamate/YMTGetDeviceName
- Select "Up to Next Major" with "5.4.0"

Use Carthage

```
github "MasamiYamate/YMTGetDeviceName" ~> 5.4.0
```

Use CocoaPods with Podfile:

```
pod 'YMTGetDeviceName'
```
## How to use
### Import
```ViewController.swift
import YMTGetDeviceName
```

### Get device name
```ViewController.swift
print(YMTGetDeviceName.getDeviceName())
```

## Q&A
### What is the range of supported devices?
Supports iOS devices up to September 26, 2021 (JST)

