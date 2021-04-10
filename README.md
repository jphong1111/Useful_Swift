# Useful iOS


### Content
- [Coding convention](#Coding-convention)
- [Design Pattern](#Design-Pattern)
- [UIDesign](#UIDesign)
- [API](#API)	
- [JSON](#JSON)
- [Third Party Library](#Third-Party-Library)



## Coding convention
set of guidelines for a specific programming language that recommend programming style

### Swift Style Guide

- [Swift Style Guide](https://github.com/linkedin/swift-style-guide)

### Swift Lint
The way of force you to adapt coding convention 
>otherwise project build will **FAILED**
- [Swift Lint](https://github.com/realm/SwiftLint) apply for all project:+1:

put .yml file into root folder and apply following code in Build Phases

## Design Pattern

### Delegate Pattern

```
weak var delegate: SomeProtocol?
```

### Singleton Pattern


```
class SingletonPattern {
    static let manager = SingletonPattern()
    
    private init() {}
```


## UIDesign

### HIG(Human Interface Guidelines)
- [Apple UI Kit](https://developer.apple.com/documentation/uikit)

### iOS icon 

- [icon8](https://icons8.com/) you can download icons for your **APP**

### UIdesign inspiration

- [dribble](https://dribbble.com/)
- [pinterest](https://pinterest.com/)
- [behance](https://www.behance.net/)
- [pttrns](https://pttrns.com/)
- [awwwards](https://www.awwwards.com/)
- [flickr](http://www.flickr.com/)
- [mobbin](https://mobbin.design/)



## API

### Various API Site
- [rapidAPI](www.rapidapi.com)

## JSON
JSON is a language-independent data format
> Which is relative with **KEY - VALUE** pair
```
{
    "main": [
        {
            "title": "example1",
            "body": "body example1"
        },
        {
            "title": "example2",
            "body: "body example2"
        },
    ]
}
```
### JSON parser extension for Chrome
This extension makes JSON more structable
[JSON parser pro](https://chrome.google.com/webstore/detail/json-viewer-pro/eifflpmocdbdmepbjaopkkhbfmdgijcc) **FREE** :+1:

## Third Party Library
[This github](https://github.com/vsouza/awesome-ios) contains all the popular libraries in Swift:+1:
