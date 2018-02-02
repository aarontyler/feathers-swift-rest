# FeathersSwiftRest

[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](#carthage) [![CocoaPods compatible](https://img.shields.io/cocoapods/v/FeathersSwiftRest.svg)](#cocoapods) [![GitHub release](https://img.shields.io/github/release/feathersjs-ecosystem/feathers-swift-rest.svg)](https://github.com/feathersjs-ecosystem/feathers-swift-rest/releases) ![Swift 4.0.x](https://img.shields.io/badge/Swift-4.0.x-orange.svg) ![platforms](https://img.shields.io/badge/platform-iOS%20%7C%20macOS%20%7C%20tvOS%20%7C%20watchOS-lightgrey.svg) [![Build Status](https://travis-ci.org/feathersjs-ecosystem/feathers-swift-rest.svg?branch=master)](https://travis-ci.org/feathersjs-ecosystem/feathers-swift-rest)

## What is FeathersSwiftRest?

FeathersSwiftRest is a ReactiveSwift REST HTTP provider for [FeathersSwift](https://github.com/feathersjs-ecosystem/feathers-swift).

## Installation

### Cocoapods
```
pod `FeathersSwiftRest`
```
### Carthage

Add the following line to your Cartfile:

```
github "feathersjs-ecosystem/feathers-swift-rest"
```

## Usage

To use FeathersSwiftRest, create an instance of `RestProvider` and initialize your FeathersSwift application:

```swift
let feathersRestApp = Feathers(provider: RestProvider(baseURL: URL(string: "https://myawesomefeathersapi.com")!))
```

That's it! Your feathers application will now support a REST API.
