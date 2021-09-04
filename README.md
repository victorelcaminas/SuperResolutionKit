# SuperResolutionKit

[![CI Status](https://img.shields.io/travis/kenmaz/SuperResolutionKit.svg?style=flat)](https://travis-ci.org/kenmaz/SuperResolutionKit)
[![Version](https://img.shields.io/cocoapods/v/SuperResolutionKit.svg?style=flat)](https://cocoapods.org/pods/SuperResolutionKit)
[![License](https://img.shields.io/cocoapods/l/SuperResolutionKit.svg?style=flat)](https://cocoapods.org/pods/SuperResolutionKit)
[![Platform](https://img.shields.io/cocoapods/p/SuperResolutionKit.svg?style=flat)](https://cocoapods.org/pods/SuperResolutionKit)

Super resolution implementation with CoreML and Keras.
See my presentaiton: https://github.com/kenmaz/SuperResolutionKit

## Requirements

## Installation

SuperResolutionKit is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'SuperResolutionKit'
```

## Usage

```swift
// Using SRCNN
imageView.setSRImage(image: image)

// Using F-SRCNN (faster)
imageView.setFSRImage(image: image)
```

## Author

kenmaz, kentaro.matsumae@gmail.com

## License

SuperResolutionKit is available under the MIT license. See the LICENSE file for more info.

### CoreMLHelpers
CoreMLHelpers is copyright 2017 Matthijs Hollemans and is licensed under the terms of the [MIT license](https://github.com/hollance/CoreMLHelpers/blob/master/LICENSE.txt).
