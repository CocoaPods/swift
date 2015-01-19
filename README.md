Issue tracker for CocoaPods with Swift issues.

A common question regarding CocoaPods and Swift is which OS versions are supported.

- Swift is supported on OS X 10.9 / iOS 7 and newer, as stated by Apple numerous times.
- There is no support for building static archives with Swift (see <http://openradar.appspot.com/radar?id=5536341827780608>).
- Dynamic frameworks are supported on all versions of OS X.
- Dynamic frameworks are unsupported on iOS versions prior to 8:

> ld: warning: embedded dylibs/frameworks only run on iOS 8 or later.

From this we can conclude that it is **not possible** to support Swift on any other platforms than OS X 10.9/10.10 and iOS 8.

Getting Started? Install the CocoaPods beta via `[sudo] gem install cocoapods --pre`
