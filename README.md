# html2String
A String extension to decode HTML entities to string in Swift 2.0

## Usage

Import the html2String+Extensions.swift in your project and do the following:

```swift
let htmlString = "Fast &amp; Furious&#8482; Showdown"

let plainString = htmlString.stringByDecodingHTMLEntities
```
--> Fast &amp; Furious&#8482; Showdown

or 

```swift
let htmlString = "&#12456;&#12463;&#12473;&#12488;&#12523;&#12540;&#12497;&#12540;&#12474;"

let plainString = htmlString.stringByDecodingHTMLEntities
```
---> &#12456;&#12463;&#12473;&#12488;&#12523;&#12540;&#12497;&#12540;&#12474;

## License
This repository is licensed under the MIT license, more under
[LICENSE](LICENSE).

