# GiseApp

<img src="Screenshots/Frases.png" width="700">
<img src="Screenshots/Teclado.png" width="700">
<img src="Screenshots/Instrucciones.png" width="700">

I designed this app to help my aunt. She's had ALS for over a decade now and can't move any of her limbs and she can't speak either. She comunicates by blinking to certain letters and colors that her nurses say to her. She selects the letter and somehow (I dont know her method very well) forms words and sentences. 
She's been using my app for a couple of weeks now and finds it verty helpfull, especially the part of the app that lets her say specific phrases. That saves her a great amount of time that is very helpfull when she needs to go to the bathroom or do something very quickyly.

## Main feature

- [x] Helps disabled people that can't move or speak to comunicate using a specific method explained in tha about section.

## Requirements

- iOS 13+
- Xcode 12

## Installation

#### CocoaPods
You can use [CocoaPods](http://cocoapods.org/) to install `YourLibrary` by adding it to your `Podfile`:

```ruby
platform :ios, '8.0'
use_frameworks!
pod 'YourLibrary'
```

To get the full benefits import `YourLibrary` wherever you import UIKit

``` swift
import UIKit
import YourLibrary
```
#### Carthage
Create a `Cartfile` that lists the framework and run `carthage update`. Follow the [instructions](https://github.com/Carthage/Carthage#if-youre-building-for-ios) to add `$(SRCROOT)/Carthage/Build/iOS/YourLibrary.framework` to an iOS project.

```
github "yourUsername/yourlibrary"
```
#### Manually
1. Download and drop ```YourLibrary.swift``` in your project.  
2. Congratulations!  

## Usage example

```swift
import EZSwiftExtensions
ez.detectScreenShot { () -> () in
    print("User took a screen shot")
}
```
